# 🏡 AbodeLLM

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/tricenc)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029ValNwp4I7BeEzI67Xp0i)

</div>

AbodeLLM is an offline AI assistant built for Android devices, powered by various compact language models. It runs entirely on your device, ensuring privacy by processing everything locally. No internet connection is required for chat operations.

## Features

- **Offline AI Processing**: Chat without internet access.
- **Privacy First**: All prompts and conversations are processed on-device.
- **Multimodal Input**: Vision and audio input on supported models.
- **Expert Mode**: Advanced settings with adjustable temperature, top-k/top-p, kv-cache and token limits.
- **Multiple Model Families**: Choose from various model architectures, each with size variants.
- **Optimized for Mobile**: Designed to work efficiently on Android devices.

## Screenshots

<div align="center">
<img src="screenshots/main.png" alt="Screenshots"  width="950"/>
</div>

## Version Info

- **Current Version**: `3.1.0`
- **Models Available (for download)**

| Family | Capabilities |
|--------|--------------|
| **LLaMA 3.2** | Text-only |
| **SmolLM2 / SmolLM3** | Text-only |
| **SmolVLM2** | Vision + text |
| **DeepSeek R1 Distill** | Text-only (reasoning) |
| **Gemma 3 / Gemma 4** | Text + Audio + Vision (Gemma 4) |
| **Qwen3 / Qwen3.5** | Qwen3.5 includes Vision |
| **Ministral 3** | Vision + text |
| **LFM2.5 / LFM2.5-VL** | Text (LFM2.5, includes "Thinking" variant) + Vision (LFM2.5-VL) |
| **Ultravox** | Audio + text |
| **Granite 3.3 / Granite 4.0** | Vision (Granite 3.3) + Text (Granite 4.0) |

> Each family may offer multiple size variants (e.g., 1B, 3B). The app shows available downloads when you select a family.

## Requirements

| Component | Specification |
|-----------|--------------|
| Android   | 9 or higher |
| RAM       | 3GB minimum (6GB+ recommended) |
| Storage   | 1GB+ free space |

## Installation

### 1. Download the APK
   > Download the APK from [Releases](https://github.com/brendmung/abodellm/releases)

### 2. Install the APK
   > After downloading, install the APK file on your Android device.

### 3. Model Download
   > Go to the **Models** tab and select a model family to download. Models with a `+ Vision` or `+ Audio` badge support optional projector download for multimodal input — tap the badge when ready.

### 4. Start Chatting
   > Once the model is downloaded, start a new chat!

## Expert Mode

Expert Mode provides advanced users with fine-grained control over model behavior:

- **Temperature**: Control randomness in responses (0.0-1.0)
- **Top-K Sampling**: Limit vocabulary selection to top K tokens
- **Top-P Sampling**: Nucleus sampling for more coherent outputs
- **KV-Cache Management**: Context window size — 512 to 32768 tokens
- **Token Limits**: Maximum response length — 512 to 16384 tokens
- **Model Info**: View model architecture, layers, context length, quantization, and license
- **Import Model**: Load any external model (GGUF format supported), with optional projector for vision or audio input

<details>
<summary>How to Unlock Expert Mode</summary>
<br>

**To Enable Expert Mode:**
1. Open the app and navigate to **Settings** (via the inference page menu)
2. **Hold** the "Settings" title for 5 seconds until a confirmation dialog appears
3. The advanced controls will now be visible in your settings

**To Hide Expert Mode:**
- Simply **hold** the "Settings" title again for 5 seconds

</details>

## Important Notes

- Uncensored and abliterated model variants have fewer content restrictions — use responsibly
- KV cache changes apply on the next model load
- Performance depends on device capabilities

## Stay Updated

Join our channels for updates and discussions:
- [Telegram Channel](https://t.me/tricenc)
- [WhatsApp Channel](https://whatsapp.com/channel/0029ValNwp4I7BeEzI67Xp0i)

---

<div align="center">
Simply Abode 🏡
</div>
