
# Awesome Sound Source Separation: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of source separation, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

This list mainly focuses on deep learning based models. It aims to introduce *milestones* works and essential things for beginner researchers(including myself).

This list may contain incorrect informations and I don't want this list to be exhaustive. If I miss **important** papers or anyone found incorrect informations, please let me know via Github issue.

**WIP: This list is in construction.** 

## Contributing

Please feel free to send me pull requests or email(jaechang@postech.ac.kr).

## Table of contents

* What is source separation?
* survey papers
* papers
* datasets
* open-source projects
* competitions

## What is Source Separation?

Separating a mixture into sources. Major researches are about sound source separation. You can refer Stöter's [nice tutorials](https://sigsep.github.io/tutorials). As the problem itself is an under-determined problem(for single-channel), additional priors should be used. The priors include distrubution of sources and addtional information(score, video, ...).

## Survey Papers

* [An Overview of Lead and Accompaniment Separation in Music](https://arxiv.org/abs/1804.08300) - Z. Rafii et al., 2018

## Papers

### supervised source separation

* [Deep clustering: Discriminative embeddings for segmentation and separation](https://ieeexplore.ieee.org/abstract/document/7471631) - J. Hershey et al., ICASSP 2016
* [Conv-TasNet: Surpassing Ideal Time-Frequency Magnitude Masking for Speech Separation](https://arxiv.org/abs/1809.07454) - Yi Luo et al., TASLP 2019
* wave-u-net
* [Permutation invariant training of deep models for speaker-independent multi-talker speech separation](https://arxiv.org/abs/1607.00325) - D. Yu et al., ICASSP 2017
* Voice Separation with an Unknown Number of Multiple Speakers
* [Demucs](https://github.com/facebookresearch/demucs) - A. Défossez, 2021, 
	* https://arxiv.org/abs/2111.03600 (version 3)
* [HIERARCHICAL MUSICAL INSTRUMENT SEPARATION](https://program.ismir2020.net/static/final_papers/105.pdf) - E. Manilow et al., ISMIR 2020.

### source separation with additional information

* Score-informed source separation of choral music
* AUDIO QUERY-BASED MUSIC SOURCE SEPARATION
* Weakly informed audio source separation
* Conditioned Source Separation for Musical Instrument Performances.
* [Co-separating sounds of visual objects](https://arxiv.org/abs/1904.07750) - R. Gao et al., ICCV 2019

### unsupervised source separation

* [Unsupervised Sound Separation Using Mixture Invariant Training](https://arxiv.org/abs/2006.12701) - S. Wisdom et al., NeurIPS 2020.

### universal sound source separation

* [Universal sound separation](https://arxiv.org/abs/1905.03330) - I. Kavalerov, WASPAA 2019.

### source localization based method

* [The Cone of Silence: Speech Separation by Localization](https://arxiv.org/abs/2010.06007) - T. Jenrungrot, NeurIPS 2020.

### Evaluation Metrics

* [Performance measurement in blind audio source separation](https://ieeexplore.ieee.org/document/1643671) - E. Vincent, TASLP 2006
* [SDR – Half-baked or Well Done?](https://ieeexplore.ieee.org/abstract/document/8683855) - J. Le Roux, ICASSP 2019.

## Datasets

* MUSDB18 (for music)
* wsj0 (for speech)
* WHAM! 
* FUSS (for universal source separation)

## Open-Source Projects

* asteroid

## Competitions

* sisec 2018
* Music Demixing Challenge 2021

