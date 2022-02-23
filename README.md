
# Awesome Sound Source Separation: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of source separation, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

This list may contain incorrect informations and I don't want this list to be exhaustive. If I miss **important** papers or anyone found incorrect informations, please let me know via Github issue.

This list mainly focuses on deep learning based models. 

** WIP: This list is in construction. ** 

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

* deep clustering
* conv-tasnet / tasnet / dual-path
* wave-u-net
* Permutation invariant training of deep models for speaker-independent multi-talker speech separation
* Voice Separation with an Unknown Number of Multiple Speakers
* demucs
* HIERARCHICAL MUSICAL INSTRUMENT SEPARATION

### source separation with additional information

* Score-informed source separation of choral music
* AUDIO QUERY-BASED MUSIC SOURCE SEPARATION
* Weakly informed audio source separation
* Conditioned Source Separation for Musical Instrument Performances.

### unsupervised source separation

* MixIT

### universal sound source separation

* Universal sound separation

### source localization based 

* The Cone of Silence: Speech Separation by Localization

### Evaluation Metrics

* Performance measurement in blind audio source separation
* SDR – Half-baked or Well Done?

## Datasets

* MUSDB18
* wsj0
* WHAM!

## Open-Source Projects

* asteroid

## Competitions

* sisec 2018
* Music Demixing Challenge 2021

