---
layout: default
img: enc_data_processing.png
title: Encrypted Data Processing
description: |
---

In order to enable users to regain control over their data and therefore privacy, Shafagh et al. developed Talos, a cryptographic tool-set to enable encrypted query processing for mobile devices and embedded Internet of Things (IoT) devices. It is based on the idea of combining Partial Homomorphic Encryption and Property Preserving Encryption, first introduced in [CryptDB](https://css.csail.mit.edu/cryptdb/). A remote (e.g. cloud-hosted) Database is used to store encrypted values. Thanks to the properties of the mentioned encryption schemes we can still execute many SQL queries over the data while giving up only small amounts of information about the plaintext data.

