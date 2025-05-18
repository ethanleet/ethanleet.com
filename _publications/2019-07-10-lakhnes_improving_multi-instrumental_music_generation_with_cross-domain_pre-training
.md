---
title: "LakhNES: Improving multi-instrumental music generation with cross-domain pre-training"
collection: publications
category: conferences
permalink: /publication/2019-07-10-lakhnes_improving_multi-instrumental_music_generation_with_cross-domain_pre-training
excerpt: 'We are interested in the task of generating multi-instrumental music scores. The Transformer architecture has recently shown great promise for the task of piano score generation; here we adapt it to the multi-instrumental setting. Transformers are complex, high-dimensional language models which are capable of capturing long-term structure in sequence data, but require large amounts of data to fit. Their success on piano score generation is partially explained by the large volumes of symbolic data readily available for that domain. We leverage the recently-introduced NES-MDB dataset of four-instrument scores from an early video game sound synthesis chip (the NES), which we find to be well-suited to training with the Transformer architecture. To further improve the performance of our model, we propose a pre-training technique to leverage the information in a large collection of heterogeneous music, namely the Lakh MIDI dataset. Despite differences between the two corpora, we find that this transfer learning procedure improves both quantitative and qualitative performance for our primary task.'
date: 2019-11-04
venue: 'International Society for Music Information Retrieval (ISMIR)'
paperurl: 'https://zenodo.org/records/3527902'
citation: 'Donahue, C., Mao, H. H., Li, Y. E., Cottrell, G. W., and
McAuley, J. J. LakhNES: Improving multi-instrumental
music generation with cross-domain pre-training. In <i>International Society for Music Information Retrieval Conference</i>, pp. 685–692, 2019.'
---

We are interested in the task of generating multi-instrumental music scores. The Transformer architecture has recently shown great promise for the task of piano score generation; here we adapt it to the multi-instrumental setting. Transformers are complex, high-dimensional language models which are capable of capturing long-term structure in sequence data, but require large amounts of data to fit. Their success on piano score generation is partially explained by the large volumes of symbolic data readily available for that domain. We leverage the recently-introduced NES-MDB dataset of four-instrument scores from an early video game sound synthesis chip (the NES), which we find to be well-suited to training with the Transformer architecture. To further improve the performance of our model, we propose a pre-training technique to leverage the information in a large collection of heterogeneous music, namely the Lakh MIDI dataset. Despite differences between the two corpora, we find that this transfer learning procedure improves both quantitative and qualitative performance for our primary task.

[Source code (GitHub)](https://github.com/chrisdonahue/LakhNES)\
[Music sample](https://chrisdonahue.com/LakhNES/)
