# Interactive OSI Model Simulator 🌐

---

## Overview

This is an **interactive, emoji-based simulator** of the **OSI model**, designed to help users **visualize how data travels** from one computer to another.

It covers:

* 🏗️ **OSI Layers** (Application → Physical)
* 📦 **Data Encapsulation** (headers added)
* 🔓 **Data De-Encapsulation** (headers removed)
* 🔀 **TCP vs UDP**
* ⚡ **Transmission across network**
* 🏎️ **Adjustable speed** for simulation

Everything is **animated** and **uses only emojis** for visual clarity.

---

## Live Demo

Experience it online: [Interactive OSI Model Simulator](https://giriaryan694-a11y.github.io/Interactive-OSI-Model-Simulator/)

💻 Sender: `49.20.60.12`
💻 Receiver: `49.20.60.20`

1. Type a message in the input box.
2. Choose **TCP** or **UDP** protocol.
3. Adjust the **speed slider** to control animation speed.
4. Press **Send ▶️** to watch encapsulation, transmission, and de-encapsulation.
5. Press **Reset ⟲** to start over.

During simulation:

* The **packet moves** from sender → receiver.
* **Headers are added** layer by layer (encapsulation).
* **Headers are removed** at receiver (de-encapsulation).
* Right panel shows **live stack** of headers.
* Payload is **only visible during send** for clean UI.

---

## Features ✨

* Clean, modern **dark UI**
* Layer highlights during simulation
* Dynamic **header stack visualization**
* TCP vs UDP emoji distinction
* Fully **emoji-based and educational**
* Responsive design for desktop & mobile

---

## How It Works

1. **Application Layer 🌐**: User message
2. **Presentation Layer 🎨**: Data formatting/encoding
3. **Session Layer 🔗**: Session management
4. **Transport Layer 📦**: Adds TCP/UDP headers
5. **Network Layer 🛣️**: Adds IP header (src/dst)
6. **Data Link Layer 💽**: Adds MAC frame
7. **Physical Layer 🔌**: Converts to bits (0️⃣1️⃣)

**Transmission →** packet moves across network.
**De-Encapsulation ↑** receiver removes headers in reverse order.

---

## Contributing

Contributions are welcome!

* Add more **emoji representations** for headers
* Add **quiz questions** for learning reinforcement
* Add **additional protocols** (ICMP, HTTP visualization)

---

## License

MIT License — free to use for learning & educational purposes.

---

**Made by Aryan Giri 💻**
Interactive OSI Model Simulator 🌐
