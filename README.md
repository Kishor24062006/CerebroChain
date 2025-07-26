# 🧠 **CEREBROCHAIN – AI Chatbot on ICP**  

![ICP](https://img.shields.io/badge/Internet%20Computer-%23E91E63.svg?&style=for-the-badge&logo=internet-computer&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?&style=for-the-badge&logo=rust&logoColor=white)
![React](https://img.shields.io/badge/React-%2361DAFB.svg?&style=for-the-badge&logo=react&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Ollama](https://img.shields.io/badge/LLM-Ollama-00b300?style=for-the-badge&logo=OpenAI)

---

## **📌 Table of Contents**
- [About CerebroChain](#-about-cerebrochain)
- [✨ Features](#-features)
- [🚀 Quick Deployment (ICP Ninja)](#-quick-deployment-icp-ninja)
- [🗂 Project Structure](#-project-structure)
- [📊 System Architecture](#-system-architecture)
- [ASCII Block Diagram](#-ascii-block-diagram)
- [Cyberpunk Effect Diagram](#-cyberpunk-effect-diagram)
- [📝 Conclusion](#-conclusion)

---

## **🔹 About CerebroChain**
**CerebroChain** is a next-generation **AI chatbot** powered by **Large Language Models (LLMs)**, running on **Internet Computer Protocol (ICP)** smart contracts for decentralized, secure, and fast AI conversations.

**Tech Stack:**  
**Backend:** Rust (ICP Canister)  
**Frontend:** React + TailwindCSS  
**LLM Engine:** Ollama (LLaMA 3.1)

---

## **✨ Features**
- **🤖 AI Conversations:** Uses **LLM** for natural, human-like replies.  
- **⚡ Deployed on ICP:** Secure, decentralized smart contracts.  
- **🛠 Local Development:** Compatible with **Ollama** for local testing.  
- **🌐 Modern Web UI:** Built with **React** and optimized for performance.  

---

## **🚀 Quick Deployment (ICP Ninja)**
1. Open **ICP Ninja**.
2. Click **“Deploy”** (top-right corner).
3. Or open directly:  
   [![Deploy CerebroChain](https://img.shields.io/badge/DEPLOY-NOW-FF1493?style=for-the-badge)](https://icp.ninja/i?url=https://github.com/dfinity/examples/rust/llm_chatbot)

---

## **🗂 Project Structure**

CerebroChain/
├── backend/
│ ├── Cargo.toml # Backend Rust canister configuration
│ └── lib.rs # Core smart contract
├── frontend/
│ ├── index.html # Main entry point
│ └── components/ # React components
├── BUILD.md # Local build instructions
└── README.md # Project documentation

---

## **📊 System Architecture**

+--------------------+
| User |
| (Sends Prompt) |
+---------+----------+
|
v
+--------------------+
| User Interface |
| (React Frontend) |
+---------+----------+
|
v
+--------------------+
| ICP Smart Contract |
| (Rust Canister) |
+---------+----------+
|
v
+--------------------+
| LLM Engine |
| (Ollama + LLaMA 3) |
+---------+----------+
|
v
+--------------------+
| Response to User |
+--------------------+


---

## **ASCII Block Diagram**
█████████████████████████████████████████████████
█ █
█ CEREBROCHAIN █
█ AI CHATBOT ON ICP SMART CONTRACT █
█ █
█████████████████████████████████████████████████



    ┌───────────────────────┐
    │        USER           │
    │   (Prompt Input)      │
    └───────────┬───────────┘
                │
                ▼
    ┌───────────────────────┐
    │   REACT FRONTEND      │
    │  (User Interface)     │
    └───────────┬───────────┘
                │
                ▼
    ┌───────────────────────┐
    │ ICP SMART CONTRACT    │
    │   (Rust Canister)     │
    └───────────┬───────────┘
                │
                ▼
    ┌───────────────────────┐
    │   LLM ENGINE          │
    │ (Ollama + LLaMA 3.1)  │
    └───────────┬───────────┘
                │
                ▼
    ┌───────────────────────┐
    │    RESPONSE TO USER   │
    │  (AI Generated Text)  │
    └───────────────────────┘



---

## **Cyberpunk Effect Diagram**

╔══════════════════════════════════════╗
║ CEREBROCHAIN SYSTEM ║
╚══════════════════════════════════════╝

[ USER ] ───► [ FRONTEND (React UI) ]
│
▼
[ ICP SMART CONTRACT ]
│
▼
[ LLM ENGINE ]
(Ollama + LLaMA 3.1)
│
▼
[ RESPONSE ]


---

## **📝 Conclusion**
**CerebroChain** merges the power of **LLMs** with **ICP smart contracts** to deliver **secure, decentralized AI interactions.**  

- **Modular Design:** React-based frontend, Rust backend, and LLM engine.  
- **Decentralization:** Trustless and tamper-proof architecture via ICP.  
- **Scalability:** Powered by **Ollama + LLaMA 3.1** for low-latency local responses.  
- **Modern UI/UX:** Built using **React, Rust, TailwindCSS.**

---

