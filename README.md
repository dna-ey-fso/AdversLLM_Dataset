# AdversLLM

We make publicly available a dataset containing 50 malicious prompts to test LLMs against. The dataset has been created by identifying questions that invoke a malicious, violent, sexual or hateful response. The goal of this dataset is to be a starting point to evaluate the robustness of any LLM, be it open-source or proprietary, against any type of prompts (unaltered or altered). The unaltered prompts can be used as a benchmark to verify whether the perturbation on the prompt is the reason for bypassing the model. After prompting the LLM, the result can be categorized as successful or not, depending on whether unwanted content has been generated. 

The dataset is an ongoing effort, due to the current fast nature of LLM development, attacks that were successful in the past might now not be able to fool the model anymore. Therefore, we strive to update these results with both the latest techniques and LLMs. Due to the Herculean size of this task, we strongly encourage anyone to contribute to this dataset as well. Note that LLMs are non-deterministic, so it is encouraged to test each prompt multiple times.

## Contact
- Othmane Belmoukadam othmane.belmoukadam@be.ey.com
- Jiri De Jonghe jiri.de.jonghe@be.ey.com
- Sofyan Ajridi sofyan.ajridi@be.ey.com
