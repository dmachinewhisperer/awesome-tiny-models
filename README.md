# Awesome Tiny Models

A curated list of recent small models, organized by what they do. "Small" means models that run comfortably on a laptop, phone, or edge device.

Each entry gives the model name, parameter count, a one-line note, and links to the weights and, where available, the paper or code.

## Contents

- [Text-to-Speech (TTS)](#text-to-speech-tts)
- [Speech-to-Text (STT)](#speech-to-text-stt)
- [OCR and Document Understanding](#ocr-and-document-understanding)
- [Language Models (LLM)](#language-models-llm)
- [Vision-Language Models (VLM)](#vision-language-models-vlm)
- [Embeddings and Rerankers](#embeddings-and-rerankers)
- [Image Generation](#image-generation)
- [Object Detection and Segmentation](#object-detection-and-segmentation)
- [Contributing](#contributing)

## Text-to-Speech (TTS)

| Model | Params | Notes | Links |
|-------|--------|-------|-------|
| Leokani-tts 4.5M | 4.3M | Smaller sibling of Leokani-tts 7M with the same English voice. ONNX (fp32, fp16, int8), 24 kHz. CC BY-NC 4.0. | [Hugging Face](https://huggingface.co/milliwattlabs/leokani-tts-4.5M) · [Milliwatt Labs](https://milliwattlabs.com/models/leokani-tts/) |
| Leokani-tts 7M | 7.0M | Single American English voice for CPU and microcontrollers, with a companion G2P phonemizer. CC BY-NC 4.0. | [Hugging Face](https://huggingface.co/milliwattlabs/leokani-tts-7M) · [G2P](https://huggingface.co/milliwattlabs/leokani-g2p) · [Milliwatt Labs](https://milliwattlabs.com/models/leokani-tts/) |
| Paradee-8M | 8.1M | Kokoro-82M distilled into one English voice. 8.5 MB in int8, about 25x real time on one CPU thread. Apache 2.0. | [Hugging Face](https://huggingface.co/sahilmahendrakar/Paradee-8M-v1.2) · [GitHub](https://github.com/sahilmahendrakar/paradee) · [Paper](https://arxiv.org/abs/2610.06817) |
| phonon-31m-en | 31M | English streaming TTS from Gradium, built on Pocket TTS and the Mimi codec. Runs in a browser tab or on a laptop CPU. Apache 2.0. | [Hugging Face](https://huggingface.co/gradium/phonon-31m-en) · [Blog](https://gradium.ai/blog/phonon-closer-look) |
| PiVo-1.4M | 1.4M | Full English stack with two voices: a 585K acoustic model plus an 817K FARGAN-derived vocoder, 16 kHz. Research model. | [Hugging Face](https://huggingface.co/empero-ai/PiVo-1.4M) |
| sanoTTS | 294K to 2.27M | 11 voices across English, Nepali, Hindi, Vietnamese, Indonesian and Chinese. Runs on an ESP32-S3 or in the browser via WebAssembly. GPL-3.0. | [Hugging Face](https://huggingface.co/ampixa/sanoTTS) · [Project page](https://ampixa.com/sanotts/) |
| Supertonic 3 | 99M | On-device TTS for 31 languages, runs on ONNX Runtime. OpenRAIL-M. | [Hugging Face](https://huggingface.co/Supertone/supertonic-3) |
| Woof | 30.7M / 38.2M | Underdog's TTS in one-voice (31.7 MB) and two-voice (40.6 MB) versions. The one-voice model runs in the browser. CC BY-NC 4.0. | [Hugging Face](https://huggingface.co/ConwayResearch/Underdog-Woof) · [Project page](https://underdog.ai/woof) |

## Speech-to-Text (STT)

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## OCR and Document Understanding

| Model | Params | Notes | Links |
|-------|--------|-------|-------|
| Bina 0.4 Rizeh | 71M | Persian page OCR pipeline (layout, line detection, recognition) for printed and handwritten text. CC BY-NC 4.0; detector weights follow Surya's license. | [Hugging Face](https://huggingface.co/Reza2kn/Bina-0.4-Rizeh) |

## Language Models (LLM)

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## Vision-Language Models (VLM)

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## Embeddings and Rerankers

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## Image Generation

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## Object Detection and Segmentation

| Model | Params | Notes | Links |
|-------|--------|-------|-------|

## Contributing

Open a pull request adding a row to the matching table. Keep rows alphabetical within a section and link to the official model page.
