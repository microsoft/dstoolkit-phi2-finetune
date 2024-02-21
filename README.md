# Finetuning Phi-2

## Introduction 
This repository contains step by step instructions on how to finetune Microsoft's Phi-2 model with your own data. You can read Phi-2 technical paper [here](https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/) and the conference paper [here](https://arxiv.org/abs/2306.11644).

There are three files included in this repository:

    (1) requirements.txt
    (2) phi2Finetune.ipynb
    (3) QnA_MSFT365.csv

(1) contains the required python libaries which need to be installed on a new enviroment to run (2). File (2) is the self contained notebook which provides step by step instructions on how to finetune Microsofts' Phi-2 language model using your own data. (3) is some sample data (taken from [Microsoft 365 FAQ](https://www.microsoft.com/en-us/microsoft-365/microsoft-365-for-home-and-school-faq)) which can be used to run in the notebook if you wish, otherwise it can be used as an example to base your own data on.

## Getting Started
To get started:

1.  Create a vm with a GPU or use a local machine with a GPU.
2.  Clone this repository on a vm or local machine.
3.  Create a new python enviroment installing all libraries listed in requirements.txt.
4. Follow step by step instructions in phi2Finetune.ipynb.

The VM (Azure ML) that was used in creation of this notebook was: Standard_NC6s_v3 - 1 x NVIDIA Tesla V100.

## Contribute
Please reach out to henrytaylor@microsoft.com, for any questions, suggestions, or improvements. Thank you!

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
