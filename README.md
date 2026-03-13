# 🚦 Il Semaforo della Merenda

> Gioco educativo interattivo per bambini sulla corretta alimentazione

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 🎮 Di cosa si tratta

**Il Semaforo della Merenda** è un gioco drag & drop pensato per bambini delle scuole primarie.  
L'obiettivo è classificare correttamente 15 alimenti nei tre rettangoli colorati del semaforo,
imparando in modo divertente cosa è bene mangiare durante la merenda.

---

## 🍽️ Classificazione degli alimenti

| 🔴 Rosso — Da evitare | 🟡 Giallo — Con moderazione | 🟢 Verde — Consigliati |
|---|---|---|
| 🍟 Patatine | 🍰 Torta | 🍎 Mela |
| 🍫 Cioccolato | 🧃 Succo | 🥣 Yogurt |
| 🥐 Brioche | 🫓 Focaccia | 🍌 Banana |
| 🥤 Bibita | 🥪 Panino | 🥕 Carota |
| 🍬 Caramella | 🍪 Biscotto | 🥖 Pane |

---

## ✨ Funzionalità

- 🖱️ **Drag & Drop** fluido con SortableJS (compatibile mouse, touch screen e tablet)
- 👻 **Ghost manuale personalizzato** — elemento rimpicciolito che segue il cursore/dito senza inclinazione
- 🚦 **Semaforo animato** — si illumina di verde se corretto, rosso se sbagliato
- 📳 **Toast banner mobile** — notifica visiva animata (verde/rosso) che appare da sinistra su smartphone
- 🎊 **Schermata di successo** con coriandoli animati al completamento di tutti gli alimenti
- 🎯 **Calibrazione luci** — accessibile solo tramite scorciatoia da tastiera (nascosta agli utenti)
- ⚙️ **Pannello coordinate** — accessibile solo tramite scorciatoia da tastiera (nascosta agli utenti)
- 💾 **Salvataggio automatico** delle impostazioni di calibrazione nel localStorage
- 🔄 **Reset** per ricominciare da zero

---

## 🚀 Come usarlo

### Metodo 1 — Diretto nel browser
1. Scarica o clona il repository
2. Apri `index.html` nel browser — **nessun server necessario**

### Metodo 2 — Clona con Git
```bash
git clone https://github.com/Fra702sco/semaforo-della-merenda.git
cd semaforo-della-merenda
# Apri index.html nel browser
```

### Metodo 3 — GitHub Pages
Il gioco è disponibile online all'indirizzo:  
👉 **[https://fra702sco.github.io/semaforo-della-merenda](https://fra702sco.github.io/semaforo-della-merenda)**

---

## 🎯 Come calibrare le luci del semaforo

I pannelli di calibrazione e coordinate sono **nascosti** all'utente finale e accessibili
solo tramite scorciatoie da tastiera — così i bambini non possono modificare accidentalmente
le impostazioni.

### ⌨️ Scorciatoie da tastiera

| Azione | Windows / Linux | macOS |
|---|---|---|
| Apri/chiudi **Coordinate** | `Ctrl + Shift + L` | `Cmd + Shift + L` |
| Avvia/annulla **Calibratore** | `Ctrl + Shift + K` | `Cmd + Shift + K` |
| Annulla calibrazione | `ESC` | `ESC` |

### Procedura di calibrazione
1. Premi `Ctrl+Shift+K` (o `Cmd+Shift+K` su macOS)
2. Il cursore diventa una croce — clicca sul **centro del bulbo rosso**
3. Clicca sul **centro del bulbo giallo**
4. Clicca sul **centro del bulbo verde**
5. Le coordinate vengono **salvate automaticamente** nel browser

Per impostare le coordinate manualmente, usa `Ctrl+Shift+L`.  
Per ripristinare i valori di default, clicca **🔄 Default** nel pannello.

---

## 📱 Compatibilità

| Piattaforma | Supporto |
|---|---|
| Desktop (Chrome, Firefox, Edge) | ✅ Completo |
| Desktop Safari / macOS | ✅ Completo (ghost drag senza inclinazione) |
| Tablet (touch) | ✅ Completo |
| Mobile (iOS / Android) | ✅ Completo con toast banner |

---

## 📁 Struttura del progetto

```
semaforo-merenda/
├── index.html                          # Applicazione completa (single file)
├── assets/                             # Risorse statiche
│   └── image/
│       └── background/
│           ├── background.jpg          # Sfondo desktop
│           └── background-mobile.jpg  # Sfondo mobile
├── README.md                           # Questo file
└── LICENSE                             # Licenza CC BY-NC 4.0
```

---

## 🛠️ Tecnologie utilizzate

| Tecnologia | Utilizzo |
|---|---|
| **HTML5** | Struttura dell'applicazione |
| **CSS3** | Animazioni, layout, effetti glow, clip-path toast |
| **JavaScript (ES6+)** | Logica del gioco, ghost manuale, calibrazione, localStorage |
| **[SortableJS 1.15](https://sortablejs.github.io/Sortable/)** | Drag & drop degli alimenti |
| **localStorage** | Salvataggio impostazioni di calibrazione |

> Nessun framework, nessuna dipendenza backend — tutto gira nel browser.

---

## 📚 Contesto didattico

Progetto realizzato nell'ambito del programma **"La Salute a Tavola e in Palestra"**,  
un percorso di educazione alimentare rivolto agli studenti delle scuole primarie  
del comune di **Nicotera (VV), Calabria**.

L'obiettivo è sensibilizzare i bambini a scegliere in modo consapevole
cosa mangiare durante la merenda quotidiana.

---

## 👤 Autore

**Il Semaforo della Merenda** è un progetto educativo interattivo realizzato
nell'ambito del programma **"La Salute a Tavola e in Palestra"** a Nicotera (VV), Calabria 🇮🇹

### 🧑‍💻 Autore
- **Ideazione, design e coordinamento**: Francesco Taccone ([@Fra702sco](https://github.com/Fra702sco))
- **Sviluppo del codice**: Realizzato con il supporto di **Perplexity AI**

### 🎯 Obiettivo
Sensibilizzare i bambini delle scuole primarie a scegliere in modo
consapevole cosa mangiare durante la merenda quotidiana,
attraverso un gioco interattivo e divertente.

### 🏫 Contesto
Progetto sviluppato durante il **Servizio Civile** 2025/2026
presso il comune di Nicotera (VV), Calabria.

### 🤝 Ringraziamenti
- [Perplexity AI](https://perplexity.ai) — Supporto allo sviluppo del codice

---

## 📄 Licenza

Questo progetto è distribuito sotto licenza  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

✅ Puoi usarlo, modificarlo e condividerlo liberamente  
✅ Devi citare l'autore originale  
❌ Non puoi usarlo per scopi commerciali

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

---

*Fatto con ❤️ per i bambini di Nicotera*
```

**Cosa ho aggiornato rispetto alla versione precedente:**

- ✅ Aggiunto **ghost manuale** nelle funzionalità
- ✅ Aggiunto **toast banner mobile** nelle funzionalità
- ✅ Rimosso riferimento ai bottoni UI per calibrazione/coordinate — ora **solo scorciatoie da tastiera**
- ✅ Aggiunta **tabella scorciatoie** `Ctrl+Shift+L` / `Ctrl+Shift+K`
- ✅ Aggiunta sezione **Compatibilità** con nota macOS/Safari
- ✅ Corretto il link `git clone` (era malformattato con parentesi)
