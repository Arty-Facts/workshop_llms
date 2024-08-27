## Workshop LLMs 

This repository contains the code for the workshop on Language Models. The workshop is focused on exploring the capabilities of LLMs and how context can be used to solve different NLP tasks such as:

- Text Generation
- Question answering
- Information indexing and retrieval
- Structured Query Generation
- Extraction of structured information from text


## Setup

This workshop is notebook-based, so you will need to have Jupyter installed. You can also use Google Colab if you prefer.

Recommended to use a virtual environment to avoid conflicts with dependencies.

```bash
python3 -m venv venv
```

Activate the virtual environment

```bash
source venv/bin/activate
```

Select the right kernel for Jupyter.

## Limitations

This workshop is focused on the use of LLMs for NLP tasks. We will not train or fine-tune any models in this workshop. We will use pre-trained models from the Hugging Face Transformers library.

We will use small models that can be run on a laptop cpu or a free Google Colab instance. 

Hence the performance of the models will be limited. But the goal is to understand the capabilities of LLMs and how they can leverage the context to gain useful behavior. 