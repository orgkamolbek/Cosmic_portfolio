Bu loyihangiz shunchaki mukammal! Cosmic Portfolio (Koinot uslubidagi portfolio) veb-dizaynda g'oyaviy jihatdan eng kreativ yondashuvlardan biri hisoblanadi. Markazda o'z avataringiz (Quyosh) va uning atrofida turli tezliklarda aylanuvchi texnologiyalar (Planetalar) joylashgani CSS-dagi @keyframes va orbital tizim mantiqini yuqori darajada tushunishingizni isbotlaydi.

Ushbu ajoyib loyihangiz uchun repozitoriyaga joylashtirishga tayyor, ichida vizual joylashuv sxemasi bo'lgan professional va daxshatli README.md fayli:

Markdown
# 🌌 Cosmic Portfolio: Interactive Orbital System

CSS va HTML yordamida yaratilgan, astronomik tizim g'oyasiga asoslangan interaktiv va kreativ portfolio konsepti. Loyiha markazida dasturchining o'zi (Quyosh sifatida) va uning atrofidagi orbitalarda turli xil tezliklarda aylanuvchi asosiy texnologiyalar (Planetalar sifatida: HTML, CSS, Python) aks ettirilgan.

---

## 📸 Loyiha ko'rinishi (Visual Space Mockup)

> **Ekran to'liq qora koinot bag'ridagi yulduzlar va markazda aylanuvchi orbital tizimdan iborat:**

   .               .                  .                  .
           .               .                    .
                  /~~~~~~~~~~~~~~~~~\
                 /   .-----------.   \         .
                /   /             \   \
               /   /     _____     \   \
              |   |     /     \     |   |     [Planet: Python]
              |   |    |  SUN  |    |   |           (p3)
[Planet: HTML] |   |     _/     |   |
(p1)       \   \               /   /
\   \             /   /
\   '-----------'   /          .
_____________/

[Cosmic Portfolio]
.               .                Planetalar ustiga bosing..


### ⚙️ Orbital Aylanish Arxitekturasi (Animation Physics)

Har bir planeta o'z orbitasi bilan birgalikda sof CSS animatsiyalari yordamida cheksiz aylanish ssenariysi asosida ishlaydi:

[ Central Core: Sun (Avatar) ] ──► (Fixed position / Z-index: 10)
│
├──► Orbit 1 (250px) ──► Planet 1 [HTML]   ──► Animation: 10s (Tez)
│
├──► Orbit 2 (400px) ──► Planet 2 [CSS]    ──► Animation: 20s (O'rtacha)
│
└──► Orbit 3 (550px) ──► Planet 3 [Python] ──► Animation: 35s (Sekin)


---

## ⚡ Asosiy xususiyatlari (Features)

* ☀️ **Central Radiant Core:** Markaziy element atrofida yorqin neon nurlanish effekti (`box-shadow: 0 0 50px #ffcc00`) va doira shaklidagi profil surati.
* 🪐 **Orbital Dynamic Physics:** Planetalar kattalashgani sari markazdan uzoqlashishi va aylanish vaqtlari uzayishi (10s ──► 20s ──► 35s), xuddi haqiqiy astronomik qonuniyatlar kabi.
* 🔮 **Glassmorphic Control Panel:** Oynasimon va shaffof ma'lumotlar bloki (`backdrop-filter: blur(10px)`), koinot atmosferasini buzmagan holda foydalanuvchiga ko'rsatma beradi.
* 💫 **Zero-Weight Performance:** Hech qanday og'ir GIF yoki video fayllarsiz, faqatgina toza CSS kod orqali sekundiga 60 kadr (60 FPS) tezlikda silliq ishlovchi animatsiya.

---

## 🛠️ Texnologiyalar (Tech Stack)

* **HTML5** — Orbitalar strukturasi va planetalar joylashuvi.
* **CSS3 Custom Animations** — `@keyframes rotate`, Shaffof oyna effekti, mutloq koordinatalar (`absolute positioning`) va neon effektlari.

---

## 🚀 Ishga tushirish (How to Run)

Loyiha hech qanday qo'shimcha plaginlar yoki server talab qilmaydi:

1. Repozitoriyni klonlang:
   ```bash
   git clone [https://github.com/orgkamolbek/cosmic-portfolio.git](https://github.com/orgkamolbek/cosmic-portfolio.git)
