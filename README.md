# Spring AI Core Concepts Learning Lab

This repository contains my hands-on learning projects, code samples, and experiments with the core components of the **Spring AI** framework. It focuses on structuring interactions with Large Language Models (LLMs) using programmatic prompts, responses, templates, and roles.

## 🚀 Core Concepts Covered

### 1. Prompts & Responses
*   **Prompt**: The foundational input object in Spring AI used to encapsulate the text messages sent to the AI model.
*   **ChatResponse**: The structured output returned by the model, containing metadata, token usage metrics, and the generated content (`Generation`).

### 2. Prompt Templates
*   Reusable blueprints used to create dynamic prompts.
*   Uses placeholders (e.g., `{topic}`) to separate the prompt structure from the runtime user data.

### 3. User & System Messages
*   **System Prompt**: Sets the persona, boundaries, and rules for the AI model before the conversation starts.
*   **User Prompt**: The direct input or query provided by the end-user during the interaction.
