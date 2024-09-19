# RDM4AI Tutorial @ KI 2024
This is the repository for the session "Model and Data Documentation for AI — Fostering Transparency, Accountability & Replicability" (Angelie Kraft) that is part of the tutorial [Research Data Management in Data Science and AI - Avoiding a Replicability Crisis (RDM4AI)](https://sites.google.com/view/rdm4ai-2024/) co-located with the [KI 2024](https://www.informatik.uni-wuerzburg.de/ki24/) held in Würzburg, Germany. The tutorial is organized by Leyla Jael Castro (ZB Med), Angelie Kraft (University of Hamburg, Leuphana University Lüneburg) and Ricardo Usbeck (Leuphana University Lüneburg) and an effort of the project [NFDI4DataScience](https://www.nfdi4datascience.de/). 

![NFDI4DS Logo](https://github.com/krangelie/rdm4ai-tutorial-ki2024/blob/main/imgs/Logo_NFDI4DataScience_smaller.jpg?raw=true)

# Overview
* **Name**: Model and Data Documentation for AI — Fostering Transparency, Accountability & Replicability
* **Description**: This tutorial will introduce you to documentation schemas that facilitate comprehensive reporting of key information such as model architectures, hyperparameters, and dataset characteristics. By standardizing documentation practices, researchers can enhance the reproducibility of experiments, foster collaboration across diverse AI domains, and foster transparency regarding biases and limitations.
* **Keywords**: AI models, documentation, transparency, accountability, data management

**Questions**
* What are data and model cards?
* Why do we need them?
* Who are they for?
* How and where can I create a data or model card?

**Learning outcomes**
* Understand the motivation and goals behind data and model documentation
* Understand their use for different stakeholders
* Know where to find templates and tools and how to use them

**Requirements**
* Basic knowledge about AI development

**Time estimation** 40 minutes input + 20 minutes hands-on
**Level** Beginner/Introductory
**Published** 2024-09-19
**License** [CC-By 4.0](https://spdx.org/licenses/CC-BY-4.0)

 Version 1.0.0

# Tutorial materials
## Examples
* [Fineweb Model Card](https://huggingface.co/datasets/HuggingFaceFW/fineweb)
* [Wikipedia Model Card](https://huggingface.co/datasets/wikimedia/wikipedia)

## Hands-on data card creation
* [HuggingFace Data Card UI](https://huggingface.co/new-dataset)
* [Google Data Cards Playbook Template](https://github.com/PAIR-code/datacardsplaybook/tree/main/templates)

How to create a data card via the HuggingFace UI:
![HuggingFace Data Card creation step 1](https://github.com/krangelie/rdm4ai-tutorial-ki2024/blob/main/imgs/step1.png?raw=true)
![HuggingFace Data Card creation step 2](https://github.com/krangelie/rdm4ai-tutorial-ki2024/blob/main/imgs/step2.png?raw=true)

## Hands-on model card creation
* [HuggingFace Model Card Jupyter Notebook](https://colab.research.google.com/drive/1cmETl1Q8spab3rfsolB1qYp3l7iPYfeP?usp=sharing#scrollTo=By8fG2PKaLX0)
* [Bias Toolkit Model Card Generator version 0.2](https://bias.xd.gov/resources/model-card-generator/tool/)


# Readings
## Dataset documentation
* Ben Hutchinson, Andrew Smart, Alex Hanna, Emily Denton, Christina Greer, Oddur Kjartansson, Parker Barnes, Margaret Mitchell: [Towards Accountability for Machine Learning Datasets: Practices from Software Engineering and Infrastructure.](https://dl.acm.org/doi/10.1145/3442188.3445918) FAccT 2021: 560-575.
* Timnit Gebru, Jamie Morgenstern, Briana Vecchione, Jennifer Wortman Vaughan, Hanna M. Wallach, Hal Daumé III, Kate Crawford: [Datasheets for datasets.](https://dl.acm.org/doi/10.1145/3458723) Commun. ACM 64(12): 86-92 (2021).

## Model documentation
* Margaret Mitchell, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, Timnit Gebru: [Model Cards for Model Reporting.](https://dl.acm.org/doi/10.1145/3287560.3287596) FAT 2019: 220-229.
* Ezi Ozoani, Marissa Gerchick, Margaret Mitchell: [Model Card Guidebook.](https://huggingface.co/docs/hub/en/model-card-guidebook) Hugging Face, 2022. 

## Additional recommended readings
* Bernard Koch, Emily Denton, Alex Hanna, Jacob G. Foster: [Reduced, Reused and Recycled: The Life of a Dataset in Machine Learning Research.](https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/file/3b8a614226a953a8cd9526fca6fe9ba5-Paper-round2.pdf) NeurIPS Datasets and Benchmarks 2021.
* Amy Heger, Liz B. Marquis, Mihaela Vorvoreanu, Hanna M. Wallach, Jennifer Wortman Vaughan: [Understanding Machine Learning Practitioners' Data Documentation Perceptions, Needs, Challenges, and Desiderata.](https://dl.acm.org/doi/10.1145/3555760) Proc. ACM Hum. Comput. Interact. 6(CSCW2): 1-29 (2022).
* Will Orr, Edward B. Kang: [AI as a Sport: On the Competitive Epistemologies of Benchmarking.](https://dl.acm.org/doi/10.1145/3630106.3659012) FAccT 2024: 1875-1884.
* Hugging Face: [The Landscape ML Documentation Tools](https://huggingface.co/docs/hub/model-card-landscape-analysis)
* Xinyu Yang, Weixin Liang, James Zou: [Navigating Dataset Documentations in AI: A Large-Scale Analysis of Dataset Cards on HuggingFace.](https://openreview.net/pdf?id=xC8xh2RSs2) ICLR 2024

# More templates & tools
## Dataset documentation
* [Datasheet for Datasets Template](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4t8QB)
* [Aether Data Documentation Template](https://www.microsoft.com/en-us/research/uploads/prod/2022/07/aether-datadoc-082522.pdf)
* [Full Google Data Cards Playbook](https://sites.research.google/datacardsplaybook/)

## Model documentation
* [VerifyML Model Card](https://report.verifyml.com/)
* [Tutorial by Karl Weinmeister](https://cloud.google.com/blog/products/ai-machine-learning/create-a-model-card-with-scikit-learn?hl=en)

# Acknowledgments
This tutorial draws a lot of input from the [Model Card Guidebook](https://huggingface.co/docs/hub/en/model-card-guidebook).
Funding information: German Research Foundation (DFG), project NFDI4DataScience, grant no. [460234259](https://gepris.dfg.de/gepris/projekt/460234259?context=projekt&task=showDetail&id=460234259&).
