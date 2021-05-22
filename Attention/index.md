# Attention

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

These images were originally published in the book ["Deep Learning with PyTorch Step-by-Step: A Beginner's Guide"](https://leanpub.com/pytorch).

They are also available at the book's official repository: [https://github.com/dvgodoy/PyTorchStepByStep](https://github.com/dvgodoy/PyTorchStepByStep).

## Index

- [Back](https://github.com/dvgodoy/dl-visuals)
- [Attention](#attention)
	- [Scaled Dot Product](#scaled-dot-product)
	    - [Alignment Scores](#alignment-scores)
	    - [Context Vector](#context-vector)
	    - [Attention Scores](#attention-scores)
	        - [Encoder](#encoder)
	        - [Decoder](#decoder)
	            - [Masked](#masked)
	    - [Translation Example](#translation-example)
	- [Cross-Attention](#cross-attention)
	    - [Encoder + Decoder + Cross-Attention](#encoder+decoder+cross-attention)
	- [Multi-Headed Attention](#multi-headed-attention)
	    - [Wide](#wide-attention)
	    - [Narrow](#narrow-attention)
- [Self-Attention](#self-attention)
    - [Self-Attention Encoder](#self-attention-encoder)
    - [Self-Attention Decoder](#self-attention-decoder)
    - [Encoder+Decoder](#decoder)

### **** CLICK ON THE IMAGES FOR FULL SIZE ****

## Papers

- Encoder-Decoder Architecture: [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/2014/hash/a14ac55a4f27472c5d894ec1c3c743d2-Abstract.html) by Sutskever, I. et al. (2014)
- Scaled Dot Product / Self-Attention: [Attention Is All You Need](https://arxiv.org/abs/1706.03762) by Vaswani, A. et al. (2017)

## Attention

### Scaled Dot Product

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/aiayn_dot.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.3.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.4.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.5.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.8.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Alignment Scores

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/score_alignment.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Context Vector

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/context_vector.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/multiple_keys_context.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Attention Scores

#### Encoder

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.11.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.12.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.12.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Decoder

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.14.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.15.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.16.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

##### Masked

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.17.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Cross-Attention

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/attention.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/cross_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Encoder+Decoder+Cross-Attention

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/encdec_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Translation Example

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/kq_matches.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/eq09.1.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/context_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/score_alignment_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/translation_att.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/enc_dec_attn_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Multi-Headed Attention

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/aiayn_multihead.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Wide Attention

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/multiattn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Narrow Attention

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/multihead_chunking.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/attn_narrow_first_head.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/attn_narrow_2heads.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

## Self-Attention

### Self-Attention Encoder

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/encoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/encoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/encoder_self_detail.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/enc_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Self-Attention Decoder

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/decoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/decoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/dec_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Encoder+Decoder

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Attention/encdec_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
