# llm-engineering

This repository is my learning while trying to explore and learn about LLMs and integrating with them

## Week 1 - Building our first LLM Product : Exploring top models & transformers

### Day 1 -

- Setup ollama for local llm deployment.

  - ollama lets us run a large language model directly on our computer. #TODO check more about how ollama works internally
  - ollama lets us run C++ code version of LLMs compiled directly on our machine.
  - download ollama compatible for our machine.

- Running llm in ollama -

  - run in command line `ollama run llama3.2` or maybe a version of `qwen` or any other model from ollama site models page.
  - running above command might take some time at first as it needs to download the 2 billion parameters associated with 3.2 .
    - #TODO check more about these parameter numbers and how models are created for these different parameter numbers.
    - #TODO check dependency between model parameters Vs system requirements (RAM etc..) for running those models.

- Setting up our LLM development environment -

  - install anaconda.
  - setup anaconda environment by running `conda env create -f environment.yml`.
    - environment.yml file has full description of the environment we are trying to setup.
  - activate the environment we just created using `conda activate llm`
  - launch jupyter lab in that environment using `jupyter lab`
  - create `.env` file in project root directory with openai key e.g. `OPENAI_API_KEY=<key_from_openai>`

### Day 2 -
