# 📘 GUIDA PUBBLICAZIONE GITHUB PAGES

## Prerequisiti
- Account GitHub (gratuito): https://github.com/signup

---

## PASSO 1: Crea Repository

### 1.1 Login GitHub
- Vai su https://github.com
- Fai login con le tue credenziali

### 1.2 Nuovo Repository
- Click su **"+"** in alto a destra
- Seleziona **"New repository"**

### 1.3 Configurazione Repository
Compila i campi:

```
Repository name: capitale-umano
Description: Calcolatore interattivo del capitale umano
```

Opzioni:
- ☑️ **Public** (lascia selezionato)
- ☑️ **Add a README file** (puoi saltare, lo caricherai dopo)
- License: **MIT License** (opzionale)

Click **"Create repository"**

---

## PASSO 2: Carica File

### 2.1 Caricamento via Web Interface

1. Nella pagina del repository, click **"Add file"** → **"Upload files"**

2. Trascina questi 3 file:
   - `index.html`
   - `README.md`
   - `LICENSE`

3. In basso:
   - Commit message: "Initial commit - Calcolatore capitale umano"
   - Click **"Commit changes"**

### 2.2 Alternativa: Git da Terminale

Se preferisci usare Git:

```bash
# Clona il repository
git clone https://github.com/TUOUSERNAME/capitale-umano.git
cd capitale-umano

# Copia i file nella cartella
# (index.html, README.md, LICENSE)

# Commit e push
git add .
git commit -m "Initial commit - Calcolatore capitale umano"
git push origin main
```

---

## PASSO 3: Attiva GitHub Pages

### 3.1 Vai su Settings
- Nel repository, click tab **"Settings"**

### 3.2 Configura Pages
- Nel menu laterale sinistro, scroll fino a **"Pages"**

### 3.3 Configurazione Source
Nella sezione **"Build and deployment"**:

- **Source**: Deploy from a branch
- **Branch**: 
  - Seleziona **main**
  - Seleziona **/ (root)**
- Click **"Save"**

### 3.4 Attendi Deployment
- GitHub inizia il deployment (1-2 minuti)
- Appare un box verde con URL: 
  ```
  Your site is live at https://TUOUSERNAME.github.io/capitale-umano/
  ```

---

## PASSO 4: Verifica Pubblicazione

### 4.1 Controlla URL
- Click sul link nel box verde
- Oppure vai direttamente a: `https://TUOUSERNAME.github.io/capitale-umano/`

### 4.2 Test Funzionalità
Verifica:
- ✅ Dashboard si carica correttamente
- ✅ Input funzionano
- ✅ Calcolo real-time attivo
- ✅ Design responsive su mobile

---

## PASSO 5: Personalizzazione (Opzionale)

### 5.1 Custom Domain
Se hai un dominio tuo:

1. **Settings** → **Pages**
2. **Custom domain**: inserisci `calcolatore.tuodominio.it`
3. Configura DNS:
   ```
   CNAME calcolatore TUOUSERNAME.github.io.
   ```

### 5.2 HTTPS
- GitHub Pages fornisce HTTPS automaticamente
- ☑️ Enforce HTTPS (raccomandato)

---

## 🔄 Aggiornamenti Futuri

### Come Aggiornare il Sito

**Via Web:**
1. Vai nel repository
2. Click su `index.html`
3. Click icona matita (Edit)
4. Modifica codice
5. Commit changes

**Via Git:**
```bash
cd capitale-umano
# Modifica i file localmente
git add .
git commit -m "Descrizione modifiche"
git push origin main
```

Dopo 1-2 minuti, le modifiche sono online.

---

## 🎯 URL Finale

Il tuo calcolatore sarà accessibile a:

```
https://TUOUSERNAME.github.io/capitale-umano/
```

**Condividilo via:**
- Link diretto
- QR Code
- Social media
- Email clienti

---

## 📊 Monitoraggio

### Statistiche Accesso
- **Settings** → **Insights** → **Traffic**
- Visualizzazioni ultime 2 settimane
- Referrer e visitatori unici

---

## ⚠️ Troubleshooting

### Sito Non Visibile
- Attendi 5 minuti dopo primo deployment
- Controlla Settings → Pages (deve essere "Active")
- Verifica file si chiami esattamente `index.html`

### Errore 404
- Controlla branch corretto (main)
- Verifica root directory (/)

### Design Rotto
- Apri console browser (F12)
- Verifica errori JavaScript
- Controlla cache browser (Ctrl+Shift+R)

---

## 🎓 Risorse Aggiuntive

- Documentazione GitHub Pages: https://docs.github.com/pages
- Supporto GitHub: https://support.github.com
- Community: https://github.community

---

## ✅ Checklist Completamento

- [ ] Account GitHub creato
- [ ] Repository "capitale-umano" creato
- [ ] 3 file caricati (index.html, README.md, LICENSE)
- [ ] GitHub Pages attivato
- [ ] Sito testato e funzionante
- [ ] URL condiviso

---

**Tempo stimato:** 10-15 minuti  
**Difficoltà:** ⭐⭐☆☆☆ (Principiante/Intermedio)  
**Costo:** €0 (completamente gratuito)

---

**Buona pubblicazione! 🚀**
