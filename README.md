Support development (please):<br>
`btc on bitc network: 3JB6if8iTpWBbBGBdnoYZxpg3CZoLUUvYe`<br>
`eth on eth unified 0x3fad449e20b44308d80ec663cbc2408f8bb68804`<br>
`sol on sol EpxKy2DqsoALJC35BJ3ZPEoqPYqwQmVGC1BpqeT6vJHt`<br>
`xtz tz1ULvqesQA8SnopRzuQKFQj2jdLGBatJoC3`

## Monthly update
Jan 2024 - https://aicrumb.github.io/reports/012024/

## Various projects
### GLORT2
- GLORT2 (Glort2 Low Rank Transformer-Transformer), a transformer model where every linear layer is replaced with a smaller transformer.
- https://huggingface.co/crumb/GLORT2

| model | 512-token strided perplexity on a pile test set | tokens |
| --- | --- | --- | 
| cerebras 111m | 21.550655364990234 | 2.2b |
| cerebras 256m | 15.203496932983398 | 5.1b |
| cerebras 590m | 12.098200798034668 | 11.something b |
| deduped pythia 70m (95.6M) | 22.393400192260742 | 300b |
| deduped pythia 160m (213M) | 13.933751106262207 | 300b |
| deduped pythia 410m (506M) | 9.61842155456543 | 300b |
| llama w same settings as cerebras 111m (119m) | 13.882301330566406 | 2.2b |
| llama plus w same settings as cerebras 111m and llama 70b embeddings (369m) | 13.565109252929688 | 2.2b |
| **GLORT2 (205m)** | 13.051741600036621 | 2.2b |

### Reweighting
- Creating very small continued-pretraining datasets specifically to increase the size of the domain that a model performs well in
- https://crumbly.medium.com/reweighting-refining-ai-with-precision-and-efficiency-9a01c2ca4c26
  
![image](https://github.com/aicrumb/aicrumb/assets/58605641/c3cd1a2f-6840-4f26-9a65-a99e3608fad1)

### MoLora
- Mixture-of-experts LoRA, the first of it's kind on the Llama-2 models! (and looks like one of the first few finetunes!)
- medium blog post with proof of concept and inference code: https://crumbly.medium.com/llama-2-molora-f5f909434711

### GPT-2-Linear
- GPT-2 models converted to use linear layers, making them more compatible with existinf quantization and adapter code.
- model card: https://hf.co/crumbly/gpt2-linear-xl
- qlora finetuning notebook: https://hf.co/crumbly/gpt2-linear-xl/blob/main/GPT2_Linear_4bit_training.ipynb

### GPT-2023
- The base GPT2 model finetuned on 2.23B tokens (from crawl, arxiv, github) from 2023 (almost enough to chinchilla-optimally pretrain the model!)
- Model & Evaluations: https://hf.co/crumb/gpt2023

### DistilPythia (wip)
- Knowledge distillation in Pythia models
- Model card (which is also the project page) https://hf.co/crumb/distilpythia

### GerbilLab (wip)
- Parody of advertising models being chinchilla-optimal but then I actually started to care
- New UL2 inspired pretraining technique
- Small GPT models trained from scratch
- Small Instruct-Pythia model finetunes
- Project page: https://hf.co/GerbilLab

### Quick Inversions for Stable Diffusion

- novel method for estimating single-token representations (text-inversions) of images quickly
- https://twitter.com/aicrumb/status/1588769725286600704?s=20&t=DW43TNWTqs-lYp63H3CqGg

### Adversarial Attacks towards AI-Art-Adjacent tools

- Investigated the effectiveness of certain adversarial attacks on AI tools
- https://twitter.com/aicrumb/status/1580440734192148481 (explainer thread)
- https://colab.research.google.com/github/aicrumb/notebook-hosting/blob/main/Adversarial_Attacks_to_AI_Art_Tools.ipynb (messy code)

### One-Person RLHF (+PPO with aesthetic models)

- Tuned a prompt-generating BLOOM model for aesthetic Stable Diffusion results
- One of the first open source rlhf'd language models I guess (possibly the first one on huggingface)? Sucks that that achievement is on a stable diffusion prompt generator but whatever.
- https://twitter.com/aicrumb/status/1598248104981319681

### Doohickey

- Early CLIP Guided Text2img notebook built on top of Stable Diffusion
- https://hf.co/doohickey

<p align="left"> <img src="https://komarev.com/ghpvc/?username=aicrumb&label=Profile%20views&color=0e75b6&style=flat" alt="aicrumb" /> </p>
