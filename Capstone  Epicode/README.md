# Dashboard Vendite e Marketing - Power BI

## 📊 Panoramica Progetto

Questo progetto rappresenta un'**analisi interattiva delle performance di vendita e dell'efficacia delle strategie di marketing** di un'azienda manifatturiera nazionale. 

Il deliverable è un **report analitico in Power BI** presentabile al management, che consente di:
- ✅ Individuare i segmenti di mercato più redditizi
- ✅ Misurare l'impatto delle campagne marketing sulle vendite
- ✅ Identificare aree geografiche e categorie di prodotto su cui concentrare gli investimenti

---

## 🎯 Obiettivi

Costruire un **report interattivo** che fornisca:
1. **Visione esecutiva** con KPI principali
2. **Analisi geografica** per performance regionale
3. **Analisi dettagliata dei prodotti** per strategie commerciali
4. **Interattività completa** con filtri dinamici
5. **ROI marketing** come metrica centrale

---

## 📁 Struttura del Progetto

```
Capstone Epicode/
├── Report_Vendite_Marketing.pbix          # File Power BI principale
├── Sales_Marketing_Data.csv               # Dataset sintetico (500 record)
└── README.md                              # Questo file
```

---

## 🛠️ Tecnologie Utilizzate

- **Power BI Desktop** - Dashboard e visualizzazioni
- **DAX (Data Analysis Expressions)** - KPI calcolati
- **Power Query** - Trasformazione dati
- **CSV** - Dataset sintetico

---

## 📊 Dataset

**Fonte:** Dataset sintetico creato per simulare un'azienda manifatturiera nazionale
**Dimensione:** 500 transazioni
**Periodo:** 12 mesi completi
**Granularità:** Giornaliera

**Campi disponibili:**
- `Data` - Data della transazione
- `Regione` - Ovest, Sud, Est, Nord, Centro
- `Prodotto` - Prodotto A, B, C, D
- `Segmento` - Categoria di mercato
- `Unità_Vendute` - Quantità venduta
- `Prezzo_Unitario` - Prezzo per unità
- `Costo_Unitario` - Costo per unità
- `Spesa_Marketing` - Investimento marketing
- `Contatti_Marketing` - Numero contatti

---

## 📈 Misure DAX Implementate

| Misura | Formula | Significato |
|--------|---------|-------------|
| **Ricavi** | SUMX(Units × Price) | Ricavo totale |
| **Profitto** | SUMX(Ricavi - Costi) | Guadagno netto |
| **ROI** | Profitto / Spesa_Marketing | Ritorno su investimento |
| **Quota_Mercato** | Ricavi / Ricavi_Totali × 100 | Quota percentuale |
| **Margine_Profitto** | Profitto / Ricavi × 100 | Margine percentuale |
| **Indice_Soddisfazione** | IF(ROI>2.5,"Alto","Medio","Basso") | Livello soddisfazione |

---

## 📄 Dashboard - 3 Pagine

### **Pagina 1: Executive Summary**
Overview per il management con KPI principali:
- 4 KPI Cards: Ricavi (600M), Unità (25K), Profitto (329M), ROI (2,84)
- Timeline Ricavi nel Tempo (trend mensile)
- Gauge Chart ROI con spiegazione
- Filtri interattivi: Data, Regione, Prodotto

### **Pagina 2: Analisi Performance Regionale**
Analisi geografica dettagliata:
- Unità_Vendute per Regione
- Ricavi per Regione
- ROI per Regione (Ovest: 3,8 | Est: 2,1)
- Filtri per focus territoriale

### **Pagina 3: Analisi Performance Prodotto**
Strategia per linea di prodotto:
- Quota di Mercato (Pie Chart)
- Ricavi per Prodotto
- Profitto per Prodotto
- ROI per Prodotto
- Tabella Ranking completa

---

## 🎨 Caratteristiche Visive

- **Colori coerenti e professionali:** Verde (crescita), Blu (dati), Viola (ROI), Rosa (analisi)
- **Layout responsivo** su 3 pagine specializzate
- **Sfondi grigi** per delimitare sezioni visivamente
- **Emoji descrittivi** sui titoli per leggibilità
- **Formattazione numeri** in milioni per compattezza

---

## 📊 Key Insights

Dai dati emerge:

1. **ROI Marketing Eccellente (2,84)** - Ogni euro investito genera 2,84 euro di profitto
2. **Regione Ovest Dominante** - ROI più alto (3,8) rispetto a Est (2,1)
3. **Prodotti C e A Leader** - Condividono quota di mercato 28% ciascuno
4. **Stagionalità Evidente** - Picchi Feb/Mar, calo in Dic (-50%)
5. **Tutti i Prodotti Performanti** - Indice di Soddisfazione "Alto" su tutta la linea

---

## 🚀 Come Utilizzare

### Prerequisiti
- Power BI Desktop (versione 2023+)
- File: `Report_Vendite_Marketing.pbix`
- File: `Sales_Marketing_Data.csv`

### Procedura
1. Scaricare `Report_Vendite_Marketing.pbix`
2. Aprire in Power BI Desktop
3. I dati si caricheranno automaticamente
4. Usare i filtri (Data, Regione, Prodotto) su tutte le pagine
5. Navigare tra le 3 pagine con le frecce (← →)

### Filtri Interattivi
- **Data:** Filtra per intervallo temporale
- **Regione:** Seleziona una o più regioni
- **Prodotto:** Focalizza su specifiche linee

---

## 📌 Requisiti Progetto Rispettati

✅ Analisi performance vendita e marketing
✅ Dati per prodotto, area geografica, periodo temporale
✅ Quota di mercato visualizzata
✅ Report interattivo con filtri
✅ Individuazione segmenti redditizi
✅ Misurazione impatto campagne (ROI)
✅ Identificazione aree geografiche e categorie prodotto
✅ Power BI con DAX per KPI
✅ Dashboard presentabile al management

---

## 👤 Autore

**Antonio Spagnuolo**
- Email: antoniospagnuolo02@gmail.com
- Progetto: Capstone Project - Data Analytics
- Data: Maggio 2026

---

## 📝 Note Tecniche

- Dataset sintetico creato per rappresentare scenario realistico
- Indice di Soddisfazione basato su ROI (alternativa al sentiment non disponibile)
- Filtri interattivi implementati su tutte le pagine
- Misure DAX ottimizzate per performance
- 3 pagine specializzate per audience diverse

---

## 📞 Supporto

Per domande o chiarimenti sul progetto, contattare l'autore.

---

**Ultimo aggiornamento:** Maggio 2026
