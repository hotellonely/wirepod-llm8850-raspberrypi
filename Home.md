# wirepod-llm8850-raspberrypi Wiki

Welcome to the **wirepod-llm8850-raspberrypi** project wiki! This project documents how to set up a fully local, on-device large language model (LLM) for your **Anki Vector** robot using the **LLM8850** AI accelerator module on a **Raspberry Pi** running **WirePod**.

---

## What Is This Project?

Anki Vector is a small home robot that originally relied on cloud services (Anki/Digital Dream Labs) for its AI responses. [WirePod](https://github.com/kercre123/wire-pod) is an open-source server replacement that lets Vector work without those cloud services.

This project extends WirePod by integrating the **LLM8850** — an affordable AI inference module — connected to a **Raspberry Pi**, so Vector can answer questions and hold conversations entirely offline using a locally-running LLM.

---

## Getting Started

Follow these guides in order for a complete setup:

1. **[Prerequisites](Prerequisites)** — Hardware and software requirements before you begin
2. **[Hardware Setup](Hardware-Setup)** — Connecting the LLM8850 module to your Raspberry Pi
3. **[Installing WirePod](Installing-WirePod)** — Setting up the WirePod server on Raspberry Pi
4. **[Configuring the LLM](Configuring-the-LLM)** — Loading a model onto the LLM8850 and connecting it to WirePod
5. **[Pairing Vector](Pairing-Vector)** — Pointing your Anki Vector robot to your local WirePod server
6. **[Troubleshooting](Troubleshooting)** — Common issues and how to resolve them

---

## Components at a Glance

| Component | Role |
|-----------|------|
| **Anki Vector** | The robot that delivers LLM-generated responses |
| **WirePod** | Open-source cloud-server replacement for Vector |
| **LLM8850** | AI accelerator module for efficient on-device LLM inference |
| **Raspberry Pi** | Host hardware that runs WirePod and interfaces with the LLM8850 |

---

## Why Run a Local LLM?

- **Privacy** — Conversations never leave your local network
- **Offline operation** — Vector keeps working without an internet connection
- **No subscription fees** — No dependency on paid cloud AI services
- **Customization** — Choose and tune the language model to your liking

---

## Contributing

Found an error or want to add a guide? Contributions are welcome!

- Open an **[issue](https://github.com/hotellonely/wirepod-llm8850-raspberrypi/issues)** to report problems or suggest new content
- Submit a **[pull request](https://github.com/hotellonely/wirepod-llm8850-raspberrypi/pulls)** with improvements

---

*Back to the [repository](https://github.com/hotellonely/wirepod-llm8850-raspberrypi)*
