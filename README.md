# Easy Finetuning Stable Diffusion
Let's easily fine-tuning pre-trained Stable Diffusion using dataset-maker and [LoRA](https://github.com/cloneofsimo/lora)!

## dataset-maker Instructions
`dataset-maker` is an example for custom data collection to finetune Stable Diffusion. It consists of web crawler and BLIP image captioning module.

1. Inspect your desired website and slightly modify `webCrawler.py`.

2. Run `webCrawler.py`.