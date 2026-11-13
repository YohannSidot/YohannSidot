# Hey, I'm Yohann 👋

I build **verified GPU kernels for Apple Silicon**: Metal kernels for inference engines, written by Claude models under my direction, checked bit for bit and benchmarked on real shapes.

## What I'm building

- One operation of your engine at a time (quantized matmul, attention, speculative verify), on Apple Silicon.
- Each kernel comes with its verifier (float64 reference, fuzzing of shapes and values, bit-for-bit batch-invariance checks) and an interleaved A/B benchmark that you run on your own machine.
- When the answer is "no gain here", I say so, with the numbers.

Examples, the verifier, the benchmark and the commissioning terms are in **[verified-metal-kernels](https://github.com/YohannSidot/verified-metal-kernels)**. Commissions are paid on result.

## Earlier work

**Senthex**, an AI firewall for LLM API calls: a transparent reverse proxy that scanned requests and responses to the main LLM providers in real time, with multi-turn injection tracking, canary tokens for system prompt leaks and an agent-native mode.

Writing from that project:

- [How I Detect Multi-Turn Prompt Injections Without ML](https://dev.to/yohannsidot/how-i-detect-multi-turn-prompt-injections-without-ml-13oj)
- [How Canary Tokens Detect System Prompt Leaks in Real Time](https://dev.to/yohannsidot)

## Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yohann%20Sidot-0077B5)](https://www.linkedin.com/in/yohann-sidot-ab055a192)
[![Dev.to](https://img.shields.io/badge/Dev.to-yohannsidot-000000)](https://dev.to/yohannsidot)
