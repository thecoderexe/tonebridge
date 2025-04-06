![Tonebridge Banner](https://github.com/thecoderexe/tonebridge/blob/main/assets/tonebridge-banner.png?raw=true)

<p align='center'>
Try tonebridge at <a href="https://tonebridge.vercel.app">tonebridge.vercel.app</a>
</p>

## Using tonebridge

Visit [tonebridge.vercel.app](https://tonebridge.vercel.app), paste your own API keys, and start experimenting with sentence translations with fine-grained formality control.

### ✨ Features:
- Adjust the **formality level** of any sentence (e.g., casual ↔️ formal)
- Bring your own [Google Gemini API Key](https://aistudio.google.com/app/prompts)
- Optional [ElevenLabs API Key](https://www.elevenlabs.io/) for ultra-realistic voice playback
- Fallback to **native browser TTS** if ElevenLabs is not used
- Light/dark themes for a clean dev experience

> ⚠️ This project is an experimental tool for developers and tinkerers. It is **non-commercial** and **closed-source**.

---

## Techstack

[![Techstack](https://skillicons.dev/icons?i=html,js,vercel,react,nextjs,figma,ai)](https://skillicons.dev)

Tonebridge is built as a lightweight web utility using powerful APIs:

- [Google Gemini via AI Studio](https://aistudio.google.com/)
  - Fast, intelligent formality-aware language processing
- [ElevenLabs TTS](https://www.elevenlabs.io/)
  - Realistic voice generation for translated output
- [Web Speech API (TTS)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
  - Browser-native text-to-speech fallback
- Hosted on [Vercel](https://vercel.com)
  - Fast, global CDN delivery and serverless API support
- Icons sourced and exported from [Figma](https://www.figma.com/community/icons)
  - Lightweight SVGs designed for UI clarity and consistency

---

## 📖 Philosophy

**tonebridge** was built with the idea that translation shouldn't be one-size-fits-all.  

The goal is to provide:
- ✍️ **Customizable, context-aware translation** with adjustable tone and formality
- 🔊 **Optional voice playback** using ElevenLabs or native speech synthesis
- 🎨 A clean, modern UI with support for multiple themes

It’s designed to help developers prototype better multilingual interactions in their own tools or apps—without the complexity.

---

## 🗝️ Setup & API Keys

You must bring your own API keys to use tonebridge:

1. **Google Gemini API Key**  
   - Get it from [Google AI Studio](https://aistudio.google.com/app/prompts)
2. *(Optional)* **ElevenLabs API Key**  
   - Sign up at [ElevenLabs](https://www.elevenlabs.io/) and paste the key in the app to enable audio

Paste both directly into the web app. No keys are stored or sent to any backend—**everything runs in-browser**.

---

## ⚖️ Legal

tonebridge is an independent developer tool and **is not affiliated with any other product or company using the name "Tonebridge."**  
It is a closed-source, non-commercial project in the field of AI-assisted translation.

---
