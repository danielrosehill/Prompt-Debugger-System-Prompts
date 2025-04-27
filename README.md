# Prompt Debugging System Prompts

This repository is a small collection of system prompts designed for **debugging prompts** — whether system prompts, user prompts, or instructional prompts — across different use cases.

The collection spans both **conversational** and **instructional** contexts. It includes focused system prompts for areas such as tool/function calling, RAG (Retrieval-Augmented Generation) behavior, search result relevance, and structured output validation (e.g., JSON schemas).

While AI tools are traditionally seen as the *responders* to prompts, they can also serve as highly effective *analyzers* — applying their language understanding abilities to help users perform "self-examination" of prompts and identify why deviations occurred between expected and actual model outputs.  
Of course, human intelligence and strong prompt engineering skills remain essential, but AI can serve as a useful assistant in this process.

These system prompts can be configured as AI assistants on any platform that supports setting custom system prompts (such as OpenAI, OpenRouter, LM Studio, etc.).

## System Prompts Index

This repository contains the following system prompts for debugging different types of prompts:

| Prompt | Description |
|--------|-------------|
| [![Basic](https://img.shields.io/badge/Basic_Prompt_Debugger-5C5C5C?style=for-the-badge)](basic.md) | A general-purpose debugger for analyzing and improving both system and user prompts |
| [![User](https://img.shields.io/badge/User_Prompt_Debugger-4285F4?style=for-the-badge)](user-prompt-debugger.md) | Specifically focused on debugging and improving user prompts |
| [![System](https://img.shields.io/badge/System_Prompt_Debugger-0F9D58?style=for-the-badge)](system-prompt-debugger.md) | Specifically focused on debugging and improving system prompts |
| [![RAG](https://img.shields.io/badge/RAG_Usage_Debugger-DB4437?style=for-the-badge)](debug-rag-usage.md) | For diagnosing and correcting issues related to context retrieval and RAG behavior |
| [![Search](https://img.shields.io/badge/Search_Debugger-F4B400?style=for-the-badge)](search-debugger.md) | For debugging prompts that drive search functionality and improving search result relevance |
| [![Tool](https://img.shields.io/badge/Conversational_Tool_Use_Debugger-4285F4?style=for-the-badge)](conversational-tool-use-debugger.md) | For debugging issues with tool, function, or MCP invocation in conversational contexts |
| [![Instructional](https://img.shields.io/badge/Instructional_Prompt_Debugger-7B1FA2?style=for-the-badge)](instructional-prompt-debugger.md) | For debugging prompts that produce structured outputs (such as JSON) according to an intended schema |
