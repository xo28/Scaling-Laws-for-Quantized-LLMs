# Scaling-Laws-for-Quantized-LLMs <br> [📑[Paper link]](https://arxiv.org/pdf/2411.17691) [💽[Checkpoints]](https://huggingface.co/Xu-Ouyang) 
### Low-Bit Quantization Favors Undertrained LLMs: Scaling Laws for Quantized LLMs with 100T Training Tokens.<br> Current LLM quantization algorithms may fail when the LLMs are fully trained.

Low-bit quantization improves machine learning model efficiency but surprisingly favors undertrained large language models (LLMs). Larger models or those trained on fewer tokens exhibit less quantization-induced degradation (QiD), while smaller, well-trained models face significant performance losses.

Our projection shows that the low-bit quantization performance of future models, which are expected to be trained with over 100 trillion tokens, may NOT be desirable. This poses a potential challenge for low-bit quantization in the future and highlights the need for awareness of a model's training level when evaluating low-bit quantization research. To facilitate future research on this problem, we release all the <em><strong>1500+</strong></em> quantized checkpoints used in this work at [Huggingface](https://huggingface.co/Xu-Ouyang).

## Reference
Feel free to use our results and checkpoints! If you find they are useful, please cite the following paper. Appreciate! <br>
<strong>*Low-Bit Quantization Favors Undertrained LLMs: Scaling Laws for Quantized LLMs with 100T Training Tokens*</strong>
```
@article{ouyang2024low,
  title={Low-Bit Quantization Favors Undertrained LLMs: Scaling Laws for Quantized LLMs with 100T Training Tokens},
  author={Ouyang, Xu and Ge, Tao and Hartvigsen, Thomas and Zhang, Zhisong and Mi, Haitao and Yu, Dong},
  journal={arXiv preprint arXiv:2411.17691},
  year={2024}
}
```

## Code will be released soon.
