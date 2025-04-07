---
title: "Automatic Learning of Subword Dependent Model Scales"
collection: publications
category: conferences
permalink: /publication/2022-subword-dependent-model-scales
excerpt: 'Improving combination of an attention-based encoder-decoder acoustic model and a language model by using individual scaling parameters per subword output token in the context of automatic speech recognition.'
date: 2022
venue: 'Interspeech 2022'
paperurl: 'https://www.isca-archive.org/interspeech_2022/meyer22_interspeech.html#'
citation: 'Meyer, F., Michel, W., Zeineldeen, M., Schlüter, R., Ney, H. (2022) Automatic Learning of Subword Dependent Model Scales. Proc. Interspeech 2022, 4133-4136, doi: 10.21437/Interspeech.2022-10136'
---

**Abstract**
To improve the performance of state-of-the-art automatic speech recognition systems it is common practice to include external knowledge sources such as language models or prior corrections. This is usually done via log-linear model combination using separate scaling parameters for each model. Typically these parameters are manually optimized on some held-out data. In this work we propose to use individual scaling parameters per subword output token. We train these parameters via automatic differentiation and stochastic gradient decent optimization similar to the neural network model parameters. We show on the LibriSpeech (LBS) and Switchboard (SWB) corpora that automatic learning of two scales for a combination of attention-based encoder-decoder acoustic model and language model can be done as effectively as with manual tuning. Using subword dependent model scales which could not be tuned manually we achieve 7% improvement on LBS and 3% on SWB. We also show that joint training of scales and model parameters is possible and gives additional 6% improvement on LBS.