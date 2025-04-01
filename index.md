# Introduction

**1st year Electrical Engineering @ Georgia Tech**  
**Threads**: Circuit Technology & Signal Processing/AI  
**Career Interests**: Entrepreneurial audio hardware development  
**Activities**:
- Co-lead of AI interpretability research team  
- Digital design sub-team member, Silicon Jackets (chip design club)  

---

# About Me

I've always been drawn to the meeting point of technology and creativity. At Georgia Tech, I'm exploring electrical engineering with focuses in circuit technology and signal processing/AI – areas that complement my interest in audio technology.

My work with Silicon Jackets has introduced me to the detailed world of chip design, revealing complexities and possibilities I hadn't considered before. In parallel, co-leading research on neural network polysemanticity has given me a glimpse into how AI systems process information – concepts that could have interesting applications in audio technology.

I find myself most engaged when exploring connections between these technical fields and my passion for music production. Understanding both the engineering principles and creative needs gives me a perspective I hope to develop further throughout my education.

As a first-year student, I recognize I have much to learn, but I'm building a foundation of skills in RTL design, AI, and circuit design while maintaining my connection to audio and music production.

I'm excited about the potential paths ahead—whether in specialized audio hardware, chip design, or somewhere at their intersection—and I am focused on developing the skills that will help me contribute meaningfully to these fields.

---

# Career Goals

At this point, I am not entirely certain of my specific career path. I am currently an electrical engineering major, and my threads/coursework is oriented with the goal of audio hardware development/music technology in mind. However, through Silicon Jackets I have discovered an additional passion for chip design. I am considering a switch to computer engineering, reorienting my career path to the chip design route, but for now I am sticking with EE.

I am also considering finding the niche merging these paths; for instance, working with FPGAs for audio processing purposes.

Yet regardless of my route, my overarching destination is **entrepreneurship**. My plan for my first year was to build up my technical skills, which I have done through:
- Silicon Jackets
- AI interpretability research
- Passion projects
- A summer research position at San José State University

In my coming years at GT, I plan on applying those skills by joining **Create-X** and/or **Startup Exchange**, two startup accelerators here at Tech.

---

# Project Showcase

## Neuron Research

As part of Georgia Tech's **Math Modeling Student Research Group**, I have worked with fellow students to explore and quantify *polysemanticity* in neural networks.

Polysemanticity is a phenomenon where a neuron is activated by more than one feature (e.g., curves *and* straight lines). Using the structural similarity index measure (SSIM), we analyze diversified feature visualizations for a neuron to quantify polysemanticity.

We initially used a shrunken version of **LeNet-5** on the **MNIST** dataset but switched to **CIFAR-10** due to MNIST’s limitations in image detail. This transition helped us identify more nuanced traits that activated neurons (e.g., color or shape direction).

Some key takeaways:
- CIFAR-10 allowed clearer feature visualizations (e.g., blue backgrounds, diagonal shapes)
- Polysemanticity is not always reflected by class diversity in activations
- Accuracy dropped from ~100% to ~68% with CIFAR, but that didn’t impact our polysemanticity testing

We're currently drafting a workshop paper and plan to submit to AI/ML conferences in the coming months.

---

## MIDI Moog

**MIDI Moog** is a custom MIDI controller replicating the **Minimoog** synthesizer’s layout. When paired with Minimoog emulation software (e.g., Arturia’s Mini V3), it provides a hardware-like experience at a fraction of the cost.

The controller is powered by:
- **Teensy 4.1** microcontroller  
- **I2C analog I/O expansion ICs**  
- **SPI digital I/O expansion ICs**  

Initially, I tried using an Arduino Nano, but due to USB MIDI limitations and latency with multiplexers, I switched to the Teensy. It offered cleaner USB MIDI integration and more direct I/O for latency-free control.

This project was born out of frustration with virtual synth interfaces and a desire for real-time, tactile sound design.

---

## Nextro

**Nextro** is a prototype that converts **text prompts into synth presets**.

My goal was to automate sound design using LLMs. Instead of generating audio directly (which requires advanced ML techniques), I created a system that translates text descriptions into **JSON-formatted preset files** for a synthesizer plugin.

Tech Stack:
- Python for prompt-to-JSON conversion  
- C++ audio plugin integration  
- Open-source synthesizer as the base  

Challenges included:
- Learning C++ from scratch for plugin integration  
- Selecting an LLM (initially GPT-3.5 for cost; future plans include GPT-4o-mini or Claude)  
- Curating text/preset pairs for fine-tuning (future work)

While the generated sounds aren’t yet production-ready, the concept is scalable and adaptable to higher-quality synths and LLMs.

---

Want to chat about synths, circuits, or startups?  
Let’s connect!
