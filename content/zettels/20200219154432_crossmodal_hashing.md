+++
title = "Cross-modal Hashing"
author = ["Jethro Kuan"]
lastmod = 2020-02-21T15:10:21+08:00
slug = "crossmodal_hashing"
draft = false
+++

Cross-modal hashing is the compression of high dimensional data into
compact binary codes with similar binary codes for similar objects.
The key ideas is to create codes for cross-modal retrieval. The
constraints are :

1.  It has to be an N-dimensional hamming space -- a binary
    representation with a controllable number of bits.
2.  The same object from different modalities has to have a similar
    hash code
3.  The space has to be similarity-preserving

<a id="fe1ca450aa5e404428b89a0e174b2e99" href="#baltrusaitis17:_multim_machin_learn">(Baltru\vsaitis et al., 2017)</a> has some good reference
papers.

# Bibliography
<a id="baltrusaitis17:_multim_machin_learn" target="_blank">Baltru\vsaitis, Tadas, Ahuja, C., & Morency, L., *Multimodal machine learning: a survey and taxonomy*, CoRR, *()*,  (2017). </a> [↩](#fe1ca450aa5e404428b89a0e174b2e99)
