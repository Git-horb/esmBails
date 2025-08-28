# esmBails – WhatsApp Baileys  
`MODIFIED BY DavidX`

<p align="center">
  <img src="https://cnd.davex.site/1756390329706-upload_1756390326785.jpg" alt="Thumbnail" width="500"/>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/esm-bails">
    <img src="https://img.shields.io/npm/v/esm-bails?color=brightgreen&label=npm" alt="npm version" />
  </a>
  <a href="https://www.npmjs.com/package/esm-bails">
    <img src="https://img.shields.io/npm/dt/esm-bails?color=blue&label=downloads" alt="npm downloads" />
  </a>
  <a href="https://github.com/DavidX/esm-bails/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/DavidX/esm-bails?color=yellow" alt="license" />
  </a>
  <a href="https://github.com/DavidX/esm-bails">
    <img src="https://img.shields.io/github/stars/DavidX/esm-bails?style=social" alt="GitHub stars" />
  </a>
</p>

**esmBails** is a modern, lightweight, and actively maintained fork of the popular [Baileys](https://github.com/adiwajshing/Baileys) WhatsApp library.  
It provides developers with a **browser-free WebSocket connection** to WhatsApp, enabling you to build bots, automation systems, and integrations with **high stability and full feature support**.

---

## ✨ Features

- ✅ Stable and **custom pairing** (fixes past disconnection issues)  
- ✅ **Interactive messages**: buttons, lists, menus, and dynamic replies  
- ✅ **Automatic session management** (lightweight & reliable)  
- ✅ Fully compatible with **WhatsApp Multi-Device**  
- ✅ **Secure authentication** with customizable codes  
- ✅ Well-structured and modular for easy integration  
- ✅ Ideal for **business bots, automation, and customer service**  

---

## 🚀 Installation

npm install esm-bails
# or
yarn add esm-bails

---

⚡ Quick Start

import makeWASocket from "esm-bails"

async function startBot() {
  const sock = makeWASocket({
    printQRInTerminal: true
  })

  sock.ev.on("messages.upsert", m => {
    console.log("New message:", m)
  })
}

startBot()




📚 Why Choose esmBails?

Built on latest Baileys core with stability improvements

Enhanced pairing & authentication system

Continuously updated for compatibility with WhatsApp updates

Lightweight, fast, and secure → perfect for production bots



---

🔧 Technical Notes

Stable custom pairing codes

Automatic reconnection & efficient session handling

Full support for interactive templates (buttons, lists, etc.)

Works seamlessly with the latest WhatsApp MD architecture

Easy to extend & customize for your own workflows



---

📖 Documentation & Support

Baileys Original Docs

Community discussions and examples (coming soon)

Contributions are welcome via PRs



---

💡 About

This is a modified & improved fork of WhatsApp Baileys, tailored for developers who want reliability + modern features out of the box.


---

🏆 Credit

Baileys by @adiwajshing

Modified and maintained by DavidX
