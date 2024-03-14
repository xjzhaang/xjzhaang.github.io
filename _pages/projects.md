---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
I have had the opportunity contribute to the following projects in the past.
<br>

## BioimageLoader

> _Load bioimages for machine learning applications_

[![Python version](https://img.shields.io/pypi/pyversions/bioimageloader)](https://pypi.org/project/bioimageloader/)
[![PyPI version](https://img.shields.io/pypi/v/bioimageloader)](https://pypi.org/project/bioimageloader/)
[![PyPI download per month](https://img.shields.io/pypi/dm/bioimageloader)](https://pypi.org/project/bioimageloader/)
[![License](https://img.shields.io/github/license/LaboratoryOpticsBiosciences/bioimageloader)](https://github.com/LaboratoryOpticsBiosciences/bioimageloader/blob/main/LICENSE)

[_bioimageloader_](https://github.com/LaboratoryOpticsBiosciences/bioimageloader) is a python library to make it easy to load bioimage datasets for
machine learning and deep learning. Bioimages come in numerous and inhomogeneous forms. 
_bioimageloader_ attempts to wrap them in unified interfaces, so that you can easily
concatenate, perform image augmentation, and batch-load them.

**_bioimageloader_ provides**

1. collections of interfaces for popular and public bioimage datasets
2. image augmentation using [albumentations], which is popular and powerful
   image augmentation library (for 2D images)
3. compatibility with [pytorch]
4. and with others such as [scikit-learn] and [tensorflow]

<!-- links -->
[albumentations]: https://albumentations.ai/
[scikit-learn]:  https://scikit-learn.org/stable/index.html
[tensorflow]: https://www.tensorflow.org/
[pytorch]: https://pytorch.org/
[bioimageloader-docs]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/
[bioimageloader-docs:Installation]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/installation/index.html
[bioimageloader-docs:Catalogue]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/catalogue/index.html
[bioimageloader-docs:User Guides]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/user_guides/index.html
[templates]:  https://github.com/LaboratoryOpticsBiosciences/bioimageloader/blob/main/bioimageloader/template.py
[issue]: https://github.com/LaboratoryOpticsBiosciences/bioimageloader/issues
[Modifying existing collections]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/user_guides/more2_subclassing.html
[bioimageloader-docs:Contributing]: https://laboratoryopticsbiosciences.github.io/bioimageloader-docs/contributing/index.html
