# Misty✨

Meet **Misty** — your AI companion for all things TTRPG! 🎲

[What it can do - Demo - Overview]

## Quickstart 🚀

### Colab

[![Start for Free](https://img.shields.io/badge/Start%20for%20Free%20on-Colab-brightgreen?style=for-the-badge&logo=google-colab)](https://colab.research.google.com/drive/1GxO1RO-WKDh3MV9KcupjJ1FoOLlESL9z?usp=sharing)

### Local Installation

1. Download [Ollama](https://ollama.com/).
2. Run the following command in your terminal:
   ```bash
   ollama run mltheuser/misty-slim
   ```
3. Start chatting with Misty!

## Model Cards 🧠

### Misty-Slim

```bash
ollama run mltheuser/misty-slim
```

|     |                                                             |
|----------------|------------------------------------------------------------------------------|
| **Name**       | Misty-Slim                                                                   |
| **Version**    | `v1.0` <br> *Released: 08.09.2024*                                           |
| **Base Model** | [Meta-Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct) |
| **Size**       | 8 billion parameters                                                        |
| **Context**    | 8k tokens                                                                    |
| **Max Output**    | 2k tokens                                                                    |
| **Training**   | Fine-tuned on 8 million tokens of high-quality chat data                     |

##### Performance Comparison 📊

![Performance Comparison](https://via.placeholder.com/600x300?text=Performance+Comparison+Coming+Soon)

## Training Process 🛠️

Here's a brief overview of how Misty was trained:

1. **Data Collection**: We gather raw data from freely accessible sources such as blogs, wikis, homebrew content, and game transcripts.
2. **Data Transformation**: The raw data is trasnformed and aligned using a state-of-the-art LLM, following a method similar to [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html).
3. **Continued Pretraining**: We perform [continued pretraining](https://docs.unsloth.ai/basics/continued-pretraining) on a smaller open-source model.
4. **Model Iterations**: The collected training data is removed, and new up-to-date data is collected for the next model iteration.
