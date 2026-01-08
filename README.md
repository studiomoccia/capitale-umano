# 📊 Calcolatore Capitale Umano 2026

Strumento web interattivo per la stima del valore attuale del capitale umano secondo il metodo finanziario attuariale.

## 🎯 Descrizione

Il **capitale umano** rappresenta il valore attuale dei redditi futuri che una persona genererà durante la propria vita lavorativa. Questo calcolatore utilizza la formula di attualizzazione dei flussi finanziari per stimare tale valore, tenendo conto di:

- Rendimento di mercato (BTP indicizzato all'inflazione)
- Livello di sicurezza dell'impiego
- Orizzonte temporale fino al pensionamento
- Reddito annuale netto

## 🚀 Demo Online

**[→ Prova il calcolatore](mmoccia-star/capitale-umano))**

## 📋 Caratteristiche

- ✅ Calcolo real-time
- ✅ Interfaccia intuitiva
- ✅ Metodologia trasparente
- ✅ Mobile-responsive
- ✅ Zero dipendenze esterne
- ✅ Funziona offline dopo il caricamento

## 🧮 Metodologia

### Formula di Calcolo

```
Valore Attuale = Reddito × [(1 - (1 / (1+r)^n)) / r]
```

Dove:
- **Reddito**: reddito annuale netto (€)
- **r**: tasso di attualizzazione (%)
- **n**: anni di lavoro restanti

### Tasso di Attualizzazione

Il tasso di attualizzazione si basa sul rendimento BTPei 2056 con premio al rischio:

| Livello Sicurezza | Moltiplicatore | Esempio (BTPei 2,58%) |
|-------------------|----------------|----------------------|
| Eccellente        | 1,0×           | 2,58%                |
| Media             | 1,5×           | 3,87%                |
| Modesta           | 2,0×           | 5,16%                |

### Ipotesi

- Crescita del reddito pari all'inflazione (incorporata nel BTPei)
- Reddito costante in termini reali
- Continuità lavorativa fino al pensionamento

## 💻 Utilizzo Locale

### Download

```bash
git clone https://github.com/tuousername/capitale-umano.git
cd capitale-umano
```

### Apertura

Apri `index.html` nel browser (nessuna installazione richiesta).

## 📱 Compatibilità

- ✅ Chrome / Edge / Safari / Firefox (versioni recenti)
- ✅ iOS Safari
- ✅ Android Chrome
- ✅ Desktop e Mobile

## 🛠️ Tecnologie

- HTML5
- CSS3 (Flexbox, Grid, Gradients)
- JavaScript Vanilla (ES6+)
- Zero framework o librerie esterne

## 📊 Casi d'Uso

- **Pianificazione finanziaria**: valutazione del patrimonio complessivo
- **Scelte lavorative**: confronto opportunità professionali
- **Consulenza assicurativa**: calcolo coperture adeguate
- **Formazione**: didattica su matematica finanziaria

## 🎓 Riferimenti Teorici

Il concetto di capitale umano deriva da:
- Gary Becker (Nobel Economia 1992)
- Theodore Schultz (Nobel Economia 1979)
- Jacob Mincer (equazione dei redditi)

## ⚠️ Disclaimer

Questo strumento è fornito per **finalità illustrative e formative**. 

Il calcolo del capitale umano è una stima che:
- Non costituisce consulenza finanziaria o assicurativa
- Dipende da ipotesi semplificatrici
- Può variare significativamente in base a fattori individuali
- Non garantisce i risultati futuri

Per decisioni finanziarie importanti, consultare professionisti qualificati.

## 📄 Licenza

MIT License - Libero utilizzo con attribuzione

di Matteo Moccia e Marco Liera
---

**Versione**: 1.0.0  
**Ultimo aggiornamento**: Gennaio 2026  
**Tasso BTPei riferimento**: 2,58% (Gennaio 2026)
