OpenViVQA: Open-domain Vietnamese Visual Question Answering
=====

![examples](data_examples.png)
Examples of some samples of the OpenViVQA dataset. Note that texts in green indicate scene texts copied from the images.

Paper of this dataset is under review at an international journal. The dataset will be available when our paper will have been accepted.

If you mention or use any information of our dataset, please cite to our paper:
```
@article{NGUYEN2023101868,
title = {OpenViVQA: Task, dataset, and multimodal fusion models for visual question answering in Vietnamese},
journal = {Information Fusion},
volume = {100},
pages = {101868},
year = {2023},
issn = {1566-2535},
doi = {https://doi.org/10.1016/j.inffus.2023.101868},
url = {https://www.sciencedirect.com/science/article/pii/S1566253523001847},
author = {Nghia Hieu Nguyen and Duong T.D. Vo and Kiet {Van Nguyen} and Ngan Luu-Thuy Nguyen},
keywords = {Visual question answering, Vision-language understanding, Low-resource languages, Information fusion, Multimodal representation},
abstract = {In recent years, visual question answering (VQA) has attracted attention from the research community because of its highly potential applications (such as virtual assistance on intelligent cars, assistant devices for blind people, or information retrieval from document images using natural language as queries) and challenge. The VQA task requires methods that have the ability to fuse the information from questions and images to produce appropriate answers. Neural visual question answering models have achieved tremendous growth on large-scale datasets which are mostly for resource-rich languages such as English. However, available datasets narrow the VQA task as the answers selection task or answer classification task. We argue that this form of VQA is far from human ability and eliminates the challenge of the answering aspect in the VQA task by just selecting answers rather than generating them. In this paper, we introduce the OpenViVQA (Open-domain Vietnamese Visual Question Answering) dataset, the first large-scale dataset for VQA with open-ended answers in Vietnamese, consists of 11,000+ images associated with 37,000+ question–answer pairs (QAs). Moreover, we proposed FST, QuMLAG, and MLPAG which fuse information from images and questions, then use these fused features to construct answers as humans iteratively. Our proposed methods achieve results that are competitive with SOTA models such as SAAA, MCAN, LORA, and M4C. The dataset11https://github.com/hieunghia-pat/OpenViVQA-dataset. is available to encourage the research community to develop more generalized algorithms including transformers for low-resource languages such as Vietnamese.}
}
```

### Contact

This repository was constructed under the instruction of the [NLP@UIT](https://nlp.uit.edu.vn/). For more information, contact the following author:
1. Nghia Hieu Nguyen. Email: 19520178@gm.uit.edu.vn
