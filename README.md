# 🎮 ModernUO - Server di Giacomo

## 📋 Descrizione

Questo è il mio server personale **ModernUO** per apprendimento e sperimentazione con Ultima Online.

Branch principale: **my-shard** (configurazione funzionante)  
Branch sviluppo: **learning** (esperimenti e modifiche)

---

## ✅ Setup Completato

- **Data setup:** 03/12/2025
- **Versione ModernUO:** 0.15.3.12
- **Versione .NET:** 10.0.100
- **Client:** ClassicUO
- **Sistema Operativo:** Windows 11

---

## 🚀 Quick Start

### Compilazione
```powershell
.\publish.cmd release win x64
```

### Avvio Server
```powershell
cd Distribution
.\ModernUO.exe
```

### Primo Login
- **Server:** 127.0.0.1:2593
- **Account:** giacomo
- **Password:** [configurata durante setup]

---

## 📁 Struttura Progetto
```
ModernUO/
├── Distribution/          # Server compilato
│   ├── ModernUO.exe      # Eseguibile principale
│   ├── Saves/            # Salvataggi mondo
│   └── Data/             # Configurazioni
├── Projects/
│   ├── UOContent/        # Script di gioco
│   └── Server/           # Core del server
└── MieNote/              # Note personali (se presenti)
```

---

## 🌿 Branch Strategy

### **my-shard** (main branch)
- Setup base funzionante
- Server avviato e testato
- Mondo popolato
- **NON toccare!** Questo è il tuo "safe state"

### **learning** (development branch)
- Esperimenti e modifiche
- Item custom
- Script di test
- Feature in sviluppo

---

## 📚 Risorse

- **ModernUO Ufficiale:** https://github.com/modernuo/ModernUO
- **Discord:** https://discord.gg/modernuo
- **Documentazione:** Vedi cartella \docs/\

---

## 📝 Note

Questo repository è basato su [ModernUO](https://github.com/modernuo/ModernUO).  
Tutti i crediti vanno al team di ModernUO Development.

---

**Ultimo aggiornamento:** 03/12/2025
