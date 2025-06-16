# Misty ✨

**Your AI companion for all things Tabletop RPG.**

Misty is a specialized AI designed with a deep, accurate knowledge of TTRPG domains like Dungeons & Dragons 5e, Pathfinder, and more. Built with a custom RAG (Retrieval-Augmented Generation) pipeline, Misty provides detailed and context-aware answers to your TTRPG questions.

<p align="center">
  <a href="https://chati-836177676205.us-central1.run.app/" target="_blank" rel="noreferrer noopener">
    <img src="https://img.shields.io/badge/Try%20the%20Live%20Demo-Web%20App-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQxIDAtOC0zLjU5LTgtOHMzLjU5LTggOC04IDggMy41OSA4IDhzLTMuNTkgOC04IDh6bS0xLTNWOWgydjZIMTF6bTAgNHYtMmgydjJIMTEiLz48L3N2Zz4=" />
  </a>
  &nbsp;
  <a href="https://colab.research.google.com/drive/1GxO1RO-WKDh3MV9KcupjJ1FoOLlESL9z?usp=sharing" target="_blank" rel="noreferrer noopener">
    <img src="https://img.shields.io/badge/Open%20in-Colab-brightgreen?style=for-the-badge&logo=google-colab" />
  </a>
  &nbsp;
  <a href="https://ollama.com/mltheuser/llama-misty-slim" target="_blank" rel="noreferrer noopener">
    <img src="https://img.shields.io/badge/Download%20from-Ollama-lightgrey?style=for-the-badge&logo=ollama" />
  </a>
</p>

---

## ✨ Example in Action

Here's a demonstration of Misty's ability to provide specific, actionable information from a well-known D&D module.

**User:**
> In the Cragmaw Hideout (LMOP) how do you get from Klarg's cave to the place where Sildar is held captive? Walk me through the route.

**Misty:**
> Okay, let's trace the routes from Klarg's Cave (Area H8) to the Goblin Den where Sildar is held (Area H6) in the Cragmaw Hideout, based on the map. There are two main ways to get there:
>
> **Route 1: Via the Twin Pools and the Bridge**
>
> 1.  Start in **Klarg's Cave (H8)**.
> 2.  Take the **large opening leading north** down a set of natural stone steps.
> 3.  This leads you into the **Twin Pools Cave (H7)**.
> 4.  From H7, take one of the **two smaller passages leading west**.
> 5.  These passages lead to the **Overpass/Bridge area (H5)**.
> 6.  Cross the **bridge** over the stream.
> 7.  After crossing the bridge, the passage continues **west** directly into the **Goblin Den (H6)**.
>
> **Route 2: Via the Natural Chimney and Kennel**
>
> 1.  Start in **Klarg's Cave (H8)**.
> 2.  Locate the **narrow opening in the western wall**, which is a natural chimney.
> 3.  Descend this **chimney** (it's a 30-foot drop/climb) to reach the **Kennel (H3)**.
> 4.  From H3, take the passage leading **north**.
> 5.  This passage is the **Steep Passage (H4)**.
> 6.  Continue **north** through the Steep Passage.
> 7.  The passage opens up into the **Goblin Den (H6)**.
>
> Both routes will get you from Klarg's Cave to the Goblin Den where Sildar is imprisoned. The first route is longer but involves walking through caves and across a bridge, while the second route is more direct but requires descending a chimney.

## 🚀 Quickstart

Get up and running with Misty in minutes. The easiest way to start is with Google Colab or by running it locally with Ollama.

### Option 1: Run on Google Colab (Free)

Click the button below to launch a free, ready-to-use notebook.

<a href="https://colab.research.google.com/drive/1GxO1RO-WKDh3MV9KcupjJ1FoOLlESL9z?usp=sharing" target="_blank" rel="noreferrer noopener">
  <img src="https://img.shields.io/badge/Start%20for%20Free%20on-Colab-brightgreen?style=for-the-badge&logo=google-colab" />
</a>

### Option 2: Run Locally with Ollama

If you have [Ollama](https://ollama.com/) installed, you can download and run Misty with a single command.

1.  **Install Ollama:** If you don't have it, [download it here](https://ollama.com/).
2.  **Run Misty:** Open your terminal and run the following command:
    ```bash
    ollama run mltheuser/llama-misty-slim
    ```
3.  **Start Chatting:** That's it! You can now interact with Misty directly in your terminal.

## 🧠 Model Details: Misty-Slim

This is the freely available, distilled version of Misty. It's built for efficient local use without sacrificing quality on core TTRPG knowledge.

| Attribute      | Details                                                                                                                                  |
| :------------- | :--------------------------------------------------------------------------------------------------------------------------------------- |
| **Name**       | `Misty-Slim`                                                                                                                             |
| **Version**    | `v1.0` (Released: 2024-08-09)                                                                                                            |
| **Base Model** | [Meta-Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Meta-Llama-3.1-8B-Instruct)                                                 |
| **License**    | Llama 3.1 is licensed under the [Llama 3.1 Community License](https://github.com/meta-llama/llama-models/blob/main/models/llama3_1/LICENSE). |
| **Parameters** | 8 Billion                                                                                                                                |
| **Context Size** | 8,192 tokens                                                                                                                            |
| **Max Output** | 2,048 tokens                                                                                                                             |
| **Training Data** | 8 million TTRPG-focused tokens 📚                                                                                                      |

## 📊 Performance

Here's a quick comparison showing how `Misty-Slim` stacks up against other models in its class on a TTRPG-focused benchmark.

<img width="607" alt="Misty-Slim performance comparison chart" src="https://github.com/user-attachments/assets/b8da0c11-a190-44e7-a6e2-8284ca4ee605">

## 🛠️ How Misty Learns

Misty's expertise comes from a carefully designed training process:

1.  **Curating Knowledge:** We gather high-quality data from a wide range of freely accessible TTRPG sources, including blogs, wikis, homebrew content, and actual-play transcripts.
2.  **Instruction Tuning:** This raw knowledge is transformed into a structured, instruction-following format. We use a powerful LLM to generate high-quality question-and-answer pairs, similar to the method used for [Stanford's Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html).
3.  **Specialized Pre-training:** Finally, we perform [continued pre-training](https://docs.unsloth.ai/basics/continued-pretraining) on the base model, further refining its understanding and response patterns specifically for the TTRPG domain.
