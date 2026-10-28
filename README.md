### Justin Barber

Machine learning scientist and engineer in Colorado, working in NLP since 2014. I build the data
and evaluation side of model training: multi-agent LLM annotation pipelines, synthetic data with
rejection loops, LLM-as-judge panels validated against human raters, and the encoder models and
services trained on what they produce. Most of it is automated scoring of writing and speech,
where a model ships only once it matches human-to-human agreement. Lately also generative
models, post-training, and agent harnesses.

Fifteen peer-reviewed conference papers and presentations since 2021 (NCME, AIME-Con, ITC, a
NeurIPS workshop) on synthetic data, LLM evaluation, label quality, active learning and
confidence modeling.

**Selected projects**

| | |
|---|---|
| [essay-scoring](https://github.com/jobarber/essay-scoring) | Prompt-specific essay scoring on ASAP 2.0: LoRA-tuned DeBERTa-v3 and ModernBERT, Optuna search per prompt, agreement, score-point recall and subgroup SMD for each prompt. |
| [speech-proficiency-scoring](https://github.com/jobarber/speech-proficiency-scoring) | Explainable read-aloud scoring: Whisper timings, forced-alignment pronunciation scores, one model per construct, conformal intervals, feedback grounded in the model's own evidence. |
| [progan](https://github.com/jobarber/progan) | Progressive growing of GANs from scratch in PyTorch, trained to 128x128 on a laptop GPU. |

Python, PyTorch, Hugging Face Transformers, Optuna, ONNX Runtime, AWS (EKS, Bedrock), Kubernetes, uv.
