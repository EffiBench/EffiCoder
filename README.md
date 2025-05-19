# 🌟 EffiCoder: Enhancing Code Generation in Large Language Models through Efficiency-Aware Fine-tuning

## 🚀 Installation

```bash
cd EffiCoder
pip install -r requirements.txt
cd LLaMA-Factory
pip install -e ".[torch,metrics]"
```

## 🔧 Fine-tune LLMs with EffiCoder

We have provided the EffiCoder dataset in `EffiCoder/LLaMA-Factory/data/efficoder.json`, so we can directly use SFT and other methods to finetune LLMs.

> Replace `{your_directory_path}` with the **absolute path** to the directory where you have placed `EffiCoder/datasets/efficoder.json` in `EffiCoder/LLaMA-Factory/data/dataset_info.json`.

```bash
cd EffiCoder/LLaMA-Factory
bash run.sh
```

## ⚡ VLLM Inference

```bash
cd EffiCoder/scripts
bash run.sh
```

## 📊 Report Efficiency and pass\@1 Results

```bash
cd EffiCoder/src
python code_efficiency_calculator.py
python calculate_memory_usage.py
```

---

Happy tuning! 🎉 Feel free to open an issue if you encounter any problems. 🛠️
