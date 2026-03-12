<div align="center">

# ⚡ NEXUS SEQUENCE CALCULATOR & JOURNAL

### *Institutional Liquidity Sweep Position Sizing Engine*

**Stop calculating. Start executing.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FJS%2FCSS-orange.svg)](https://developer.mozilla.org/en-US/docs/Web)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen.svg)](#)
[![Offline Ready](https://img.shields.io/badge/Works-Offline-purple.svg)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-cyan.svg)](http://makeapullrequest.com)

---

*Built for traders who discovered that the stop-loss being hit*
***is the setup, not the failure.***

[**🚀 Launch Calculator**](https://YOUR_USERNAME.github.io/nexus-sequence-calculator/) · [Features](#-features) · [How It Works](#-how-it-works) · [Installation](#-installation) · [Screenshots](#-screenshots)

---

</div>

## 🧠 The Problem

You trade a **liquidity sweep strategy** — a strategy where price takes out your stop-loss, grabs institutional liquidity, then moves violently in your predicted direction. Your results are extraordinary:

- **1:10 R:R minimum**, often reaching **1:18 to 1:25**
- **60%+ win rate** on the full sequence
- But the stop-loss gets hit **1-2 times** before the winning move

**The challenge?** After getting stopped out, you need to:
1. Recalculate your position size for the re-entry
2. Account for the capital already lost on the sweep
3. Stay disciplined enough to re-enter (the hardest part)
4. Do all this under live market pressure with emotions running high

**Mental math under pressure = mistakes. Mistakes = blown risk management. Blown risk management = blown accounts.**

---

## 💡 The Solution

NEXUS eliminates **all math during live trading**. Every calculation happens **before** the session starts.

Open the calculator → Enter your numbers → Read your lot sizes → Trade like a machine.

```
┌─────────────────────────────┐
│  Entry 1 (Scout):    0.08   │
│  Entry 2 (Confirmed): 0.12  │
│  Entry 3 (Conviction): 0.20 │
│  SL: 50 pips                │
│  Max Loss: -$200            │
└─────────────────────────────┘

Write it on a sticky note.
No thinking during the session.
Just execution.
```

---

## ✨ Features

### 🧮 Position Sizing Calculator

| Feature | Description |
|---------|-------------|
| **Inverse Pyramid Sizing** | Automatically splits your sequence budget across 3 entries (Scout → Confirmed → Conviction) with increasing size as conviction grows |
| **Multi-Currency Support** | USD, EUR, GBP, NGN — calculates in your account currency |
| **Instrument Presets** | One-click presets for Gold (XAU/USD), Forex pairs, or custom instruments |
| **6 Outcome Scenarios** | See exact P&L for every possible outcome: Win on Entry 1, Win after 1 sweep, Win after 2 sweeps at TP1/TP2/TP3, and full sequence loss |
| **TP Distance Calculator** | Converts R:R ratios to exact pip distances |
| **Weekly/Monthly Projections** | Compound growth projections based on your win rate and sequences per week |
| **Allocation Validation** | Real-time validation ensures your entry splits always total 100% |

### 📓 Trade Journal

| Feature | Description |
|---------|-------------|
| **Sequence-Based Logging** | Designed specifically for multi-entry strategies — logs the entire sequence as one unit |
| **Sweep Tracking** | Records how many sweeps occurred before the winning entry |
| **Sweep Depth** | Tracks how far price went beyond your SL (data to optimize SL placement) |
| **Displacement Quality** | Notes whether a strong displacement candle appeared after the sweep |
| **Emotion Tracking** | Log your emotional state: Calm, Anxious, FOMO, Revenge, Confident |
| **Rules Compliance** | Did you follow your rules? Yes / Partial / No — with win rate correlation |
| **Session Tracking** | Which session (London, NY, Overlap, Asian) for performance analysis |
| **CSV Export** | One-click export to CSV for Excel/Google Sheets analysis |
| **Persistent Storage** | All data saved automatically in your browser (localStorage) |
| **Delete & Clear** | Individual entry deletion or full data clear with confirmation |

### 📊 Analytics Dashboard

| Feature | Description |
|---------|-------------|
| **Performance Overview** | Total sequences, win rate, total R, total P&L, expectancy, average sweeps |
| **P&L Equity Chart** | Visual bar chart of every sequence's profit/loss |
| **Sweep Analysis** | Win rate broken down by number of sweeps — proves which entry wins most |
| **Session Performance** | Which trading sessions give you the best win rate |
| **TP Hit Distribution** | Which take-profit levels get hit most often |
| **Emotion Correlation** | Win rate comparison across emotional states — proves calm trading wins |
| **Rules Compliance Impact** | Win rate when rules followed vs. broken — the most powerful insight |
| **Win/Loss Streak** | Visual streak tracker with best/worst streak stats |

---

## 🎯 How It Works

### The Inverse Pyramid Model

Most traders use equal position sizing across all entries. This calculator implements the **Inverse Pyramid** — your smallest position is when you're *least* sure (Entry 1), and your largest is when you're *most* sure (Entry 3, after the market has confirmed your thesis via stop sweeps).

```
TRADITIONAL (Equal Sizing):
  Entry 1: 1% risk → stopped → -1%
  Entry 2: 1% risk → stopped → -1%
  Entry 3: 1% risk → +10R   → +10%
  Net: +8%

INVERSE PYRAMID:
  Entry 1: 0.4% risk → stopped → -0.4%  (Scout)
  Entry 2: 0.6% risk → stopped → -0.6%  (Confirmed)
  Entry 3: 1.0% risk → +10R   → +10%   (Conviction)
  Net: +9%

  At 18R: Net = +17%
  At 25R: Net = +24%
  Full loss: -2% (completely survivable)
```

The key insight: **each stop-out is not a failure — it's the market confirming that liquidity existed where you expected**. Your conviction should *increase* with each sweep, not decrease.

### The Reframe

```
OLD THINKING:
"I got stopped out. I'm losing money. Should I re-enter?"
→ Emotional. Reactive. Inconsistent.

NEW THINKING:
"Phase 1 complete. Liquidity confirmed. Deploying Phase 2
 with higher conviction and larger size."
→ Systematic. Confident. Antifragile.
```

---

## 🚀 Installation

### Option 1: Use Directly (GitHub Pages)

**[👉 Click here to launch](https://YOUR_USERNAME.github.io/nexus-sequence-calculator/)**

No installation needed. Works on any device with a browser.

### Option 2: Download & Run Locally

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/nexus-sequence-calculator.git

# Open the file in your browser
open index.html
# or on Windows:
start index.html
# or on Linux:
xdg-open index.html
```

That's it. **No npm. No build tools. No server. No dependencies.**

It's a single HTML file. Double-click it and it works. Forever. Offline.

### Option 3: Phone Shortcut

1. Open the GitHub Pages link on your phone
2. **iOS:** Share → Add to Home Screen
3. **Android:** Menu → Add to Home Screen
4. Now it looks and works like a native app

---

## 📸 Screenshots

### Calculator Tab
*Enter your account details and sequence configuration. Get exact lot sizes for all 3 entries instantly.*

### Journal Tab
*Log every sequence with sweep count, emotion, rules compliance, and detailed notes.*

### Analytics Tab
*See your performance data visualized — win rates by session, emotion correlation, sweep analysis, and streak tracking.*

---

## 🔧 Customization

### Adjusting Default Values

Open `index.html` in any text editor and modify the `value` attributes in the input fields:

```html
<!-- Change default account balance -->
<input type="number" id="cBal" value="10000">

<!-- Change default SL -->
<input type="number" id="cSL" value="50">

<!-- Change default TP ratios -->
<input type="number" id="cTP1" value="10">
<input type="number" id="cTP2" value="18">
<input type="number" id="cTP3" value="25">
```

### Adding More Instruments

Find the instrument dropdown in the journal section and add options:

```html
<select id="jPair">
    <option>XAU/USD</option>
    <option>EUR/USD</option>
    <!-- Add your pairs here -->
    <option>BTC/USD</option>
</select>
```

---

## 📐 Technical Details

| Aspect | Detail |
|--------|--------|
| **Architecture** | Single-file SPA (Single Page Application) |
| **Languages** | HTML5, CSS3, Vanilla JavaScript |
| **Dependencies** | Zero. None. Nada. |
| **Data Storage** | Browser localStorage (persistent, private, no server) |
| **Hosting** | Static file — GitHub Pages, Netlify, Vercel, or local |
| **Offline Support** | Full functionality without internet |
| **Browser Support** | Chrome, Firefox, Safari, Edge (any modern browser) |
| **Mobile** | Fully responsive — works on all screen sizes |
| **File Size** | ~45KB single HTML file |
| **Privacy** | All data stays in YOUR browser. Nothing is sent anywhere. |

---

## 🧠 The Philosophy Behind This Tool

> *"The best traders in the world don't have strategies that never lose. They have strategies where the wins are so much larger than the losses that losing is just a business expense."*

This tool was built for a specific type of trader:

1. **You trade liquidity sweeps** — your edge comes from entering *after* smart money has grabbed stop-loss liquidity
2. **Your R:R is asymmetric** — 1:10 minimum, often 1:18 to 1:25
3. **You accept getting stopped** as part of the process, not as failure
4. **You need to eliminate math during live trading** because calculation under pressure leads to emotional decisions

The calculator removes the mental overhead. The journal proves what works. The analytics reveal patterns you can't see in real-time.

**The result:** You stop being a trader who does math under pressure. You become an executor who follows a pre-calculated plan.

---

## 🤝 Contributing

Contributions are welcome! Here are some ideas:

- [ ] Dark/light theme toggle
- [ ] Import journal data from CSV
- [ ] Backup/restore to JSON file
- [ ] Additional chart types in analytics
- [ ] Multi-timeframe tracking
- [ ] Broker integration for auto-fill
- [ ] PWA support for better mobile experience
- [ ] Multiple strategy profiles

### How to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/awesome-feature`)
3. Commit your changes (`git commit -m 'Add awesome feature'`)
4. Push to the branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request

---

## ⚠️ Disclaimer

This tool is for **educational and personal use only**. It is not financial advice.

- Trading forex, gold, and other financial instruments carries significant risk
- Past performance does not guarantee future results
- Never risk money you cannot afford to lose
- Always do your own research and due diligence
- This tool helps with **position sizing math** — it does not predict market direction
- The creator assumes no liability for trading losses

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this tool. Attribution is appreciated but not required.

---

## ⭐ Support

If this tool helps your trading:

- **Star** this repository ⭐
- **Share** it with fellow traders
- **Fork** it and customize for your strategy
- **Contribute** improvements back to the community

---

<div align="center">

**Built with focus. Designed for discipline. Engineered for execution.**

*"Budget the sequence, not the trade."*

⚡

</div>
