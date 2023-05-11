# LangChain LLM Library Port

LangChain is a versatile library for working with Large Language Models (LLMs) like GPT-4. This repository contains a port of the LangChain library to the dotnet platform.  

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Quick Start](#quick-start)
6. [Documentation](#documentation)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgements](#acknowledgements)

## Introduction

Does the world need a port of Langchain to a popular Enterprise language? We don't know, but to bring along our fellow enterprise engineers for the ride on the LLM train, we wanted to lower the barrier to entry.  This port attempts to do that by giving the enterprise fleet of dot net developers the tools they need to work themselves out of a job.

## Features

- Seamless integration with your dotnet async workflows.
- Ports of models, prompts, chains, agents and tools
- The feeling like being a dotnet developer can still be exciting and fresh

## Requirements

- dotnet 7.0
- Compatible LLM (e.g., GPT-4 or other supported models)

## Installation

To install the LangChain LLM Library Port, simply run:

```
TODO: package on nuget.
pip install langchain-llm-port 
```

## Quick Start

To get started with the LangChain LLM Library Port, follow these steps:

1. Import the library:

```python
import langchain_llm_port as llm
```

2. Initialize the LLM (e.g., GPT-4) and the desired tokenizer:

```python
model = llm.load_model("gpt-4")
tokenizer = llm.load_tokenizer("gpt-4")
```

3. Perform a task with the model, such as generating text:

```python
input_text = "Once upon a time, in a faraway land, there was a"
output_text = llm.generate_text(model, tokenizer, input_text)
print(output_text)
```

## Contributing

We welcome contributions from the community! If you would like to contribute to the LangChain LLM Library Port, please refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines.

## License

The LangChain LLM Library Port is released under the [MIT License](./LICENSE).

## Acknowledgements

We would like to thank the original authors of the LangChain library, the OpenAI team for creating GPT-4, and the countless contributors who have helped to make this port possible.
