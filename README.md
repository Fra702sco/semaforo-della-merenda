Ecco il README completo, copia e incolla tutto in un file `README.md`:


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

- 🖱️ **Drag & Drop** fluido con SortableJS (compatibile touch screen e tablet)
- 🚦 **Semaforo animato** — si illumina di verde se corretto, rosso se sbagliato
- 🎊 **Schermata di successo** con coriandoli animati al completamento di tutti gli alimenti
- 🎯 **Calibrazione luci** — clicca direttamente sui bulbi del semaforo per allineare le luci
- ⚙️ **Pannello coordinate** — impostazione manuale precisa della posizione luci
- 💾 **Salvataggio automatico** delle impostazioni di calibrazione nel localStorage
- 🔄 **Reset** per ricominciare da zero

---

## 🚀 Come usarlo

### Metodo 1 — Diretto nel browser
1. Scarica o clona il repository
2. Apri `index.html` nel browser — **nessun server necessario**

### Metodo 2 — Clona con Git
```bash
git clone https://github.com/Fra702/semaforo-della-merenda.git
cd semaforo-della-merenda
Apri index.html nel browser
```

### Metodo 3 — GitHub Pages
Il gioco è disponibile online all'indirizzo:  
👉 **[https://fra702.github.io/semaforo-della-merenda](https://fra702.github.io/semaforo-della-merenda)**

---

## 🎯 Come calibrare le luci del semaforo

Se le luci non sono perfettamente allineate con l'immagine dello sfondo:

1. Clicca il pulsante **🎯 Calibra Luci** in alto a destra
2. Il cursore diventa una croce — clicca sul **centro del bulbo rosso**
3. Clicca sul **centro del bulbo giallo**
4. Clicca sul **centro del bulbo verde**
5. Le coordinate vengono **salvate automaticamente** nel browser

Per impostare le coordinate manualmente, usa il pulsante **⚙️ Coordinate**.  
Per ripristinare i valori di default, clicca **🔄 Default** nel pannello.

---

## 📁 Struttura del progetto

```
semaforo-merenda/
├── index.html                              # Applicazione completa (single file)
├── assets/                                 # Risorse statiche
│ └── image/                                # Contiene tutte le immagini  
│ │ └── background                          # Sfondo e texture
│ │ │ └── IL-SEMAFORO-DELLA-MERENDA.jpg     # Immagine di sfondo del semaforo
├── README.md                               # Questo file 
└── LICENSE                                 # Licenza CC BY-NC 4.0
```

---

## 🛠️ Tecnologie utilizzate

| Tecnologia | Utilizzo |
|---|---|
| **HTML5** | Struttura dell'applicazione |
| **CSS3** | Animazioni, layout, effetti glow |
| **JavaScript (ES6+)** | Logica del gioco, calibrazione, localStorage |
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

 **Fra702sco**   
🔗 [github.com/Fra702sco](https://github.com/Fra702sco)

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
