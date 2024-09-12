---
layout: default
is_contact: true
---

## Selected Publications

[**A predictive learning model can simulate temporal dynamics and context effects found in neural representations of continuous speech**](https://arxiv.org/pdf/2405.08237) <span class="subline">[[slides]](Cogsci_talk.pdf)</span>  
[*(Computational Modeling Prize in Perception & Action)*](https://cognitivesciencesociety.org/conference-awards/)

Oli Danyi Liu, Hao Tang, Naomi Feldman, Sharon Goldwater. In <em>Proceedings of the 46th Annual Conference of the Cognitive Science Society</em>. 2024.

Speech perception involves storing and integrating sequentially presented items. Recent work in cognitive neuroscience has identified temporal and contextual characteristics in humans’ neural encoding of speech that may facilitate this temporal processing. In this study, we simulated similar analyses with representations extracted from a computational model that was trained on unlabelled speech with the learning objective of pre- dicting upcoming acoustics. Our simulations revealed temporal dynamics similar to those in brain signals, implying that these properties can arise without linguistic knowledge. Another property shared between brains and the model is that the encod- ing patterns of phonemes support some degree of cross-context generalization. However, we found evidence that the effective- ness of these generalizations depends on the specific contexts, which suggests that this analysis alone is insufficient to support the presence of context-invariant encoding.

<details>
  <summary>bib</summary>
     <pre>@inproceedings{liu.tang.ea:predictive,
  title = {A predictive learning model can simulate temporal dynamics and context effects found in neural representations of continuous speech},
  author = {Liu, Oli Danyi and Tang, Hao and Feldman, Naomi H. and Goldwater, Sharon},
  booktitle = {Proceedings of the 46th Annual Conference of the Cognitive Science Society},
  year = {2024}
}</pre>
</details>

[**Self-supervised Predictive Coding Models Encode Speaker and Phonetic Information in Orthogonal Subspaces**](https://arxiv.org/pdf/2305.12464.pdf) 

Oli Danyi Liu, Hao Tang, Sharon Goldwater. In <em>Proceedings of Interspeech</em>. 2023.

Self-supervised speech representations are known to encode both speaker and phonetic information, but how they are distributed in the high-dimensional space remains largely unexplored. We hypothesize that they are encoded in orthogonal subspaces, a property that lends itself to simple disentanglement. Applying principal component analysis to representations of two predictive coding models, we identify two subspaces that capture speaker and phonetic variances, and confirm that they are nearly orthogonal. Based on this property, we propose a new speaker normalization method which collapses the subspace that encodes speaker information, without requiring transcriptions. Probing experiments show that our method effectively eliminates speaker information and outperforms a previous baseline in phone discrimination tasks. Moreover, the approach generalizes and can be used to remove information of unseen speakers.

<details>
  <summary>bib</summary>
     <pre>@inproceedings{liu.tang.ea:self-supervised,   
  author={Oli Danyi Liu and Hao Tang and Sharon Goldwater},     
  title={Self-supervised Predictive Coding Models Encode Speaker and Phonetic Information in Orthogonal Subspaces},   
  year=2023,   
  booktitle={Proc. INTERSPEECH 2023},   
  pages={2968--2972},   
  doi={10.21437/Interspeech.2023-871}   
  }</pre>
</details>

[**Orthogonality and isotropy of speaker and phonetic information in self-supervised speech representations**](https://www.isca-archive.org/interspeech_2024/mohamed24_interspeech.pdf)  <span class="subline">[[poster]](interspeech_poster.pdf)</span>  

Mukhtar Mohamed, Oli Danyi Liu, Hao Tang, Sharon Goldwater. In <em>Proceedings of Interspeech</em>. 2024.

Self-supervised speech representations are known to encode both speaker and phonetic information, but how they are distributed in the high-dimensional space remains largely unexplored. We hypothesize that they are encoded in orthogonal subspaces, a property that lends itself to simple disentanglement. Applying principal component analysis to representations of two predictive coding models, we identify two subspaces that capture speaker and phonetic variances, and confirm that they are nearly orthogonal. Based on this property, we propose a new speaker normalization method which collapses the subspace that encodes speaker information, without requiring transcriptions. Probing experiments show that our method effectively eliminates speaker information and outperforms a previous baseline in phone discrimination tasks. Moreover, the approach generalizes and can be used to remove information of unseen speakers.

<details>
  <summary>bib</summary>
     <pre>@inproceedings{mohamed24_interspeech,
  title={Orthogonality and isotropy of speaker and phonetic information in self-supervised speech representations},
  author={Mukhtar Mohamed and Oli Danyi Liu and Hao Tang and Sharon Goldwater},
  year={2024},
  booktitle={Interspeech 2024},
  pages={3625--3629},
  doi={10.21437/Interspeech.2024-1054},
}</pre>
</details>
