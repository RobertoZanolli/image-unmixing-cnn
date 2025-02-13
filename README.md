# Image Separation Project

Questo progetto si focalizza sulla separazione di immagini utilizzando un'architettura basata su una rete neurale convoluzionale (CNN) con struttura encoder-decoder. L'obiettivo principale è prendere in input un'immagine combinata e restituire le due immagini originali separate. Le prestazioni del modello vengono valutate utilizzando l'errore quadratico medio (MSE) tra le immagini predette e quelle di riferimento.

Contenuto del progetto

Il progetto è fornito come un notebook Jupyter contenente tutto il codice necessario per il caricamento dei dati, la pre-elaborazione, la definizione del modello, l'addestramento e la valutazione delle prestazioni.

Dataset

## I dataset utilizzati per questo progetto sono:

MNIST: Dataset di cifre scritte a mano, composto da immagini in scala di grigi di dimensione 28x28, successivamente adattate a 32x32.

Fashion-MNIST: Dataset di immagini di capi d'abbigliamento, anch'esso composto da immagini in scala di grigi di dimensione 28x28, adattate a 32x32.

Le immagini vengono normalizzate (dividendo per 255) e combinate casualmente per creare il dataset di input al modello.

## Funzionalità del progetto

*Preprocessing dei dati*: Normalizzazione e adattamento delle immagini.

*Generazione dati di training*: Creazione dinamica di immagini combinate a partire da coppie casuali di immagini MNIST e Fashion-MNIST.

*Training del modello*: Addestramento della rete CNN encoder-decoder con funzione di perdita basata sull'errore quadratico medio.

*Valutazione delle performance*: Analisi delle prestazioni del modello, calcolo delle metriche e visualizzazione di esempi di separazione.

## Dataset di riferimento

I dataset utilizzati in questo progetto sono stati importati direttamente grazie a tensorflow:

MNIST Dataset

Fashion-MNIST Dataset

