# CzechTopic Prompts

This directory contains files with prompts that were used during development of CzechTopic

### Prompts to generate the synthetic annotations:
- `dev-topic-discovery.txt`
- `dev-topic-localization.txt`

The generation was done using the scripts provided in the repository.

### Prompts for LLM inference:
- `czech-prompt-extractive-few-shot.yaml`
- `czech-prompt-tagging-few-shot.yaml`
- `english-prompt-extractive-few-shot.yaml`
- `english-prompt-tagging-few-shot.yaml`
- `czech-prompt-extractive-zero-shot.yaml`
- `czech-prompt-tagging-zero-shot.yaml`
- `english-prompt-extractive-zero-shot.yaml`
- `english-prompt-tagging-zero-shot.yaml`

The inference was done using the [ai-caller](https://github.com/mdocekal/ai_caller) package made by Martin Dočekal.
