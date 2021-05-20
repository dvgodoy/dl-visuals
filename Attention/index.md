## Index

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

## Papers

- Encoder-Decoder Architecture: [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/2014/hash/a14ac55a4f27472c5d894ec1c3c743d2-Abstract.html) by Sutskever, I. et al. (2014)
- Scaled Dot Product / Self-Attention: [Attention Is All You Need](https://arxiv.org/abs/1706.03762) by Vaswani, A. et al. (2017)

## Attention

### Scaled Dot Product

![](aiayn_dot.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Alignment Scores

![](score_alignment.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Context Vector

![](context_vector.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](multiple_keys_context.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Cross-Attention

![](attention.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](cross_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Encoder+Decoder+Cross-Attention

![](encdec_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Translation Example

![](kq_matches.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](score_alignment_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](context_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](translation_attn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](encdec_attn_translate.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

### Multi-Headed Attention

![](aiayn_multihead.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Wide Attention

![](multiattn.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

#### Narrow Attention

![](multihead_chunking.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

![](attn_narrow_first_head.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

![](attn_narrow_2heads.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

## Self-Attention

### Encoder

![](encoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](encoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](encoder_self_detail.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](enc_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Decoder

![](decoder_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](decoder_self.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*

![](dec_both.png)
*Source: [Chapter 10](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter10.ipynb)*

### Encoder+Decoder

![](encdec_self_simplified.png)
*Source: [Chapter 9](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/Chapter09.ipynb)*