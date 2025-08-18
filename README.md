# 🎧 AudioAtlas: A Comprehensive and Balanced Benchmark Towards Movie-Oriented Text-to-Auido Generation

AudioAtlas, a comprehensive and balanced benchmark for movie-oriented text-to-audio generation. AudioAtlas contains 1,165 high-quality and diverse recordings, comprising 276 categories across 16 themes. Built upon a well-structured audio category system-SoundTrace, AudioAtlas provides a more category-balanced and comprehensive benchmark compared to the widely used AudioCaps test set. Furthermore, we provide detailed human annotations covering both temporal and semantic dimensions.

---

## 🌟 Highlights

- 🧩 **Rich Diversity**: Based on our proposed SoundTrace, an object-centric audio taxonomy, AudioAtlas comprises 276 sound effect categories grouped into 16 themes.
- ⚖️ **Balanced Category Distribution**: AudioAtlas provides a more category-balanced and comprehensive benchmark compared to the widely used AudioCaps test set.
- ⏱️ **Fine-Grained Temporal Annotation**: AudioAtlas offers fine-grained temporal annotations with a resolution of 0.1 seconds, precisely indicating the onset of each audio event.
- 🧑‍🔬 **Detail-Oriented Annotation**: AudioAtlas provides human-annotated overall and event-level captions with rich descriptors (e.g., material, quantity, volume and emotion).
- 🎧 **High-Quality Audio**: AudioAtlas offers high-quality reference audio recorded with professional-grade equipment at high sampling rates (above 44 kHz), ensuring superior fidelity and acoustic precision.
- 🛠️ **Higher-quality evaluation**: AudioAtlas facilitates comprehensive evaluation of both temporal coherence and semantic alignment. Compared to previous benchmarks, it provides clearer optimization guidance through its high-quality reference samples, aiming to mitigate the adverse effects of overfitting on low-quality, open-world recordings.

---

## 📁 Repository Structure

├── audios/ # Contains sample audios

├── images/ # Figures and icons

├── metas/ # All annotations and SoundTrace jsonl

├── LICENSE # License info

├── README.md # This file

└── index.html # Interactive demo

## 🔍 Preview

Further details are available on the project page: https://audioatlas.github.io/AudioAtlas/

## 📄 License


# License for Annotations (metas/)
All annotations and metadata files in the `metas/` directory are licensed under
the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).
See https://creativecommons.org/licenses/by-nc-sa/4.0/ for details.

# Audio Files
The `audios/` directory contains only sample files for demonstration.
Full audio files are NOT distributed in this repository. The complete dataset must be downloaded from https://artlist.io/sfx or https://www.audiostock.io, subject to their original license. 
