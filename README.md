# Olfaktorní Deník 🌹✨

> Luxusní osobní správce parfémů, SOTD (Scent of the Day) log a inteligentní rádce v provedení Single Page Application (SPA).

![Olfaktorní Deník Banner](https://img.shields.org/badge/Design-Niche%20Dark%20Mode-amber?style=for-the-badge)
![Tech Stack](https://img.shields.org/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20VanillaJS-zinc?style=for-the-badge)
![Database](https://img.shields.org/badge/Database-Firebase%20%7C%20LocalStorage-blue?style=for-the-badge)

---

## 💎 Vlastnosti Aplikace

1. **Niche Dark Mode Design**:
   - Temná luxusní estetika (`bg-zinc-950`), jemné zlaté / šampaňské detaily (`#D4AF37`), skleněný morpfišmus a špičková typografie (*Playfair Display* & *Inter*).

2. **Automatická Integrace Meteo API**:
   - Automatické načítání aktuální teploty a počasí pro **Brno, CZ** z rozhraní Open-Meteo při vytváření záznamu Vůně Dne.

3. **Předvyplněná Kolekce Parfémů**:
   - **Niche (11)**: Amouage Reflection Man, Ex Nihilo The Hedonist, Anatole Lebreton Vanille Havane, Roja The Midsummer Dream, Memo Paris Winter Palace, Memo Paris Odéon, Goldfield & Banks Ingenious Ginger, Une Nuit Nomade Sugar Leather, Nasomatto Baraonda, Essential Parfums The Musc, Clive Christian 1872.
   - **Designer (6)**: Swiss Arabian Essence of Casablanca, Afnan Turathi Electric, Valentino Born in Roma Yellow Dream, Afnan Supremacy Collector's Edition, French Avenue Liquid Brun, Afnan Rare Reef.

4. **SOTD Log & Posuvníky**:
   - Záznam Výdrže na kůži (0–10), Projekce / Sillage (0–10) a Reakce okolí (0–10) s možností libovolných poznámek.

5. **Wishlist & Blacklist**:
   - Správa nových přírůstků i seznam vůní, kterým se vyhýbáte.

6. **Inteligentní Olfaktorní Rádce**:
   - Algoritmus pro výběr ideální a alternativní vůně ze sbírky na základě 3 parametrů (Příležitost, Počasí, Žádaný dojem).

---

## 🚀 Jak Spustit Aplikaci

Aplikace je zcela soběstačná v jediném souboru `index.html`.

1. Klonujte repozitář:
   ```bash
   git clone https://github.com/hradskydavid06-bit/olfaktorni-denik.git
   ```
2. Otevřete `index.html` v libovolném moderním webovém prohlížeči (Chrome, Firefox, Safari, Edge).

---

## ⚙️ Konfigurace Firebase Cloud Firestore (Volitelné)

Ve výchozím stavu aplikace automaticky ukládá data do `localStorage` vašeho prohlížeče.

Pro synchronizaci s cloudovou databází Firebase Firestore otevřete `index.html` a doplňte vaše konfigurační klíče v objektu:

```javascript
const firebaseConfig = {
    apiKey: "VAŠE_API_KEY",
    authDomain: "VÁŠ_PROJECT.firebaseapp.com",
    projectId: "VÁŠ_PROJECT_ID",
    storageBucket: "VÁŠ_PROJECT_ID.appspot.com",
    messagingSenderId: "VÁŠ_SENDER_ID",
    appId: "VÁŠ_APP_ID"
};
```

---

&copy; 2026 Olfaktorní Deník. Všechna práva vyhrazena.
