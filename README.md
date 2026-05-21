# 📡 mem101-raat-ko-pada-subah-exam

> *"Raat bhar soye, subah uthke GitHub khola — bhai yeh dekh, ab toh pass hoga"*

---

<div align="center">

![Made with Panic](https://img.shields.io/badge/Made%20with-Panic%20%26%20Red%20Bull-ff6b6b?style=for-the-badge&logo=github)
![Exam Tomorrow](https://img.shields.io/badge/Exam-Kal%20Hai%20Bhai-f472b6?style=for-the-badge)
![Pass Hoga](https://img.shields.io/badge/Result-Pass%20Hoga%20InshAllah-34d399?style=for-the-badge)
![Raat Ko Banaya](https://img.shields.io/badge/Built%20At-2%3A47%20AM-a855f7?style=for-the-badge&logo=moon)
![HTML](https://img.shields.io/badge/HTML-Pure%20Desi-fb923c?style=for-the-badge&logo=html5)

</div>

---

## 🤔 Yeh Kya Hai Bhai?

**MEM101 PUE Exam Prep** — ek aisi website jo tab banayi gayi jab exam kal tha, syllabus poora nahi tha, aur neend bilkul nahi aa rahi thi.

Yeh koi normal notes nahi hai. Yeh ek **glassmorphic, animated, GPU-smooth** exam prep portal hai jisme:

- 🎯 **Predicted Mock Paper** — Section A, B, C — bilkul last sem ke PUE pattern pe
- ⚡ **Electrical Engineering** — KCL, KVL, Transformer, Induction Motor, Resonance, DC Generator sab kuch
- ⚙️ **Mechanical Engineering** — Forces, Beams, Mechatronics, Hydraulics, Control Systems
- 🧮 **Formula Sheet** — Ek jagah pe saare formulas, memory tricks ke saath
- 💡 **Step-by-step solutions** — Har question ka full solution diagrams ke saath
- 🌀 **Smooth animations** — Orbs, particles, scroll progress — sab buttery smooth (GPU-only, no lag)

Target: **55+ out of 70** — aur bhai seriously ho sakta hai.

---

## 🗂️ Repo Structure

```
mem101-raat-ko-pada-subah-exam/
│
├── 📄 index.html          # Poora exam prep portal — ek hi file mein sab kuch
├── 📄 README.md           # Yeh jo tu abhi padh raha hai
└── 📄 super_50_MEM101.pdf # Original syllabus PDF (jo maine raat bhar ghura)
```

> Haan bhai, **sirf ek HTML file** hai. Koi framework nahi, koi npm install nahi, koi `node_modules` ka 400MB dabba nahi. Seedha double-click karo, kaam karo.

---

## ✨ Features — Jo Mujhe Khud Proud Karti Hain

| Feature | Kya Hai | Kyun Daala |
|---|---|---|
| 🌊 Animated Orb Background | 4 blurred gradient orbs float karte hain | Kyunki plain background se neend aati hai |
| ✨ Floating Particles | 20 GPU-animated particles | Vibes ke liye bhai, sirf vibes |
| 🪟 Glassmorphism Cards | `backdrop-filter: blur(20px)` wali cards | Apple se inspiration liya, college se nahi |
| 📊 Scroll Progress Ring | Bottom-right mein SVG ring | Pata chale kitna padha, kitna bacha |
| 🎛️ Tab Navigation | 4 sections — sticky top bar | Mobile pe bhi mast chalti hai |
| ⚡ Zero Lag | GPU-only animations, RAF throttled scroll | `will-change: transform` — no paint, no layout |
| 📐 SVG Diagrams | Inline circuit & beam diagrams | Books se photo kheenchna band karo |
| 🧮 Collapsible Solutions | Click karo toh solution khule | Pehle khud try karo, phir dekho |

---

## 🚀 Kaise Chalayein

### Option 1 — Seedha Chalao (Recommended)
```bash
# Kuch install karne ki zaroorat nahi
# Bas yeh file download karo aur double-click karo
open index.html
```

### Option 2 — Live Server se
```bash
# VS Code mein Live Server extension hai toh
# Right click → Open with Live Server
# Done. Khatam. Bas itna.
```

### Option 3 — GitHub Pages pe Deploy karo
```bash
git clone https://github.com/obsidianghost404/mem101-raat-ko-pada-subah-exam
cd mem101-raat-ko-pada-subah-exam

# GitHub repo settings mein jaao
# Pages → Deploy from branch → main → / (root)
# 2 minute mein live ho jaayega
```

---

## 📚 Covered Topics

<details>
<summary>⚡ <strong>Electrical Engineering (Unit 1, 2, 5)</strong> — click karo</summary>

### Unit 1 — Circuit Analysis
- KCL & KVL with diagrams
- Mesh Analysis (2-loop & 3-loop numericals)
- Nodal Analysis (multi-node numericals)
- Linear vs Non-linear elements

### Unit 2 — AC Circuits & Machines
- Series RLC Resonance — derivation + Q factor
- Parallel Resonance — dynamic impedance
- DC Generator — EMF equation + numericals
- DC Motor — back EMF, torque expression
- Transformer — EMF equation, efficiency, max η condition

### Unit 5 — Electrical Machines (part)
- 3-phase Induction Motor — working principle
- Torque-slip characteristics
- Slip, rotor speed, rotor frequency calculations
- Rotor magnetic field speed w.r.t. stator & rotor

</details>

<details>
<summary>⚙️ <strong>Mechanical Engineering (Unit 3, 4, 5)</strong> — click karo</summary>

### Unit 3 — Engineering Mechanics
- Force, Moment, Couple — definitions & characteristics
- Force systems classification
- Parallelogram & Polygon law
- Varignon's Theorem — statement + proof
- Hexagon force problems (with resolution tables)

### Unit 4 — Beams & Equilibrium
- Types of loads (point, UDL, UVL, moment)
- Types of supports (roller, hinge, fixed)
- Beam reaction problems — inclined roller support
- Equilibrium equations — ΣFx=0, ΣFy=0, ΣM=0

### Unit 5 — Mechatronics & Systems (part)
- Mechatronics — definition, advantages, disadvantages
- Sensors & Transducers — types
- Actuators — Single & Double Acting Hydraulic Cylinders
- Gears, Ratchet mechanism, Cam & Follower
- Pressure Relief Valve, 3/2 DCV
- Open loop vs Closed loop control systems

</details>

---

## 🎯 Probability Matrix — Kal Kya Aayega

```
╔══════════════════════════════════════════════════════╗
║  QUESTION                          PROBABILITY       ║
╠══════════════════════════════════════════════════════╣
║  Induction Motor (slip, Ns, Nr)    ████████████ 99%  ║
║  Nodal OR Mesh Analysis numerical  ████████████ 99%  ║
║  Beam Reactions                    ███████████  95%  ║
║  Transformer Efficiency (max η)    ███████████  95%  ║
║  Series RLC Resonance              ██████████   90%  ║
║  DC Generator EMF numerical        ██████████   90%  ║
║  Hexagon Force Problem             █████████    85%  ║
║  Mechatronics / Control Systems    █████████    85%  ║
╚══════════════════════════════════════════════════════╝
```

---

## 🧠 Ek Minute Ki Memory Tricks

```
🔌 E = φZNP/60A      → "Every Zebra Now Purrs Freely Anytime"
🔌 4.44fNφ           → "Chaar point chaar chaar" — transformer EMF
🔌 Ns = 120f/P       → synchronous speed — YAAD RAKHNA HAI
🔌 f₂ = s × f₁       → rotor frequency = slip × supply frequency
🔌 Max η → Pi = Pcu  → iron loss = copper loss at max efficiency

⚙️  ΣFx=0, ΣFy=0, ΣM=0  → teen equations, teen unknowns max
⚙️  Roller = 1 reaction  → sirf perpendicular wali
⚙️  Hinge = 2 reactions  → H aur V dono
⚙️  R = √(ΣFx² + ΣFy²) → Pythagoras, hamesha
```

---

## 🐛 Known Issues

| Bug | Status | Comment |
|---|---|---|
| `parentNode null crash` | ✅ Fixed | Footer se pehle inject karne ki koshish thi, sahi kiya |
| `Identifier 'mpSection' already declared` | ✅ Fixed | IIFE mein double `const` tha, hata diya |
| Lag on scroll | ✅ Fixed | `requestAnimationFrame` + `passive:true` + `will-change` |
| 40 particles on mobile | ✅ Fixed | 20 kar diye, GPU ne shukriya kaha |

---

## 🛠️ Tech Stack

```
HTML5          → Poora structure
CSS3           → Glassmorphism, animations, grid
Vanilla JS     → Zero dependencies, zero drama
SVG            → Inline circuit diagrams
Google Fonts   → Syne + JetBrains Mono
IntersectionObserver API → Smooth card entrance
requestAnimationFrame    → Throttled scroll
will-change: transform   → GPU compositor — no paint
```

**Bundle size:** ~1 file. ~2000 lines. ~0 node_modules. Maa kasam.

---

## 📸 Screenshots

> *"Agar screenshot hota toh daalta, abhi exam tha toh time nahi tha"*
>
> Bas download karo aur khud dekho — animations screenshot mein nahi aatey waise bhi.

---

## 🤝 Contributing

Agar tu bhi MEM101 ka student hai aur koi question choot gaya — PR maar de bhai.

```bash
git clone https://github.com/ObsidianGhost404/Electrical-Mechanical-mem101-Preparation-PUE/blob/main/README.md
git checkout -b feature/mera-wala-question
# apna question aur solution add karo
git commit -m "feat: Q14 ka solution daala jo mujhe bhi samajh nahi aaya"
git push origin feature/mera-wala-question
```

Pull request mein likho ki question kahan se liya aur solution correct hai ya nahi. Hum sab milke fail hote hain, aur hum sab milke pass bhi ho sakte hain.

---

## ⚠️ Disclaimer

```
Yeh notes ek banda ne raat 2 baje banaye hain jo khud exam de raha tha.
Koi guarantee nahi ki sab kuch 100% correct hai.
Cross-verify karo apni books se.
Agar fail ho gaye toh mujhe blame mat karna — maine koshish ki thi bhai.
Agar pass ho gaye toh star de do repo ko. 🌟
```

---

## 📄 License

**MIT License** — matlab jo chahein karo iske saath.

Copy karo, fork karo, apne naam pe dal do — koi nahi rokega.
Bas ek kaam karo — agar kaam aaya toh **⭐ star de do** repo ko.
Itni si request hai bhai, zyada nahi maang raha.

---

<div align="center">

Made with absolute rizz by **obsidianghost404**

*"Padhai nahi, strategy hai yeh"* 🎯

[![GitHub](https://img.shields.io/badge/GitHub-obsidianghost404-181717?style=for-the-badge&logo=github)](https://github.com/obsidianghost404)

</div>
