#### BCG: Active learning and transfer learning of Text / Content

##### Scripted by: Laura Edell, Sr. Data Scientist | Cloud Solutions Architect
##### Date: April 4, 2019

#### Instructions

Provision an Ubuntu Linux Data Science Virtual Machine; the size "Standard_DS12_v2" works well  
(**Note: at the start of the tutorial, credentials for pre-provisioned VMs will be handed out)**:  
https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-ads.linux-data-science-vm-ubuntu

Log in to JupyterHub by pointing your web browser to https://hostname:8000 (be sure to use https, not http, and replace "hostname" with the hostname or IP address of your virtual machine). Please disgregard warnings about certificate errors.

Open a bash terminal window in JupyterHub by clicking the New button and then clicking Terminal.

In the terminal, run these four commands:

```bash
cd ~/notebooks

git clone https://github.com/annedroid/active-learning-workshop.git

cd active-learning-workshop

source startup.sh
```


## Abstract

Accessed via R and Python APIs, pre-trained Deep Learning models and Transfer Learning are making custom classification with large or small amounts of labeled data easily accessible to data scientists and application developers. 

## Active Learning

[Active learning](https://en.wikipedia.org/wiki/Active_learning) helps us address the common situation where we have large amounts of data, but labeling this data is expensive. By using a preliminary model to select the cases that are likely to be most useful for improving the model, and iterating through several cycles of model training and case selection, we can often build a model using a much smaller training set (thus requiring less labeling effort) than we would otherwise need. 

## Outline:

We have two hands-on, end-to-end active learning-based classification examples:

1. Text Classification: flagging content and tagging personal  preferences


Both examples will use similar active learning approaches, but different aspects will be emphasized in the two parts:  

* data exploration
* featurization
* classification
* iterative model building and active learning from selected cases
* deployment and consumption of scoring services
* scaling with distributed computing

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
