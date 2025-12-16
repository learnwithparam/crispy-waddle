# Practical Prompt Engineering Workshop

Master the art of communicating with AI using industry-standard techniques.

This workshop is a hands-on guide to prompt engineering, taking you from basic instructions to complex chaining and reasoning patterns.

## 🌟 What You'll Learn

Through 10 interactive Jupyter notebooks, you'll master:

1.  **Foundations**: Basics of Context, Task, and Format.
2.  **Techniques**: Role prompting, Few-Shot learning, and Chain-of-Thought.
3.  **Optimization**: Reducing hallucinations and formatting output.
4.  **Advanced Flows**: Chaining prompts and building complex "Mega-Prompts".

## 📚 Notebook Guide

| #  | Notebook | Focus | What You'll Build |
|----|----------|-------|-------------------|
| **01** | [Basic Prompting](01-basic-prompting.ipynb) | Context, Task, Format | A Napa Valley Trip Planner |
| **02** | [Clear Instructions](02-clear-instructions.ipynb) | Specificity, Constraints | A Smart Calendar Assistant |
| **03** | [Role Prompting](03-role-prompting.ipynb) | Personas, Tone | A Sarcastic Tech Support Bot |
| **04** | [Separating Data](04-separating-data.ipynb) | Delimiters, Security | A Customer Feedback Analyzer |
| **05** | [Formatting Output](05-formatting-output.ipynb) | JSON, Markdown, CSV | A Movie Recommender API |
| **06** | [Chain of Thought](06-chain-of-thought.ipynb) | Reasoning, Steps | A Math & logic problem solver |
| **07** | [Few-Shot Prompting](07-few-shot-prompting.ipynb) | Examples, Patterns | A Sentiment Classifier |
| **08** | [Avoiding Hallucinations](08-avoiding-hallucinations.ipynb) | Fact-checking, "I don't know" | A Faithful Q&A Bot |
| **09** | [Complex Prompts](09-complex-prompts.ipynb) | Modular Prompts, Rules | A Board Game Referee |
| **10** | [Chaining Prompts](10-chaining-prompts.ipynb) | Pipelines, Workflows | An Interactive Story Generator |

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- `uv` (will be installed automatically if using `make setup`)
- API key for **Google Gemini** (Recommended, Free Tier available) or OpenAI/Anthropic.

### Fast Track (5 minutes)

1.  **Get your API key**: [Google AI Studio](https://aistudio.google.com/apikey)
2.  **Setup & Run**:
    ```bash
    make dev
    ```
3.  **Configure**: The first time you run it, it will create `.env`. **Edit `.env` and add your API Key**.
4.  **Start Learning**: Open `01-basic-prompting.ipynb` at [http://localhost:8888](http://localhost:8888)

## 🛠️ Tools Used

- **[LiteLLM](https://docs.litellm.ai/)**: A universal interface for calling any AI model (Gemini, GPT-4, Claude, etc.) using a standard format.
- **JupyterLab**: Interactive coding environment.

## 🤝 Contributing

Found a typo or have a better example? Open an issue or submit a PR!
