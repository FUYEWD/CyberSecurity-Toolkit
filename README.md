🛡️ CyberSecurity Toolkit — v2 (Remand Edition)

一個 輕量、創意、教育向 的資安工具箱。
主打模組化、易讀、用途清楚，適合作為：

✔ GitHub 作品集

✔ 面試展示

✔ 資安課程、專題

✔ 個人學習工具

✨ 特色 (Highlights)

模組化設計：每個資料夾都是獨立工具，可單獨使用

極度輕量：無外部依賴，好跑、不佔資源

帶有創意：例如「迷因加密」、「釣魚信情緒誘導分數」

安全無害：即便是 malware-sim 也只是模擬，不會破壞系統

可當教材：每支程式都附「程式內註解」與「教學邏輯」

🗂️ 專案架構 (Overview)
CyberSecurity-Toolkit-v2/
│── encryption/                # 加密工具
│   ├── aes_encryptor.py
│   ├── meme_cipher.py
│   └── rot13_fun.py
│
│── pentest-utils/             # 滲透測試常用小工具
│   ├── header_info.py
│   └── common_password_scanner.py
│
│── phishing-sim/              # 釣魚郵件模擬器
│   ├── generator.py
│   └── templates/
│       ├── urgent_payment.txt
│       ├── fake_github_alert.txt
│       └── internal_update.txt
│
│── malware-sim/               # 假惡意程式行為模擬 (安全版)
│   └── harmless_ransomware.py
│
│── ai-log-analyzer/           # AI 模擬規則式 Log 分析器
│   └── rule_based_ai.py
│
└── README.md

🔐 1. Encryption Tools
✔ AES Encryptor

基本示範對稱式加密。

✔ Meme Cipher

創意功能：把每個字元轉成「迷因風格代碼」。

✔ Fun ROT13

ROT13 + 彩色輸出 + 小彩蛋。

🛠️ 2. Pentest Utilities
✔ Header Info

快速查看目標網站 HTTP 標頭。

✔ Weak Password Scanner

內建常見弱密碼字典，可自行擴充。

🎣 3. Phishing Email Simulator

自動產生：

騙財款通知

假 GitHub 安全警告

內部更新通知

並加入 情緒誘導評分機制（0～100）。

🧪 4. Malware Simulation (Safe)

模擬「看起來像勒索軟體」但不會傷害系統：

記錄檔案名稱

產生假加密檔案

產生 ransom_note.txt

純教育用。

🔍 5. AI Log Analyzer

無需機器學習模型，使用：

Pattern Matching

基本統計異常偵測

可分析：

多次錯誤登入

API 速率異常

異常 IP 活動

🚀 如何使用 (Example)
python encryption/aes_encryptor.py
python pentest-utils/header_info.py https://example.com
python phishing-sim/generator.py
python ai-log-analyzer/rule_based_ai.py logs/sample.log

📚 License

MIT — 可任意修改使用，歡迎二創。

🧩 Contribution

歡迎 PR，例如加入：

新的釣魚模板

新的 encryption 模式

新的攻擊模擬器

🎉 最後

本專案目的不是重現真實攻擊，而是：

用創意，把資安變得更好理解、更有趣。
