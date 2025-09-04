# Tutorial: BioKG meet LLM

This is the repository for the tutorial **Biomedical Knowledge Graphs meet LLM**.
See the link [here](https://www.bc2.ch/tutorials-workshops)

This tutorial focuses on the complementary nature of Biomedical Knowledge Graphs (KGs) and Large Language Models (LLMs), offering a comprehensive exploration of their individual strengths and synergistic potential. Participants will gain a deep understanding of how KGs, with their structured representation of biological knowledge, and LLMs, with their powerful natural language processing capabilities, can address key challenges in the life sciences, supporting evidence-based reasoning and discovery.


The tutorial notebooks will be segmented in 4 parts:

- LLM for Knowledge Graph:
    - [Building KG using LLM - NER/RE](notebooks/Named_Entity_Recognition_and_Relation_Extraction.ipynb) (*part 1*)
    - [Entity Linking](notebooks/Entity_Linking.ipynb) (*optional part 1.5*)

- KG for LLM
    - [Inference and prediction using LLM x KG](notebooks/inference_kg_rag.ipynb) (*part 2*)
    - [BioTopg - a biomedical GraphRAG framework](notebooks/biotopg.ipynb) (*part 3*)

The notebook are intially meant to be used with Google colab.

Inside each notebook, you will need to load the associated data (eg. for *Building KG using LLM - NER/RE* load the data in the corresponding sub-directory *part1*)

While notebooks show how to use ollama to *locally* run LLM directly inside the notebooks, many examples will use the OpenAI API for practicity. In order to use the API, please create a `.env` inside your session and add your OpenAI apikey as follow:

```.env
OPENAI_API_KEY="sk-proj..."
```

The slides of the session and the recording will be made available asap.

