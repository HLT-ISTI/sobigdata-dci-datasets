# SoBigData DCI Dataset

This repository hosts demo datasets that can be used with the DCI transfer learning method published on the [Virtual Research Environment](https://sobigdata.d4science.org/) (VRE) of the [SoBigData project](http://project.sobigdata.eu/).

The DCI method has been published in:

Alejandro Moreo Fernández, Andrea Esuli, and Fabrizio Sebastiani. 
Distributional Correspondence Indexing for Cross-Lingual and Cross-Domain Sentiment Classification.](https://jair.org/index.php/jair/article/view/10977) 
Journal of Artificial Intelligence Research 55: 131-163 (2016)

The original [Webis-CLS-10](https://webis.de/data/webis-cls-10.html) dataset has been created by Peter Prettenhofer and Benno Stein and published in:

Peter Prettenhofer and Benno Stein.
[Cross-Language Text Classification using Structural Correspondence Learning.](https://webis.de/downloads/publications/papers/prettenhofer_2010.pdf)
In Jan Hajič, Sandra Carberry, Stephen Clark, and Joakim Nivre, editors, 48th Annual Meeting of the Association of Computational Linguistics (ACL 2010), pages 1118-1127, July 2010. Association for Computational Linguistics.

The original dataset is published on [Zenodo](https://zenodo.org/record/3251672#.YG2WUOgzZaR) under a [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode)


The version published in this repository (Webis-CLS-10-SBD) is a subset rearranged to be usable with the interface of the methods available on the VRE.
Japanese documents have been removed, due to lack of proper tokenization method in the VRE implementation.
German unlabeled set has been reduced, to fit the 100MB size limit on Github.
The aim of Webis-CLS-10-SBD is only to show how to set up your data to run transfer learning experiments.
