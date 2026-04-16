# DialSeg-Ar

[![Hugging Face Model](https://img.shields.io/badge/Hugging%20Face-Model-yellow?logo=huggingface&logoColor=white)](https://huggingface.co/MBZUAI/dialseg-ar-gemma3-4B)
[![Hugging Face Dataset](https://img.shields.io/badge/Hugging%20Face-Dataset-orange?logo=huggingface&logoColor=white)](https://huggingface.co/datasets/MBZUAI/dialseg-ar)
[![Paper](https://img.shields.io/badge/Paper-coming_soon-blue)](TODO_PAPER_URL)

**DialSeg-Ar** is a benchmark and baseline system for **linear semantic segmentation** in **dialectal conversational Arabic**.

It accompanies the paper:

**Linear Semantic Segmentation for Low-Resource Spoken Dialects**  
Kirill Chirkunov, Younes Samih, Abed Alhakim Freihat, Hanan Aldarmaki

## Resources

- **Dataset:** [MBZUAI/dialseg-ar](https://huggingface.co/datasets/MBZUAI/dialseg-ar)
- **Model:** [MBZUAI/dialseg-ar-gemma3-4B](https://huggingface.co/MBZUAI/dialseg-ar-gemma3-4B)
- **Paper:** [coming soon](TODO_PAPER_URL)

## About

DialSeg-Ar is a multi-genre benchmark for semantic segmentation in Arabic, with a focus on dialectal and transcript-like data, including:

- telephone conversations
- code-switched Gulf Arabic–English podcasts
- dialogue extracted from novels
- MSA news commentary
- other challenging discourse settings

The released model, **DialSeg-Ar-Gemma3-4B**, is a Gemma-based segmenter trained to split ordered utterances into topic-coherent segments.

## Repository Status

**Source code will be released later.**


## Citation

If you use this work, please cite:

```bibtex
@inproceedings{dialsegar2026,
  title     = {Linear Semantic Segmentation for Low-Resource Spoken Dialects},
  author    = {Chirkunov, Kirill and Samih, Younes and Freihat, Abed Alhakim and Aldarmaki, Hanan},
  booktitle = {Proceedings of ACL 2026},
  year      = {2026}
}
```
