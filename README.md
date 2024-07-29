# Master Thesis - Applications of Machine Learning for Novel Datasets on Electric Vehicles

This repository represents the code support for my master thesis. It includes four notebooks with the code for the proposed method and its evaluation.

The four notebooks are explained in Section 3 of the written documnet and contain comments that explain the code artefacts.

The notebooks are to be run in the following order:
- 1st - api_explore.ipynb
- 2nd - ner_stanza_preproc.ipynb
- 3rd - prompt_chatgpt.ipynb
- 4th - create_network.ipynb

Besides the code support, there are two data files provided:
- the csv file has all the prompts which were created and are to be sent to the LLM (GPT 3.5 in this case)
- the .graphml file contains the final result, the novel dataset for the electric car batteries supply chain

The following Python packages are required for running the code support: pandas, numpy, stanza, networkx, openai, matplotlib, numpy, pytorch, lexisnexisapi, tiktoken, seaborn, adjusttext
