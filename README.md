HuggingFace - https://huggingface.co/crumb

*way more coming soon*

# Things I've Done

### AskMistral-Pile
- equal to slightly higher quality subset of the pile than MiniPile, per token, needs to be reproduced at larger scale
- compare [https://huggingface.co/crumb/askmistral-2-15-111m](https://huggingface.co/crumb/askmistral-2-15-tophalf-111m) - [https://huggingface.co/crumb/minipile-111m](https://huggingface.co/crumb/minipile-111m)
- https://huggingface.co/datasets/crumb/askmistral-pile-2-15

### Reweighting
- Creating very small continued-pretraining datasets specifically to increase the size of the domain that a model performs well in
- https://crumbly.medium.com/reweighting-refining-ai-with-precision-and-efficiency-9a01c2ca4c26
  
![image](https://github.com/aicrumb/aicrumb/assets/58605641/c3cd1a2f-6840-4f26-9a65-a99e3608fad1)

### MoLora
- Mixture-of-experts LoRA, the first of it's kind on the Llama-2 models! (and looks like one of the first few finetunes!)
- medium blog post with proof of concept and inference code: https://crumbly.medium.com/llama-2-molora-f5f909434711

### DistilPythia (wip)
- Knowledge distillation in Pythia models
- Model card (which is also the project page) https://hf.co/crumb/distilpythia

### Quick Inversions for Stable Diffusion

- novel method for estimating single-token representations (text-inversions) of images quickly
- https://twitter.com/aicrumb/status/1588769725286600704?s=20&t=DW43TNWTqs-lYp63H3CqGg

### Doohickey

- Early CLIP Guided Text2img notebook built on top of Stable Diffusion
- https://hf.co/doohickey
