---
layout: default
is_contact: true
---

## Publications


[**Self-supervised Predictive Coding Models Encode Speaker and Phonetic Information in Orthogonal Subspaces**](https://arxiv.org/pdf/2305.12464.pdf) 

Oli Liu, Hao Tang, Sharon Goldwater. In <em>Proceedings of Interspeech</em>. 2023.

Self-supervised speech representations are known to encode both speaker and phonetic information, but how they are distributed in the high-dimensional space remains largely unexplored. We hypothesize that they are encoded in orthogonal subspaces, a property that lends itself to simple disentanglement. Applying principal component analysis to representations of two predictive coding models, we identify two subspaces that capture speaker and phonetic variances, and confirm that they are nearly orthogonal. Based on this property, we propose a new speaker normalization method which collapses the subspace that encodes speaker information, without requiring transcriptions. Probing experiments show that our method effectively eliminates speaker information and outperforms a previous baseline in phone discrimination tasks. Moreover, the approach generalizes and can be used to remove information of unseen speakers.

<details>
  <summary>bib</summary>
     <pre>@inproceedings{liu.tang.ea:self-supervised,   
  author={Oli Danyi Liu and Hao Tang and Sharon Goldwater},     
  title={{Self-supervised Predictive Coding Models Encode Speaker and Phonetic Information in Orthogonal Subspaces}},   
  year=2023,   
  booktitle={Proc. INTERSPEECH 2023},   
  pages={2968--2972},   
  doi={10.21437/Interspeech.2023-871}   
  }</pre>
</details>


[**Content-aware speaker embeddings for speaker diarisation**](https://arxiv.org/pdf/2102.06467.pdf)

Guangzhi Sun, Danyi Liu, Chao Zhang, Philip C Woodland. In <em>Proceedings of ICASSP</em>. 2021.

Recent speaker diarisation systems often convert variable length speech segments into fixed-length vector representations for speaker clustering, which are known as speaker embeddings. In this paper, the content-aware speaker embeddings (CASE) approach is proposed, which extends the input of the speaker classifier to include not only acoustic features but also their corresponding speech content, via phone, character, and word embeddings. Compared to alternative methods that leverage similar information, such as multitask or adversarial training, CASE factorises automatic speech recognition (ASR) from speaker recognition to focus on modelling speaker characteristics and correlations with the corresponding content units to derive more expressive representations. CASE is evaluated for speaker re-clustering with a realistic speaker diarisation setup using the AMI meeting transcription dataset, where the content information is obtained by performing ASR based on an automatic segmentation. Experimental results showed that CASE achieved a 17.8% relative speaker error rate reduction over conventional methods.

<details>
  <summary>bib</summary>
     <pre>@inproceedings{sun.liu.ea:context,  
  author={Sun, G. and Liu, D. and Zhang, C. and Woodland, P. C.},  
  booktitle={ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},   
  title={Content-Aware Speaker Embeddings for Speaker Diarisation},   
  year={2021},  
  volume={},  
  number={},  
  pages={7168-7172},  
  doi={10.1109/ICASSP39728.2021.9414390}   
  }</pre>
</details>

