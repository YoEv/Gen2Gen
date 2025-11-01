# Gen-to-Gen: Algorithm-Based Generative Video to Partial Audio Synthesis System

**Author:** Xiaosha Li  
**Advisor:** Neil Leonard  
**Conference:** ICMC 2025 (Boston, USA)

**Resources**  
- [Paper – ICMC 2025 Proceedings (PDF)](https://github.com/YoEv/Gen2Gen/blob/main/Xiaosha%20Li%20-%20ICMC%20Boston%202025%20Proceedings%20%5B7-1-25%5D.pdf)  
- [Poster – GEN to GEN (PDF)](https://github.com/YoEv/Gen2Gen/blob/main/GEN%20to%20GEN_Xiaosha%20Li_Poster.pdf)  
- [Demo – Algorithm Based Gen Video to Partial Gen Audio Synth (PDF)](https://github.com/YoEv/Gen2Gen/blob/main/Demo_Algorithm%20Based%20Gen%20Video%20to%20Partial%20Gen%20Audio%20Synth_Xiaosha%20Li.pdf)

---

## Motivation

This project explores algorithmic connections between visual generation and sound synthesis.  
Instead of treating video and audio as separate modalities, *Gen-to-Gen* transforms generative video pixels directly into multichannel audio signals, allowing visual structures to become audible forms.

The goal is to turn visual algorithms into musical instruments — bridging the gap between perception, composition, and performance.  
By using parameterized visual patterns and spatial mappings, the system creates a framework where images can “compose” and “perform” their own sound in real time.

---

## System Overview

The system implements a six-module Max/MSP architecture with two synthesis layers.

### Low-Level: Partial Audio Generation
- Converts 256×256 generative video frames into 32-channel audio.
- Each pixel column acts as a partial oscillator, producing frequency–amplitude relationships based on brightness and motion.
- Video parameters such as contrast, zoom, and brightness dynamically shape timbre and rhythm.

### High-Level: Spatial Audio Mapping
- Five playback videos are decomposed into RGB channels, each mapped to a 32-channel amplifier.
- RGB values control amplitude and modulation, forming spatialized textures and evolving harmonic fields.
- Supports 15 predefined sound shapes, which can be user-defined.

### Interaction
- Dual control system: MIDI keyboard (continuous modulation) and computer keyboard (discrete toggling).
- Real-time control of brightness, speed, modulation, and geometry.
- Designed for live audiovisual performance and improvisation.

---

## Artistic Essence

*Gen-to-Gen* reimagines audiovisual creation as a mutual transformation process,  
where visual rhythm, shape, and contrast become the compositional grammar of sound.  
It embodies a philosophy of data unity across modalities, transforming algorithms into expressive materials.

---

## Future Directions
- Machine learning–based mapping for adaptive video-to-audio correspondence.  
- Expanded gesture and spatial control for immersive live performance.  
- Integration into multimodal AI systems for creative expression.
