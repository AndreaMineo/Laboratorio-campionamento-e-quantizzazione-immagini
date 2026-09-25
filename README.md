# 🖼️ Laboratorio Digitale: Campionamento e Quantizzazione

![Scope](https://img.shields.io/badge/Uso-Didattico-indigo)
![License](https://img.shields.io/badge/Licenza-MIT-green)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20TailwindCSS%20%7C%20JS-blue)

Un'applicazione web interattiva e visuale progettata per la didattica dell'Informatica e delle scienze STEM. Lo strumento consente agli studenti di sperimentare in tempo reale i concetti fondamentali della **digitalizzazione delle immagini**: il **campionamento spaziale** (risoluzione in pixel) e la **quantizzazione della luminanza** (profondità di bit).

---

## 🎯 Obiettivi Didattici

- **Campionamento Spaziale**: Comprendere come la suddivisione di un'immagine continua in una griglia discreta di pixel ne determini la risoluzione spaziale.
- **Quantizzazione del Colore**: Esplorare l'impatto della profondità di bit ($2^b$ livelli di grigio) sulla qualità visiva e sull'effetto di contouring o posterizzazione.
- **Lente d'Ingrandimento 5x5**: Ispezionare la matrice numerica discreta (valori da $0$ a $2^b - 1$) che compone l'immagine nell'intorno del punto selezionato dal cursore.
- **Calcolo della Memoria**: Applicare la formula $Bit\_Totali = W \times H \times b$ e osservare il cambio istantaneo dell'occupazione di memoria in Bit, Byte e KiloByte.

---

## 🚀 Caratteristiche Principali

1. **🎨 Sorgenti di Immagini Flessibili**:
   - Preset vettoriali integrati ad alto contrasto generati via software (Geometrico, Ritratto, Paesaggio, Testo/Logo).
   - Possibilità di caricare qualsiasi file immagine dal proprio dispositivo o da URL web esterno.

2. **🎛️ Controlli Digitali Parametrici**:
   - **Slider Campionamento**: Regola la risoluzione da $8 \times 8$ pixel sino a $256 \times 256$ pixel.
   - **Slider Quantizzazione**: Seleziona la profondità di bit da $1$ bit ($2$ tonalità B/N) a $8$ bit ($256$ sfumature).
   - **Griglia dei Pixel**: Attivazione di una sovrapposizione visiva dei confini dei pixel.
   - **Confronto Istantaneo**: Toggle rapido per switchare tra immagine rielaborata e originale.

3. **🔍 Lente d'Ingrandimento Numerica 5x5**:
   - Ispezione visuale a matrice delle intensità numeriche discrete relative a un intorno di $25$ pixel ($5 \times 5$) attorno al cursore mouse o al tocco touch.

4. **💾 Scheda Calcolo Memoria Occupata**:
   - Pannello interattivo che mostra tutti i passaggi matematici e le conversioni per calcolare il peso del file immagine in Bit, Byte e KB.

---

## 💻 Come Utilizzare la Web App

Trattandosi di un’applicazione **single-file HTML client-side**, non richiede l'installazione di moduli Node.js, server backend né dipendenze complesse.

### Esecuzione in Locale
1. Scarica il file `laboratorio_campionamento_e_quantizzazione_2.html` (o rinominalo in `index.html`).
2. Apri il file direttamente facendoci doppio clic con un qualsiasi browser moderno (Chrome, Edge, Firefox, Safari).

---

## 🛠️ Tecnologie Utilizzate

- **HTML5 & Canvas API**: Per la manipolazione nativa e ultra-veloce dei dati immagine.
- **Tailwind CSS (CDN)**: Per il layout reattivo, pulito e moderno.
- **Lucide Icons**: Iconografia vettoriale minimalista e chiara.
- **JavaScript ES6**: Logica di elaborazione delle immagini, conversione in scala di grigi e quantizzazione completamente eseguite nel browser lato client.

---

## 📜 Licenza

Questo progetto è distribuito sotto licenza **MIT**. È possibile riutilizzarlo, modificarlo e distribuirlo liberamente per scopi didattici, accademici e formativi.
