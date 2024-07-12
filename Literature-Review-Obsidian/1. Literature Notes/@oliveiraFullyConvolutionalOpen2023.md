---
category: literaturenote
tags:
  - Satellite
  - deeplearning
  - ML
citekey: oliveiraFullyConvolutionalOpen2023
read: true
dateread: 2024-07-02
---

> [!Cite]
> Oliveira, H., Silva, C., Machado, G. L. S., Nogueira, K., & dos Santos, J. A. (2023). Fully convolutional open set segmentation. _Machine Learning_, _112_(5), 1733–1784. [https://doi.org/10.1007/s10994-021-06027-1](https://doi.org/10.1007/s10994-021-06027-1)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Oliveira, Hugo  
> **Author**:: Silva, Caio  
> **Author**:: Machado, Gabriel L. S.  
> **Author**:: Nogueira, Keiller  
> **Author**:: dos Santos, Jefersson A.  
~    
> **Title**:: Fully convolutional open set segmentation  
> **Year**:: 2023   
> **Citekey**:: oliveiraFullyConvolutionalOpen2023  
> **itemType**:: journalArticle  
> **Journal**:: *Machine Learning*  
> **Volume**:: 112  
> **Issue**:: 5   
> **Pages**:: 1733-1784  
> **DOI**:: 10.1007/s10994-021-06027-1    

> [!LINK] 
>
>  [Full Text PDF](file://C:\Users\olley\Zotero\storage\9JS6UA4T\Oliveira%20et%20al.%20-%202023%20-%20Fully%20convolutional%20open%20set%20segmentation.pdf).

> [!Abstract]
>
> In traditional semantic segmentation, knowing about all existing classes is essential to yield effective results with the majority of existing approaches. However, these methods trained in a Closed Set of classes fail when new classes are found in the test phase, not being able to recognize that an unseen class has been fed. This means that they are not suitable for Open Set scenarios, which are very common in real-world computer vision and remote sensing applications. In this paper, we discuss the limitations of Closed Set segmentation and propose two fully convolutional approaches to effectively address Open Set semantic segmentation: OpenFCN and OpenPCS. OpenFCN is based on the well-known OpenMax algorithm, configuring a new application of this approach in segmentation settings. OpenPCS is a fully novel approach based on feature-space from DNN activations that serve as features for computing PCA and multi-variate gaussian likelihood in a lower dimensional space. In addition to OpenPCS and aiming to reduce the RAM memory requirements of the methodology, we also propose a slight variation of the method (OpenIPCS) that uses an iteractive version of PCA able to be trained in small batches. Experiments were conducted on the well-known ISPRS Vaihingen/Potsdam and the 2018 IEEE GRSS Data Fusion Challenge datasets. OpenFCN showed little-to-no improvement when compared to the simpler and much more time efficient SoftMax thresholding, while being some orders of magnitude slower. OpenPCS achieved promising results in almost all experiments by overcoming both OpenFCN and SoftMax thresholding. OpenPCS is also a reasonable compromise between the runtime performances of the extremely fast SoftMax thresholding and the extremely slow OpenFCN, being able to run close to real-time. Experiments also indicate that OpenPCS is effective, robust and suitable for Open Set segmentation, being able to improve the recognition of unknown class pixels without reducing the accuracy on the known class pixels. We also tested the scenario of hiding multiple known classes to simulate multimodal unknowns, resulting in an even larger gap between OpenPCS/OpenIPCS and both SoftMax thresholding and OpenFCN, implying that gaussian modeling is more robust to settings with greater openness.
>.
> 
# Notes
>.


# Annotations%% begin annotations %%


%% end annotations %%

%% Import Date: 2024-06-26T14:37:54.594+01:00 %%
