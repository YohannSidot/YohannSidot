# Hey, I'm Yohann 👋

Cybersecurity student building **Senthex** an AI firewall for LLM API calls.

## What I'm building

[Senthex](https://senthex.com/proxy) is a transparent reverse proxy that scans every request and response to OpenAI, Anthropic, Mistral, Gemini, and OpenRouter in real time. One line of code, 16ms overhead, 24 security shields.

```python
client = OpenAI(
    api_key="sk-...",
    base_url="https://app.senthex.com/v1",
    default_headers={"X-Senthex-Key": "your-key"}
)
```

**Some things I built that nobody else does:**
- Multi-turn injection tracking across entire conversations
- Anti-bypass system with progressive trust levels — the harder you try, the harder it gets
- Canary tokens for system prompt leak detection
- Data classification with automatic provider routing
- Agent-native mode — autonomous agents monitor their own security via response headers

## Stack

Python · FastAPI · React · PostgreSQL · Redis · Docker

## Writing

- [How I Detect Multi-Turn Prompt Injections Without ML](https://dev.to/yohannsidot/how-i-detect-multi-turn-prompt-injections-without-ml-13oj)
- [How Canary Tokens Detect System Prompt Leaks in Real Time](https://dev.to/yohannsidot)

## Links

[![Senthex](https://img.shields.io/badge/Senthex-senthex.com-blue)](https://senthex.com/proxy)
[![PyPI](https://img.shields.io/pypi/v/senthex)](https://pypi.org/project/senthex/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yohann%20Sidot-0077B5)](https://www.linkedin.com/in/yohann-sidot-ab055a192)
[![Dev.to](https://img.shields.io/badge/Dev.to-yohannsidot-000000)](https://dev.to/yohannsidot)

---

*Built solo in 3 weeks with Claude Code. Currently in free beta — [try to break it](https://senthex.com/proxy).*
