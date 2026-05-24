# AI Music Generator – Sound Composer

Generate original, royalty‑free music from any text description using Meta’s **MusicGen** model.  
Supports English, Hindi, Hinglish, and any other language prompt.
## Live Demo

https://github.com/user-attachments/assets/6ac344e7-2b2e-4a80-a9b5-ecda4b584ce0


![Gradio UI](https://img.shields.io/badge/UI-Gradio-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Python](https://img.shields.io/badge/Python-3.10+-yellow) ![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red)

## eatures

- **Text-to-Music**: Generate original audio from natural language prompts in English, Hindi, Hinglish, or any language.
- **Fine Control**: Adjust duration (3–20 sec), creativity (temperature), and prompt adherence (guidance scale).
- **Reproducibility**: Set a random seed for consistent results.
- **Optimized for T4 GPU**: Uses `musicgen-small` with half-precision for efficient inference on free Hugging Face T4 GPUs.
- **Multilingual Support**: Understands prompts in any language (model works best with English, but non-English works too).
- **Instant Playback**: Generated audio can be previewed and downloaded directly in the browser.

## Tech Stack

- **Model**: [facebook/musicgen-small](https://huggingface.co/facebook/musicgen-small) (1.5B params)
- **Framework**: PyTorch 2.0+, Hugging Face Transformers & Diffusers
- **Interface**: Gradio 4+
- **Audio Processing**: SciPy, NumPy
- **Hardware**: GPU (T4 recommended) or CPU fallback

## Installation

### Local Setup (CPU or GPU)

1. **Clone the repository**
   ```bash
   git clone https://github.com/ramkishor6003/Music Generator.git
   cd Music Generator


