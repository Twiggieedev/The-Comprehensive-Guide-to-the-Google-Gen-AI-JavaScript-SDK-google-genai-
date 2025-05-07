# Unofficial Comprehensive Guide to the @google/genai JavaScript SDK

**Disclaimer:** This repository aims to provide enhanced and detailed documentation for the `@google/genai` JavaScript SDK, offering a community-driven perspective to supplement the official resources. While we strive for accuracy and comprehensive coverage, always refer to the [official Google documentation](https://googleapis.github.io/js-genai/) as the definitive source.

## Introduction

Welcome! This repository provides an in-depth guide and supplementary documentation for the `@google/genai` JavaScript SDK. The `@google/genai` package is the primary, modern Software Development Kit (SDK) for JavaScript and TypeScript developers looking to integrate Google's Gemini family of large language models (LLMs) into their applications[cite: 1, 2].

Our goal is to offer explanations, examples, and insights that go beyond the standard documentation, making it easier for developers to understand and leverage the full potential of this powerful SDK.

The SDK is designed as a unified interface, supporting interactions with Gemini models hosted on two distinct Google platforms[cite: 4]:
* **Gemini Developer API:** Accessed via API Keys from Google AI Studio, ideal for rapid prototyping and development[cite: 4].
* **Vertex AI Platform:** Google Cloud's enterprise-grade AI platform, using standard Google Cloud authentication (IAM, Service Accounts)[cite: 5].

This dual support allows for prototyping with API keys and smoother migration to the scalable Vertex AI environment with minimal code changes[cite: 6].

## Key Features of @google/genai

The `@google/genai` SDK is built to work with the advanced features of Gemini 2.0 and later versions[cite: 7, 8]. Key capabilities include[cite: 9]:

* **Text and Multimodal Content Generation:** Create text and analyze images, audio, and video inputs[cite: 9].
* **Stateful Chat:** Easily build conversational experiences with automatic history management[cite: 10].
* **File Management:** Upload and reference media files for model analysis[cite: 10].
* **Context Caching:** Optimize performance and reduce costs for repetitive large prompts[cite: 11].
* **Real-time Interaction (Live API):** Enable low-latency, bidirectional voice and video conversations[cite: 12].
* **Function Calling:** Allow models to interact with external tools and APIs[cite: 13].
* **Grounding:** Connect model responses to verifiable data sources like Google Search[cite: 14].
* **Safety Controls:** Configure filters to manage potentially harmful content[cite: 15].

## Relation to Legacy SDK (@google/generative-ai) & Migration

It's important to note that `@google/genai` is the **official successor** to the older, now-deprecated `@google/generative-ai` package[cite: 20]. Google strongly encourages users of the legacy library to migrate to the new `@google/genai` SDK[cite: 22]. A migration guide is available in the official Gemini API documentation[cite: 23].

The legacy `@google/generative-ai` repository has a planned **end-of-life date of August 31st, 2025**[cite: 24]. After this date, it will no longer receive updates[cite: 25].

## SDK Status (Preview)

As of the latest information, the `@google/genai` JavaScript/TypeScript SDK is often referred to as being in "Preview"[cite: 27]. While it's recommended over the deprecated SDK, this means[cite: 28]:
* APIs or functionalities might change before General Availability (GA)[cite: 28].
* Some advanced features might still be under development[cite: 29].

Despite this, Google actively recommends starting new projects and migrating existing ones to `@google/genai`[cite: 30].

## Installation

Install the SDK using npm[cite: 37]:

```bash
npm install @google/genai
