# Master Thesis - Applications of Machine Learning for Novel Datasets on Electric Vehicles

This repository represents the **code support for my master thesis**. It includes four notebooks with the code for the proposed method and its evaluation.

The four notebooks are explained in Section 3 of the written documnet and contain comments that explain the code artefacts.

**The notebooks are to be run in the following order:**
- 1st - api_explore.ipynb
- 2nd - ner_stanza_preproc.ipynb
- 3rd - prompt_chatgpt.ipynb
- 4th - create_network.ipynb

Besides the code support, there are **one data file is provided:**
- the .graphml file contains the final result, the novel dataset for the electric car batteries supply chain

The following **Python packages are required for running the code support:** pandas, numpy, stanza, networkx, openai, matplotlib, numpy, pytorch, lexisnexisapi, tiktoken, seaborn, adjusttext


**The Abstract of the thesis reads as following:**
The electric car industry is expanding at an unprecedented rate,
and to achieve climate goals for 2035 and 2050, this growth is expected
to accelerate further. With challenges arising from the localization
of manufacturing, tariff introductions, and the polarized geographical
location of players, close oversight of the automotive sector’s network of
firms is crucial. Despite significant attention from both researchers and
industry stakeholders on global value chains in the automotive sector,
there remains a lack of visibility into firm-level relationships. This
master thesis proposes a method for creating novel datasets for the
electric car battery industry by utilizing unstructured data from news
sources and large language models. By utilizing this method, over 240
thousand news articles are analyzed, resulting in almost 60 thousand
possible relations between firms OEMs and battery producers.
