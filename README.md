# Medical Transformers

In this work, we developed an image classification model for medical X-ray images using the [Chexpert](https://stanfordmlgroup.github.io/competitions/chexpert) dataset. We also used [Vision Transformers](https://arxiv.org/abs/2010.11929) for the first time in the medical domain. Our proposed model used the combined architecture of convolutional neural networks and the Vision Transformer.

We developed strided vision transformers where images are given into vision transformers in a strided fashion. In our experiments, we observed that we gained close to one percent increase in mean AUC score using the strided version. This increase is especially more apparent in the distilled version of the vision transformer.

We also compared our architecture with six different variations of vision transformers that we have mentioned in the previous sections. We demonstrated that using vision transformers together with convolutional architecture achieves much better performance than vision transformers alone. Our model also managed to beat Stanford’s baseline model. Thus we believe vision transformers will have potential in the medical domain.
