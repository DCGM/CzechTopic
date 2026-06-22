# CzechTopic Prompts

This directory contains files with prompts that were used during development of CzechTopic

### Prompts to generate the synthetic annotations:
- `dev-topic-discovery.txt`
- `dev-topic-localization.txt`

The generation was done using OpenAI Batch API.

The topic discovery had the following user message:
```
[TEXT 1]
text_1

[TEXT 2]
text_2

...
```

The topic localization had the following user message:
```
[TÉMATA A JEJICH POPISY]
- topic_1_name: topic_1_description
- topic_2_name: topic_2_description
...

[TEXT]
text_to_be_processed
```


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
