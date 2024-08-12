# KoSAIM2024-Clinical-LLM

This repository is for the session 3 (large language model) in [KoSAIM 2024 Summer School].

## Main Materials
- [Lecture Slides](https://docs.google.com/presentation/d/1OKYCo2aSuOo7nkus6ly2rrECpG_5QkPC6Hg3d1ooz3A/edit?usp=sharing)
- [Colab Link](https://colab.research.google.com/drive/1UGfib5xlepFu-b0bmwTLGvR07hvJKJS4?usp=sharing)

## Contents
- How to build a clinical domain Large Language Model (LLM)?
  - (Large) Language Model
  - How to build a (large) language model?
  - Building an instruction-following LLM in the clinical domain
  - Asclepius (Gweon and Kim et al., ACL 2024 Findings)
- Hands-on Session: Fine-tuning a clinical domain LLM
  - Environment Setup & Colab Practice
  - LLM memory layout
  - Parameter-Efficient Fine-Tuning (LoRA/QLoRA)
 
## Useful Resources
- [https://github.com/huggingface/transformers](https://github.com/huggingface/transformers)
- [https://github.com/huggingface/trl](https://github.com/huggingface/trl)
- [https://github.com/huggingface/accelerate](https://github.com/huggingface/accelerate)
- [https://github.com/huggingface/peft](https://github.com/huggingface/peft)
- [https://github.com/bitsandbytes-foundation/bitsandbytes](https://github.com/bitsandbytes-foundation/bitsandbytes)
- [https://github.com/starmpcc/Asclepius](https://github.com/starmpcc/Asclepius)
- [starmpcc/Asclepius-Synthetic-Clinical-Notes](starmpcc/Asclepius-Synthetic-Clinical-Notes)

## References
- `BERT` [Devlin, Jacob. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805 (2018).](https://arxiv.org/pdf/1810.04805)
- `GPT` [Radford, Alec, et al. "Improving Language Understanding by Generative Pre-Training."](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)
- `T5` [Raffel, Colin, et al. "Exploring the limits of transfer learning with a unified text-to-text transformer." Journal of machine learning research 21.140 (2020): 1-67.](https://www.jmlr.org/papers/volume21/20-074/20-074.pdf)
- [Liu, Pengfei, et al. "Pre-train, prompt, and predict: A systematic survey of prompting methods in natural language processing." ACM Computing Surveys 55.9 (2023): 1-35.](https://dl.acm.org/doi/pdf/10.1145/3560815)
- `GPT-3` [Brown, Tom, et al. "Language models are few-shot learners." Advances in neural information processing systems 33 (2020): 1877-1901.](https://proceedings.neurips.cc/paper_files/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf)
- `FLAN` [Wei, Jason, et al. "Finetuned language models are zero-shot learners." arXiv preprint arXiv:2109.01652 (2021).](https://arxiv.org/pdf/2109.01652)
- `Llama` [Touvron, Hugo, et al. "Llama: Open and efficient foundation language models." arXiv preprint arXiv:2302.13971 (2023).](https://arxiv.org/pdf/2302.13971)
- `RLHF` [Ouyang, Long, et al. "Training language models to follow instructions with human feedback." Advances in neural information processing systems 35 (2022): 27730-27744.](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf)
- `ChatGPT` [https://openai.com/index/chatgpt/](https://openai.com/index/chatgpt/)
- `Llama 2` [Touvron, Hugo, et al. "Llama 2: Open foundation and fine-tuned chat models." arXiv preprint arXiv:2307.09288 (2023).](https://arxiv.org/pdf/2307.09288)
- `Llama 3` [Dubey, Abhimanyu, et al. "The Llama 3 Herd of Models." arXiv preprint arXiv:2407.21783 (2024).](https://arxiv.org/pdf/2407.21783)
- `DPO` [Rafailov, Rafael, et al. "Direct preference optimization: Your language model is secretly a reward model." Advances in Neural Information Processing Systems 36 (2024).](https://proceedings.neurips.cc/paper_files/paper/2023/file/a85b405ed65c6477a4fe8302b5e06ce7-Paper-Conference.pdf)
- `Alpaca` [Taori, Rohan, et al. "Alpaca: A strong, replicable instruction-following model." Stanford Center for Research on Foundation Models. https://crfm. stanford. edu/2023/03/13/alpaca. html 3.6 (2023): 7.](https://crfm.stanford.edu/2023/03/13/alpaca.html)
- `Asclepius` [Kweon, Sunjun, et al. "Publicly Shareable Clinical Large Language Model Built on Synthetic Clinical Notes." arXiv preprint arXiv:2309.00237 (2023).](https://arxiv.org/pdf/2309.00237)
- `Lora` [Hu, Edward J., et al. "Lora: Low-rank adaptation of large language models." arXiv preprint arXiv:2106.09685 (2021).](https://arxiv.org/pdf/2106.09685)
- `QLora` [Dettmers, Tim, et al. "Qlora: Efficient finetuning of quantized llms." Advances in Neural Information Processing Systems 36 (2024).](https://proceedings.neurips.cc/paper_files/paper/2023/file/1feb87871436031bdc0f2beaa62a049b-Paper-Conference.pdf)
