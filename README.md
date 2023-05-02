# Radiology-Text-Simplification-Liver
This repo contains the data created by the authors of paper: **Data Augmentation for Radiology Report Simplification** 
```
train_all.csv: 200 training samples annotated by the radiologist.
test_all.csv: 140 testing samples annotated by the radiologist.
augmentation_gold.csv: 205 samples with radiologist-provided simplifications.
```

For more details, please refer to Section 5.1 in the paper.

If you use our data in any research work, please cite our paper:
```
@inproceedings{yang-etal-2023-data,
    title = "Data Augmentation for Radiology Report Simplification",
    author = "Yang, Ziyu  and
      Cherian, Santhosh  and
      Vucetic, Slobodan",
    booktitle = "Findings of the Association for Computational Linguistics: EACL 2023",
    month = may,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-eacl.144",
    pages = "1877--1887",
    abstract = "This work considers the development of a text simplification model to help patients better understand their radiology reports. This paper proposes a data augmentation approach to address the data scarcity issue caused by the high cost of manual simplification. It prompts a large foundational pre-trained language model to generate simplifications of unlabeled radiology sentences. In addition, it uses paraphrasing of labeled radiology sentences. Experimental results show that the proposed data augmentation approach enables the training of a significantly more accurate simplification model than the baselines.",
}
```
