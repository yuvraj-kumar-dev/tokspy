# tokspy 🚧

**tokspy** is a lightweight Python library for counting tokens and estimating the cost of prompts for LLM models.

> 🚧 This project is currently under development. v0.1 will focus on supporting OpenAI models using `tiktoken`.

---

## Features

- 🔢 Token counting for GPT-3.5 and GPT-4
- 💸 Cost estimation based on prompt size
- ⚡ Powered by OpenAI's `tiktoken` tokenizer

---

## Installation

> Will be available on PyPI soon. For now:

```bash
git clone https://github.com/yuvraj-kumar-dev/tokspy.git
cd tokspy
pip install -e .
````

---

## Usage

```python
from tokspy import count_tokens, estimate_cost

text = "Hello, how are you today?"
tokens = count_tokens(text, model="gpt-3.5-turbo")
cost = estimate_cost(text, model="gpt-3.5-turbo")

print(f"Tokens: {tokens}")
print(f"Estimated Cost: ${cost}")
```

---

## 🚀 Roadmap

* [x] Token counter (OpenAI models)
* [x] Cost estimator
* [ ] CLI support
* [ ] Support for Anthropic / Mistral / LLaMA
* [ ] Model-agnostic tokenizer plug-in system
* [ ] PyPI + TestPyPI release

---

## 📄 License

MIT License © 2025

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to help improve `tokspy`.

