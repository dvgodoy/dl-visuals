# Attention


## Index

- [Back](https://dvgodoy.github.io/dl-visuals)
- [Attention](#attention)
	- [Scaled Dot Product](#scaled-dot-product)
	    - [Alignment Scores](#alignment-scores)
	    - [Context Vector](#context-vector)
	    - [Translation Example](#translation-example)
	- [Cross-Attention](#cross-attention)
	    - [Encoder + Decoder + Cross-Attention](#encoder+decoder+cross-attention)
	- [Multi-Headed Attention](#multi-headed-attention)
	    - [Wide](#wide-attention)
	    - [Narrow](#narrow-attention)
- [Self-Attention](#self-attention)
    - [Encoder](#encoder)
    - [Decoder](#decoder)
    - [Encoder+Decoder](#decoder)

### **** CLICK ON THE IMAGES FOR FULL SIZE ****

## Papers

- Encoder-Decoder Architecture: [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/2014/hash/a14ac55a4f27472c5d894ec1c3c743d2-Abstract.html) by Sutskever, I. et al. (2014)
- Scaled Dot Product / Self-Attention: [Attention Is All You Need](https://arxiv.org/abs/1706.03762) by Vaswani, A. et al. (2017)

## Attention

### Scaled Dot Product

[![](aiayn_dot.png)](https://dvgodoy.github.io/dl-visuals/Attention/aiayn_dot.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Alignment Scores

[![](score_alignment.png)](https://dvgodoy.github.io/dl-visuals/Attention/score_alignment.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Context Vector

[![](context_vector.png)](https://dvgodoy.github.io/dl-visuals/Attention/context_vector.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](multiple_keys_context.png)](https://dvgodoy.github.io/dl-visuals/Attention/multiple_keys_context.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Cross-Attention

[![](attention.png)](https://dvgodoy.github.io/dl-visuals/Attention/attention.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](cross_attn.png)](https://dvgodoy.github.io/dl-visuals/Attention/cross_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Encoder+Decoder+Cross-Attention

[![](encdec_attn.png)](https://dvgodoy.github.io/dl-visuals/Attention/encdec_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Translation Example

[![](kq_matches.png)](https://dvgodoy.github.io/dl-visuals/Attention/kq_matches.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](score_alignment_translate.png)](https://dvgodoy.github.io/dl-visuals/Attention/score_alignment_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](context_translate.png)](https://dvgodoy.github.io/dl-visuals/Attention/context_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](translation_att.png)](https://dvgodoy.github.io/dl-visuals/Attention/translation_att.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](enc_dec_attn_translate.png)](https://dvgodoy.github.io/dl-visuals/Attention/enc_dec_attn_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Multi-Headed Attention

[![](aiayn_multihead.png)](https://dvgodoy.github.io/dl-visuals/Attention/aiayn_multihead.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Wide Attention

[![](multiattn.png)](https://dvgodoy.github.io/dl-visuals/Attention/multiattn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Narrow Attention

[![](multihead_chunking.png)](https://dvgodoy.github.io/dl-visuals/Attention/multihead_chunking.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

[![](attn_narrow_first_head.png)](https://dvgodoy.github.io/dl-visuals/Attention/attn_narrow_first_head.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

[![](attn_narrow_2heads.png)](https://dvgodoy.github.io/dl-visuals/Attention/attn_narrow_2heads.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

## Self-Attention

### Encoder

[![](encoder_self_simplified.png)](https://dvgodoy.github.io/dl-visuals/Attention/encoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](encoder_self.png)](https://dvgodoy.github.io/dl-visuals/Attention/encoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](encoder_self_detail.png)](https://dvgodoy.github.io/dl-visuals/Attention/encoder_self_detail.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](enc_both.png)](https://dvgodoy.github.io/dl-visuals/Attention/enc_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Decoder

[![](decoder_self_simplified.png)](https://dvgodoy.github.io/dl-visuals/Attention/decoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](decoder_self.png)](https://dvgodoy.github.io/dl-visuals/Attention/decoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

[![](dec_both.png)](https://dvgodoy.github.io/dl-visuals/Attention/dec_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Encoder+Decoder

[![](encdec_self_simplified.png)](https://dvgodoy.github.io/dl-visuals/Attention/encdec_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*