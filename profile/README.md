# Cobalt Pear

**Prompt in, picture out — on your own RunPod.**

A one-page app for RunPod Serverless. Pick a model, paste your endpoint ID, and just type.

- Just type — no GPU, no ComfyUI, no install.
- Your own RunPod: your own GPU, your own rules — you pay only for the pictures you make.
- Your key and pictures stay in your browser.

**[Open the app](https://cobaltpear.github.io/)** · [Setup guide](https://cobaltpear.github.io/guide.html) · [Discussions](https://github.com/cobaltpear/cobaltpear.github.io/discussions)

## Repositories

| Repo | What it is |
|---|---|
| [cobaltpear.github.io](https://github.com/cobaltpear/cobaltpear.github.io) | The app itself — one page, runs in your browser |
| [docs](https://github.com/cobaltpear/docs) | The manual — [cobaltpear.github.io/docs](https://cobaltpear.github.io/docs/) |
| [civitai-sdxl](https://github.com/cobaltpear/civitai-sdxl) | Worker template: any SDXL, Pony, Illustrious or NoobAI checkpoint from Civitai or Hugging Face |
| [civitai-flux](https://github.com/cobaltpear/civitai-flux) | Worker template: any FLUX.1 model (dev, schnell, Krea) from Civitai or Hugging Face |
| [civitai-chroma](https://github.com/cobaltpear/civitai-chroma) | Worker template: any Chroma model from Civitai |
| [civitai-zimage](https://github.com/cobaltpear/civitai-zimage) | Worker template: any Z-Image (Turbo, Base) model from Civitai or Hugging Face |
| [civitai-sd15](https://github.com/cobaltpear/civitai-sd15) | Worker template: any SD 1.5 checkpoint from Civitai |
| [relay](https://github.com/cobaltpear/relay) | The small Cloudflare Worker behind the app's «Make it» button |

The worker templates are RunPod Serverless ComfyUI workers: **Use this template** → paste a model link → connect your copy on RunPod. The app sets them up for you from a model link.
