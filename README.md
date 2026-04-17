# AI Security in SoC/NoC Systems (SoK Paper)

## About this
This was a group research project for my Security of Control and Embedded Systems module.

We worked on a Systematisation of Knowledge (SoK) paper focused on security challenges in AI-enabled System-on-Chip (SoC) and Network-on-Chip (NoC) architectures.

The goal was not just to summarise papers, but to organise existing research, identify patterns, and highlight gaps in current security approaches.

---

## What the paper covers

### Threats
We analysed different types of threats across layers:

- Hardware-level → fault injection, side-channel attacks
- Network-level → eavesdropping, traffic analysis, DoS
- AI-specific → adversarial attacks, backdoor attacks

---

### Key contribution
One of the main contributions of this paper is a **taxonomy of attacks** across:

- Hardware layer
- Network layer
- AI layer

This helped in understanding how attacks can happen across multiple layers instead of in isolation.

---

### Important insight
A key observation was that:

Most existing solutions focus only on one layer (hardware OR network OR AI),  
but real attackers use **cross-layer attacks**.

This creates a major gap in current security research.

---

### Defence mechanisms
We reviewed different types of defences:

- Hardware protections (side-channel resistance)
- Secure NoC routing and encryption
- AI-specific defences (adversarial training, anomaly detection)

---

### Case studies
We also looked at real-world systems like:

- NVIDIA Tegra SoCs
- Hardware attacks like voltage glitching

---

## What I learned
- AI integration increases hardware attack surface
- Security cannot be solved at a single layer
- Real-world systems are still vulnerable to physical attacks
- Research gaps exist in cross-layer security

---

## Files
- paper.pdf → full SoK paper

---

## Note
This was completed as part of university coursework in a group setting.

The work reflects a collaborative effort, and this repository is shared to document my learning and contribution to the project.
