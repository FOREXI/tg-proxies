# tg-proxies
# ⚡ ProxyPulse — MTProto Check For Telegram

**ProxyPulse** is a lightweight, premium, and intelligent monitoring dashboard designed to test, benchmark, and sort Telegram MTProto proxies in real-time. It ensures high availability by utilizing an automated failover repository system, filtering out duplicates, and sorting the fastest proxies directly in your browser.

Live Demo: `https://<your-username>.github.io/<your-repo-name>/`

---

## 🚀 Key Features

- **🔄 Automated Failover Sources:** Intelligent mechanism that tries fetching proxies from a secure CDN first (`jsDelivr`). If blocked or failed, it switches to a secondary direct source (`GitHub Raw`) within milliseconds.
- **⚡ Real-Time Ping Checker:** Benchmarks proxy latency (`ms`) natively from your current network operator.
- **📊 Smart Sorting & Tagging:** Automatically bubbles up alive and ultra-fast proxies to the top, labeled with performance tags (`Excellent ⚡`, `Good 🟢`, `Average 🟡`).
- **📱 Instant QR Code Generator:** Generate on-the-fly scannable QR codes for each proxy to easily connect your mobile devices.
- **🌐 Network Status Monitor:** Displays your public IP address and ISP provider automatically at the top of the dashboard.
- **📋 Bulk Copying:** Copy all verified alive proxies sorted by speed into your clipboard with a single click.
- **🎨 Dark Premium UI:** Built using a modern Glassmorphism theme with Tailwind CSS, FontAwesome icons, and optimized typography.

---

## 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com) - For sleek styling and layout.
* [QRious](https://github.com/neocotic/qrious) - Lightweight pure JavaScript QR code generator.
* [Vazirmatn](https://github.com/rastikerdar/vazirmatn) - Premium Persian typography.
* [FontAwesome](https://fontawesome.com) - Modern icons.

---

## 📦 How to Use & Deploy

1. Fork or create a repository on GitHub (e.g., `tg-proxies`).
2. Create an `index.html` file and paste the source code.
3. Go to **Settings > Pages**.
4. Set the Source to **Deploy from a branch**, select `main` (or `master`), and click **Save**.
5. Your specialized MTProto checker dashboard will be live in less than a minute!

---

## 👨‍💻 Author

Made with ♥️ by **Saeed**
