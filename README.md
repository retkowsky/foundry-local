# Foundry Local 🚀

<p align="center">
  <img src="foundrylocal.jpg" width="800"/>
</p>

**Foundry Local** is an on-device AI inference solution that lets you run AI models locally through a **CLI**, **SDK**, or **REST API**. This repository provides a collection of Jupyter Notebook tutorials to help you get started and explore advanced capabilities.

🌐 **Website**: [www.foundrylocal.ai](https://www.foundrylocal.ai/)

---

## 📚 Notebooks

| # | Notebook | Description |
|---|----------|-------------|
| 01 | [Getting Started with Foundry Local](01%20Getting%20Started%20with%20Foundry%20Local.ipynb) | Introduction to Foundry Local — installation, setup, and running your first local model |
| 02 | [Foundry Local Chat Completions](02%20Foundry%20Local%20chat%20completions.ipynb) | Using the chat completions API to interact with local models |
| 03 | [Foundry Local Practical Applications](03%20Foundry%20Local%20Practical%20Applications.ipynb) | Real-world use cases and practical examples with Foundry Local |
| 04 | [Foundry Local Mistral 7B](04%20Foundry%20Local%20Mistral7b.ipynb) | Running and interacting with the Mistral 7B model locally |
| 05 | [Advanced Function Calling with Foundry Local](05%20Advanced%20Function%20Calling%20with%20Foundry%20Local.ipynb) | Implementing advanced function calling and tool use with local models |
| 06 | [Deploying Custom Models with Microsoft Olive and Foundry Local](06%20Deploying%20Custom%20Models%20with%20Microsoft%20Olive%20and%20Foundry%20Local.ipynb) | Optimizing and deploying custom models using Microsoft Olive |

---

## 🖼️ Screenshots

<p align="center">
  <img src="screenshot1.jpg" width="800"/><br/><br/>
  <img src="screenshot2.jpg" width="800"/><br/><br/>
  <img src="screenshot3.jpg" width="800"/><br/><br/>
  <img src="screenshot4.jpg" width="800"/><br/><br/>
  <img src="screenshot5.jpg" width="800"/>
</p>

---

## 📖 Documentation

The official Foundry Local documentation is available at **[www.foundrylocal.ai](https://www.foundrylocal.ai/)** and covers everything you need to get started and build on-device AI applications.

### Key Documentation Resources

| Resource | Link | Description |
|----------|------|-------------|
| 🌐 Official Website | [foundrylocal.ai](https://www.foundrylocal.ai/) | Main homepage with overview, downloads, and getting started guides |
| 📘 Microsoft Learn | [Foundry Local on Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-local/what-is-foundry-local) | In-depth documentation including concepts, quickstarts, and API references |
| 🚀 Getting Started Guide | [Get Started with Foundry Local](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-local/get-started) | Step-by-step guide to install and run your first model |

### What You'll Find in the Docs

- **Installation & Setup** — How to install Foundry Local on Windows, macOS, and servers
- **CLI Reference** — Full command-line interface documentation (`foundry model list`, `foundry model run`, etc.)
- **SDK Integration** — Python, JavaScript, and .NET SDK guides with code examples
- **REST API** — OpenAI-compatible REST API reference for seamless integration
- **Hardware Optimization** — How Foundry Local auto-detects and optimizes for your hardware (NVIDIA/AMD GPU, Apple Silicon, NPU, CPU)
- **Custom Model Deployment** — Guide to converting and deploying your own models using Microsoft Olive

---

## 🤖 Available Models

Foundry Local provides a curated catalog of **pre-optimized, open-source AI models** ready to run on your device. Browse the full model catalog at **[foundrylocal.ai/models](https://www.foundrylocal.ai/models)**.

### Featured Models

| Model | Parameters | Use Cases |
|-------|-----------|-----------|
| **Microsoft Phi 4** | ~14B | Complex reasoning, analysis, code generation |
| **Microsoft Phi 4 Mini** | ~3.8B | General chat, coding, lightweight tasks |
| **Microsoft Phi 4 Reasoning** | ~14B | Advanced multi-step reasoning |
| **Microsoft Phi 4 Reasoning Mini** | ~3.8B | Lightweight reasoning tasks |
| **Microsoft Phi 3.5 Mini** | ~3.8B | General-purpose chat and instruction following |
| **Mistral 7B** | ~7B | General chat, text generation, analysis |
| **Qwen 2.5** | 0.5B–1.5B+ | Multilingual chat, coding, instruction following |

> 💡 The model catalog is regularly updated. Visit [foundrylocal.ai/models](https://www.foundrylocal.ai/models) for the latest available models.

### Hardware-Optimized Variants

Foundry Local automatically detects your hardware and downloads the **best-optimized variant** for your device:

- 🟢 **NVIDIA GPU** — CUDA-accelerated ONNX models
- 🔴 **AMD GPU** — DirectML-optimized models
- 🍎 **Apple Silicon** — Metal-accelerated models for M-series chips
- 🔵 **Intel/Qualcomm NPU** — Neural Processing Unit optimized models
- 💻 **CPU** — Quantized INT4/INT8 models for CPU-only inference

### Model Management CLI

```bash
# List all available models in the catalog
foundry model list

# Get detailed info about a specific model
foundry model info <model-alias>

# Download and run a model
foundry model run <model-alias>

# Remove a cached model
foundry model remove <model-alias>
```

### Bring Your Own Models

You can also deploy **custom models** from Hugging Face by converting them to ONNX format using [Microsoft Olive](https://github.com/microsoft/olive). See [Notebook 06](06%20Deploying%20Custom%20Models%20with%20Microsoft%20Olive%20and%20Foundry%20Local.ipynb) for a complete walkthrough.

A reference list of models is also available in this repository: 📊 [models.xlsx](models.xlsx)

---

## ⚙️ Getting Started

### Prerequisites

- **Python 3.10+**
- **Foundry Local** installed — see [foundrylocal.ai](https://www.foundrylocal.ai/) for installation instructions
- **Jupyter Notebook** or **JupyterLab**

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/retkowsky/foundry-local.git
   cd foundry-local
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter and open any notebook:
   ```bash
   jupyter notebook
   ```

---

## 🔑 Key Dependencies

| Package | Purpose |
|---------|---------|
| `foundry-local` | Core Foundry Local package |
| `foundry-local-sdk` | Foundry Local Python SDK |
| `openai` | OpenAI-compatible API client |
| `onnxruntime` / `onnxruntime-genai` | ONNX Runtime for model inference |
| `olive-ai` | Microsoft Olive for model optimization |
| `transformers` | Hugging Face Transformers |
| `torch` | PyTorch |

---

## 🏷️ Topics

`edge` · `foundry-local` · `genai` · `microsoft` · `microsoft-foundry`

---

## 📄 Resources

- 🌐 [Foundry Local Website](https://www.foundrylocal.ai/)
- 📖 [Foundry Local Documentation](https://www.foundrylocal.ai/)
- 🤖 [Available Models Catalog](https://www.foundrylocal.ai/models)
- 📘 [Microsoft Learn — Foundry Local](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-local/what-is-foundry-local)
- 📊 [Models Reference (Excel)](models.xlsx)