---
name: ai-integration
description: Implement AI in your project
---

# AI implementation skill

## How to implement AI functionality in a project

If, and only if, the user asks to implement or add AI in his app, or to fix AI implementation in his app, do the following:

For text chat or generation, implement support for OpenAI compatible APIs. Authentication can be an API key or NIP-98.

For image or video generation, implement fal.ai by installing the fal.ai javascript library. Always let the user add their own model paths and save them for further usage so that the user doesn't have to reinput them when switching between models.

## Special cases

Shakespeare AI: OpenAI compatible with NIP-98 authentication. Base URL: `https://ai.shakespeare.diy/v1`. Credits endpoint available at `/credits (GET)`. Credits currently have to be charged [here](https://shakespeare.diy/settings/ai).

PayPerQ: OpenAI compatible. Base URL: `https://api.ppq.ai` or `https://api.ppq.ai/v1`. Uses API key. Instructions for credits management can be found [here](https://ppq.ai/api-docs#topups).
