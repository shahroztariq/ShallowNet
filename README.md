# ShallowNet (All versions)

[GAN is a friend or foe?: a framework to detect various fake face images](https://dl.acm.org/doi/abs/10.1145/3297280.3297410).

[Detecting Both Machine and Human Created Fake Face Images In the Wild](https://dl.acm.org/doi/abs/10.1145/3267357.3267367).

## Citations

If you find our work useful for your research, please consider citing the following papers :)

```
@inproceedings{10.1145/3267357.3267367,
author = {Tariq, Shahroz and Lee, Sangyup and Kim, Hoyoung and Shin, Youjin and Woo, Simon S.},
title = {Detecting Both Machine and Human Created Fake Face Images In the Wild},
year = {2018},
isbn = {9781450359887},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3267357.3267367},
doi = {10.1145/3267357.3267367},
abstract = {Due to the significant advancements in image processing and machine learning algorithms, it is much easier to create, edit, and produce high quality images. However, attackers can maliciously use these tools to create legitimate looking but fake images to harm others, bypass image detection algorithms, or fool image recognition classifiers. In this work, we propose neural network based classifiers to detect fake human faces created by both 1) machines and 2) humans. We use ensemble methods to detect GANs-created fake images and employ pre-processing techniques to improve fake face image detection created by humans. Our approaches focus on image contents for classification and do not use meta-data of images. Our preliminary results show that we can effectively detect both GANs-created images, and human-created fake images with 94% and 74.9% AUROC score.},
booktitle = {Proceedings of the 2nd International Workshop on Multimedia Privacy and Security},
pages = {81–87},
numpages = {7},
keywords = {fake image detection, image forensics, generative adversarial network},
location = {Toronto, Canada},
series = {MPS '18}
}
```


```
@inproceedings{10.1145/3297280.3297410,
author = {Tariq, Shahroz and Lee, Sangyup and Kim, Hoyoung and Shin, Youjin and Woo, Simon S.},
title = {GAN is a Friend or Foe? A Framework to Detect Various Fake Face Images},
year = {2019},
isbn = {9781450359337},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3297280.3297410},
doi = {10.1145/3297280.3297410},
abstract = {Creating fake images such as replacing one's face with other person's face has become much easier due to the advancement of sophisticated image editing tools. In addition, Generative Adversarial Networks (GANs) enable creating natural looking human faces. However, fake images can cause many potential problems, as they can be misused to abuse information, hurt people, and generate fake identification. Therefore, detecting fake face images is critical for protecting individuals from various misuses. In this work, we propose an image forensic platform using neural networks, FakeFaceDetect, to detect various fake face images. In particular, we focus on detecting fake images automatically created from GANs as well as manually created by humans. In addition, we assume a strong adversary who can arbitrarily change and remove metadata of the original images. We demonstrate that FakeFaceDetect achieves high accuracy in detecting fake face images created by humans and GANs.},
booktitle = {Proceedings of the 34th ACM/SIGAPP Symposium on Applied Computing},
pages = {1296–1303},
numpages = {8},
location = {Limassol, Cyprus},
series = {SAC '19}
}
```
