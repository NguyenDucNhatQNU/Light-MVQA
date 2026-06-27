# Light-MVQA: A Small Vision-Language Model Based Approach using Multimodal Retrieval-Augmented Generation for Medical Visual Question Answering

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)

---

## Abstract

The advancement of vision-language model applications in the medical field has led to the emergence of medical visual question answering. Through continuous evolution, contemporary systems have achieved high accuracy while mitigating constraints related to hallucination and the lack of specialized medical expertise via multimodal retrieval-augmented generation. However, the deployment of large-scale models introduces inevitable bottlenecks regarding computing resources and operational costs. Recognizing this limitation, we propose a novel approach that utilizes a more compact model for answer generation, integrated with the capability to retrieve medical evidence from database. Experimental results confirm that overall performance remains highly optimized, without being significantly compromised by the reduction in model scale. Furthermore, the operational performance demonstrates the superior feasibility of small models for real-world deployment on edge devices. Our research holds substantial potential for practical application in healthcare and clinical facilities, ultimately streamlining access to clinical question-answering services for users.

## Citation

If you use this code or our results in your research, please cite our paper:

```bibtex
@article{Nguyen2026,
  title={Light-MFND: Efficient Multimodal Fake News Detection via Fine-Tuned Small Vision-Language Models},
  author={Nguyen, Duc-Nhat and Phan, Khac-Lap and Le, Quang-Hung},
  year={2026}
}
```
