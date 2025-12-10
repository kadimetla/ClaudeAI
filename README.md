![GitHub](https://img.shields.io/github/license/DataForScience/ClaudeAI)
[![Twitter @data4sci](https://img.shields.io/twitter/follow/data4sci)](https://twitter.com/intent/follow?screen_name=data4sci)
![GitHub top language](https://img.shields.io/github/languages/top/DataForScience/ClaudeAI)
![GitHub repo size](https://img.shields.io/github/repo-size/DataForScience/ClaudeAI)
![GitHub last commit](https://img.shields.io/github/last-commit/DataForScience/ClaudeAI)

[![Data For Science Substack](https://img.shields.io/badge/Data_For_Science-Subscribe-blue)](https://graphs4sci.substack.com/)
        [![Data Science Briefing](https://img.shields.io/badge/Data_Science_Briefing-Subscribe-blue)](https://data4science.kit.com/a63d4cc8d9)

# Claude API for Python Developers

Anthropic has quickly become one of the leaders in generative AI foundation models. Anthropic’s Claude family of models (Haiku, Sonnet, and Opus) have proven to be able to process various visual formats, a high degree of accuracy, generate high-quality code all while keeping hallucinations under control.

In this course, we will introduce the main concepts behind this class of models and how their functionality is made accessible through the Anthropic API. We will build example applications to illustrate the use of each of these tools and how they can be composed and highlight when to use each model to obtain high-quality outputs at the lowest cost.

## References

- [Neural Networks and Deep Learning](https://amzn.to/48rZn9X)
- [What is ChatGPT doing...](https://amzn.to/3LBRdBY)
- [Introduction to Natural Language Processing](https://amzn.to/3ZMnTih)
- [AI and Machine Learning for Coders](https://amzn.to/3KjB5W4)
- [Generative Deep Learning](https://amzn.to/3t8PuxM)
- [Developing Apps with GPT-4 and ChatGPT](https://amzn.to/3RHRkQa)
- [Transformers for Natural Language Processing ](https://amzn.to/46kOo02)

## Contents

This tutorial is divided into five parts:


### 1. **Generative AI and Anthropic**
_Introduction to generative AI concepts._
- Basic Principles
- Transformers
- Large Language Models
- Temperature
- Hallucinations
- Image Models
- API Structure

Notebook: [1. Generative AI.ipynb](1. Generative AI.ipynb)

### 2. **Claude Models**
_Getting started with the Claude API._
- Basic Usage
- Input Formatting
- Multi-Step Prompts
- Document Summarization

Notebook: [2. Claude Models.ipynb](2. Claude Models.ipynb)

### 3. **Embeddings**
_Working with text embeddings using Voyage AI_
- Understanding Embeddings
- Questing Answering
- Recommendations
- Long Texts

Notebook: [3. Embeddings.ipynb](3. Embeddings.ipynb)

### 4. **Tools and Agents**
_Implementing function calling with Claude._
- Tool Overview
- Structured Outputs
- Choosing the Right Tool
- Workflow

Notebook: [4. Tools.ipynb](4. Tools.ipynb)

### 5. **Code Generation and Explanation**
_Best practices for prompting Claude to write and analyze code._
- Generating Code from a Prompt
- Explaining Existing Code
- Generating Comments

Notebook: [5. Code Generation.ipynb](5. Code Generation.ipynb)

## Environment Setup

This project manages dependencies using `uv` (recommended) or standard `pip`.

### Prerequisites

- Python 3.13 or higher (as specified in `pyproject.toml`)

### Option 1: Using `uv` (Recommended)

This repository includes a `uv.lock` file for reproducible environments.

1. **Install uv**: Follow instructions at [docs.astral.sh/uv](https://docs.astral.sh/uv/).
2. **Sync dependencies**:
   ```bash
   uv sync
   ```
3. **Run Jupyter**:
   ```bash
   uv run jupyter notebook
   ```

### Option 2: Using `pip`

You can install the dependencies directly from the `pyproject.toml` file.

```bash
pip install .
```

## Author

<table border="0">
 <tr>
    <td>
      <img src="data/bgoncalves.png" alt="Bruno Gonçalves" width="150" height="150" style="border-radius: 50%; object-fit: cover;">
    </td>
    <td>
      <h2>Bruno Gonçalves</h2>
      <h3>Data For Science, Inc.</h3>
      <p>
            Web: <a href="http://www.data4sci.com/">www.data4sci.com</a><br>
            Twitter/X: <a href="https://twitter.com/bgoncalves">@bgoncalves</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/bmtgoncalves/">@bmtgoncalves</a><br>
            Email: <a href="info@data4sci.com">info@data4sci.com</a><br>
            Schedule a Call: <a href="https://data4sci.com/call">https://data4sci.com/call</a>
      </p>
    </td>
 </tr>
</table>