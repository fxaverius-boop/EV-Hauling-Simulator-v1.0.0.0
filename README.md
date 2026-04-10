# ⚡ EV Hauling Truck Simulator v1.0

> Mining Fleet Intelligence — Simulasi operasi hauling dump truck listrik untuk perencanaan fleet & charging infrastructure.

**©2026 Ir. Fransiscus Saferius S.T.**

---

## 🌐 Live Demo

👉 **[Buka Simulator](https://USERNAME.github.io/ev-hauling-simulator/)**

> *Ganti `USERNAME` dengan username GitHub Anda setelah deploy.*

---

## 📋 Fitur

- **Parallel Discrete Event Simulation** — Semua truck berjalan bersamaan via global priority queue
- **Resource Queue Constraints** — 1 Loader = 1 DT, 1 Dump Point = 1 DT, 1 Charging Pile = 1 Gun = 1 DT
- **Shift Change & Istirahat** — Shift change 06:00 & 18:00, istirahat 12:00 & 00:00
- **Idle Battery Consumption** — Konsumsi baterai saat antri di loader & dump point (unit ON)
- **Stagger Optimization** — Simulasi keberangkatan bersamaan vs bertahap
- **Charging Pile Optimization** — M/M/c queueing theory + iterasi jumlah charger optimal
- **Fleet Sizing** — Grafik DT vs Ritase per konfigurasi charger
- **Multi-Period** — Dashboard & Gantt chart: 1 hari, 2 hari, 1 minggu, 1 bulan
- **AI Analysis** — Analisis mendalam menggunakan Claude Opus 4.6
- **Gantt Chart** — Timeline operasi dengan resource timeline (Loader, Dump, Charger)

## 🚀 Cara Pakai

1. Buka link demo di atas, atau download `index.html` dan buka di browser
2. Atur parameter sesuai kondisi operasi Anda
3. Klik **▶ SIMULASI + AI**
4. Explore hasil di tab Dashboard, Gantt, Stagger, Charger, Fleet, Trucks, dan AI

## 📐 Teori yang Digunakan

- **M/M/c Queueing Theory** — Analisis antrian charging station
- **Discrete Event Simulation** — Simulasi berbasis event dengan priority queue
- **Stochastic Modeling** — Variasi waktu antri CPP

## 🛠️ Teknologi

- React 18 (via CDN)
- Babel (JSX transform di browser)
- Canvas API (grafik)
- Anthropic API (AI Analysis)
- **Zero dependencies** — Single HTML file, no build tools needed

---

*Built with ❤️ for Indonesian Mining Industry*
