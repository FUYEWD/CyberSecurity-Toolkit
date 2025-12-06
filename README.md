# CyberSecurity-Toolkit
A beginner-friendly cybersecurity toolkit including port scanner, AES encryption, web security demos, and security reports.
🌐 網路安全工具包（CyberSecurity Toolkit）

一個由 fuy 開發、面向初學者與研究者的網路安全工具包。
這個專案集合了 網路掃描、密碼學、Web 安全性示範與資安技術文件，目的在於：

建立我的 資安學習框架與作品集

練習 程式開發、攻防概念、報告撰寫

展示我對 資料科學 + 系統安全 + 工程實作 的跨領域整合能力

為未來從事 資料科學 / 網路安全 / AI 安全 奠定基礎

本工具包以 理解原理、可讀性與創意呈現 為核心，希望能讓剛入門資安的人，也能在友善的架構中快速掌握關鍵概念。

🚀 專案特色 Highlights
🔍 1. Quantum-Inspired Port Scanner（量子靈感埠掃描器）

一款以「量子掃描」為概念包裝的多線程 Port Scanner。
功能：

多執行緒快速掃描大量 port

類似 Nmap 基礎版

適合用來觀察網路服務的開放情況

✨ 我為什麼要做這個？
為了強化我對 socket、TCP 連線原理、ThreadPool 執行緒模型 的理解，也建立未來進階掃描器的基礎。

🔐 2. Cyber-Alchemist AES Tool（賽博煉金 AES 密碼學工具）

以「密文煉金術」為概念的加密/解密器。

使用 cryptography 套件（Fernet AES）

自動生成 key

可用於本地資料簡易保護

✨ 我為什麼要做這個？
資料科學家與工程師都會面對資料隱私議題，因此我在專案中加入 密碼學的實作基礎，也讓未來做 Token、JWT、API 驗證時更得心應手。

🕸️ 3. XSS Multiverse Guide（XSS 多重宇宙指南）

這不是普通的 XSS 文件，而是把攻擊手法拆成 不同宇宙的敘事方式：

Reflected XSS

Stored XSS

DOM-based XSS

外加防禦對策

✨ 我為什麼要做這個？
因為我相信「好故事比純理論更容易記住」。
透過創意文案方式呈現 Web 漏洞，使我的作品集更具辨識度。

📄 4. Security Report / 資安報告示範

提供一份我自己撰寫的資安分析報告，內容包括：

漏洞描述

風險分析

攻擊重現步驟

建議修補方式

✨ 我為什麼要做這個？
這是未來做 滲透測試、資安研究、CTF writeup 必備技能，也展示我在「技術寫作」與「邏輯表達」的能力。

🛠️ 專案結構
CyberSecurity-Toolkit/
│
├── scanner/
│   └── port_scanner.py
│
├── crypto/
│   └── aes_encrypt.py
│
├── web_security/
│   └── xss_demo.md
│
└── reports/
    └── sample_report.md

🎯 我的目標（為什麼做這個專案）

這個專案不只是程式碼，而是我個人成長的一部分。

✔ 建立 資安基礎 + 工程實作能力
✔ 練習 報告撰寫、知識整理、技術文檔
✔ 強化 問題拆解、工程邏輯、系統思維
✔ 結合未來的 資料科學、AI、機器人安全性
✔ 與朋友們討論（如哲學、科技、工程）時能有更深的理解

長遠來說，我希望能打造：

「一個從工程 → 資安 → AI → 系統層級思考」的完整底盤。

這個 repo 就是我的起點。
