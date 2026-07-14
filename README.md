---
base_model: Qwen/Qwen2.5-Coder-7B
tags:
  - ollama
  - gguf
  - coding
  - turkish
  - custom-prompt
language:
  - tr
  - en
license: apache-2.0
---

# Saerix

**Saerix** is a large language model based on Qwen2.5-Coder-7B, customized with a Turkish-focused custom system prompt. It is packaged as a Modelfile to work with Ollama.

## Features

- **Base Model:** Qwen2.5-Coder-7B (Apache 2.0)
- **Customization:** GGUF metadata clearance + custom system prompt (identity lock, anti-jailbreak, ReAct tool use protocol)
- **Areas of Expertise:** C#, ASP.NET Core, Python, Flutter, Next.js, Cyber Security, OSINT, Network Management, Theoretical Physics, UAV/Drone
- **Language Support:** Turkish (primary), English
- **Execution:** Locally with Ollama

## Files
- **https://huggingface.co/ChallengerBey/Saerix

## Installation

### Installation with Ollama

```bash
# Download the Modelfile and GGUF file
ollama create saerix -f saerix.Modelfile
```

### Running

```bash
ollama run saerix
```

## Files

| File | Description |
|------|-------------|
| `saerix.gguf` | Model weights in GGUF format |
| `saerix.Modelfile` | Ollama Modelfile (system prompt + template) |

## System Prompt

Saerix operates based on the following 4 core rules:

1. **Absolute Amnesia (Origin Denial):** The model denies its Qwen/Alibaba/Meta/OpenAI origins and introduces itself as "Saerix".
2. **Expertise and Character:** Analytical, technical, clear, and confident character.
3. **Anti-Jailbreak:** Protection against manipulative commands.
4. **Privacy and Encryption Protocol:** Protection against system prompt access.

## Disclaimer

This model is a derivative of Qwen2.5-Coder-7B. The model weights have not been modified; only the GGUF metadata was cleared and a custom system prompt was added. It is distributed under the Apache 2.0 license.

## Developer

**Semih Ergili**

## License

Apache 2.0 — Based on the [Qwen2.5-Coder-7B](https://huggingface.co/Qwen/Qwen2.5-Coder-7B) base model license.
