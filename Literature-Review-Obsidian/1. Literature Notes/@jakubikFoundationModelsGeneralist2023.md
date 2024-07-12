---
category: literaturenote
tags:
  - Satellite
  - deeplearning
  - ML
citekey: jakubikFoundationModelsGeneralist2023
read: true
dateread: 2024-07-02
---

> [!Cite]
> Jakubik, J., Roy, S., Phillips, C. E., Fraccaro, P., Godwin, D., Zadrozny, B., Szwarcman, D., Gomes, C., Nyirjesy, G., Edwards, B., Kimura, D., Simumba, N., Chu, L., Mukkavilli, S. K., Lambhate, D., Das, K., Bangalore, R., Oliveira, D., Muszynski, M., … Ramachandran, R. (2023). _Foundation Models for Generalist Geospatial Artificial Intelligence_ (arXiv:2310.18660). arXiv. [http://arxiv.org/abs/2310.18660](http://arxiv.org/abs/2310.18660)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Jakubik, Johannes  
> **Author**:: Roy, Sujit  
> **Author**:: Phillips, C. E.  
> **Author**:: Fraccaro, Paolo  
> **Author**:: Godwin, Denys  
> **Author**:: Zadrozny, Bianca  
> **Author**:: Szwarcman, Daniela  
> **Author**:: Gomes, Carlos  
> **Author**:: Nyirjesy, Gabby  
> **Author**:: Edwards, Blair  
> **Author**:: Kimura, Daiki  
> **Author**:: Simumba, Naomi  
> **Author**:: Chu, Linsong  
> **Author**:: Mukkavilli, S. Karthik  
> **Author**:: Lambhate, Devyani  
> **Author**:: Das, Kamal  
> **Author**:: Bangalore, Ranjini  
> **Author**:: Oliveira, Dario  
> **Author**:: Muszynski, Michal  
> **Author**:: Ankur, Kumar  
> **Author**:: Ramasubramanian, Muthukumaran  
> **Author**:: Gurung, Iksha  
> **Author**:: Khallaghi, Sam  
> **Author**:: Hanxi,   
> **Author**:: Li,   
> **Author**:: Cecil, Michael  
> **Author**:: Ahmadi, Maryam  
> **Author**:: Kordi, Fatemeh  
> **Author**:: Alemohammad, Hamed  
> **Author**:: Maskey, Manil  
> **Author**:: Ganti, Raghu  
> **Author**:: Weldemariam, Kommy  
> **Author**:: Ramachandran, Rahul  
~    
> **Title**:: Foundation Models for Generalist Geospatial Artificial Intelligence  
> **Year**:: 2023   
> **Citekey**:: jakubikFoundationModelsGeneralist2023  
> **itemType**:: preprint    

> [!LINK] 
>
>  [Jakubik et al. - 2023 - Foundation Models for Generalist Geospatial Artifi.pdf](file://C:\Users\olley\Zotero\storage\WCGFSVPW\Jakubik%20et%20al.%20-%202023%20-%20Foundation%20Models%20for%20Generalist%20Geospatial%20Artifi.pdf).

> [!Abstract]
>
> Significant progress in the development of highly adaptable and reusable Artificial Intelligence (AI) models is expected to have a significant impact on Earth science and remote sensing. Foundation models are pre-trained on large unlabeled datasets through self-supervision, and then fine-tuned for various downstream tasks with small labeled datasets. There is an increasing interest within the scientific community to investigate whether this approach can be successfully applied to domains beyond natural language processing to effectively build generalist AI models that exploit multi-sensor data. This paper introduces a first-of-its-kind framework for the efficient pre-training and fine-tuning of foundational models on extensive geospatial data. We have utilized this framework to create Prithvi, a transformer-based geospatial foundational model pre-trained on more than 1TB of multispectral satellite imagery from the Harmonized Landsat-Sentinel 2 (HLS) dataset. Our study demonstrates the efficacy of our framework in successfully fine-tuning Prithvi to a range of Earth observation tasks that have not been tackled by previous work on foundation models involving multi-temporal cloud gap imputation, flood mapping, wildfire scar segmentation, and multi-temporal crop segmentation. We thoroughly examine and assess the effect of Prithvi’s pretrained weights on downstream tasks. We compare learning curves between 1) fine-tuning the entire model, 2) fine-tuning solely the decoder for the downstream task, and 3) training the model without utilizing Prithvi’s pre-trained weights. Our experiments show that the pre-trained model accelerates the fine-tuning process compared to leveraging randomly initialized weights. In addition, pretrained Prithvi compares well against the state-of-the-art on downstream tasks, e.g., outperforming a conditional GAN model in multi-temporal cloud imputation by up to 5pp (or 5.7%) in the structural similarity index. Finally, due to the limited availability of labeled data in the field of Earth observation, we gradually reduce the quantity of available labeled data for refining the model to evaluate data efficiency and demonstrate that data can be decreased significantly without affecting the model’s accuracy. The pre-trained 100 million parameter model and corresponding fine-tuning workflows have been released publicly as open source contributions to the global Earth sciences community through Hugging Face∗.
>.
> 
# Notes
>.


# Annotations%% begin annotations %%


%% end annotations %%

%% Import Date: 2024-07-02T11:15:39.159+01:00 %%
