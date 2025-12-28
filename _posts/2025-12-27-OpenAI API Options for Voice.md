---
title: "OpenAI API Options for Voice"
date: 2025-12-27
---

## Realtime API (Speech-to-Speech Interactive)

Build truly interactive voice agents where users can speak and get audio responses in real time, similar to ChatGPT’s Advanced Voice Mode — but for your own application.

### Capabilities:
- Stream audio input and output (WebSocket/WebRTC)
- Natural conversational speech-to-speech with low latency
- Built-in support for handling interruptions during conversations
- Function calling support to trigger actions from voice queries
  
## Chained ASR + Responses/Chat Completions API + TTS (Non-Realtime Pipeline)

Alternatively, you can build a voice system by chaining:
Speech-to-Text → Text LLM processing → Text-to-Speech 

### Why do this?
- More predictable control over responses
- Easier to integrate with existing text-based workflows
- Lower cost if real-time isn’t required
