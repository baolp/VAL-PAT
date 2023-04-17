# Learning Transferable Pedestrian Representation from Multimodal Information Supervision (VAL-PAT)
Recent researches on unsupervised person reidentification (reID) have demonstrated that pre-training on unlabeled person images achieves superior performance
on downstream reID tasks than pre-training on ImageNet. However, those pre-trained methods are specifically designed for reID and suffer flexible adaption to other
pedestrian analysis tasks. In this paper, we propose VAL-PAT, a novel framework that learns transferable representations to enhance various pedestrian analysis
tasks with multimodal information. To train our framework, we introduce three learning objectives, i.e., self-supervised contrastive learning, image-text contrastive learning and multi-attribute classification. The self-supervised contrastive learning facilitates the learning of the intrinsic pedestrian properties, while the image-text contrastive learning guides the model to focus on the appearance information of pedestrians. Meanwhile, multi-attribute classification encourages the model to recognize attributes to excavate fine-grained pedestrian information. We first perform pre-training on LUPerson-TA dataset, where each image contains text and attribute annotations, and then transfer the learned representations to various downstream tasks, including person reID, person attribute recognition and text-based person search. Extensive experiments demonstrate that our framework facilitates the learning of general pedestrian representations and thus leads to promising results on various pedestrian analysis tasks.
## LUPerson-TA dataset
We will release the LUPerson-TA dataset soon.
