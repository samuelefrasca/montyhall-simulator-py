# Monty Hall Simulator (Custom Doors)

Un simulatore in Python che permette di esplorare il Paradosso di Monty Hall con un numero personalizzato di porte.

### Provalo Subito
Testa il codice python direttamente dal browser:
* [**Online Python**](https://www.online-python.com/d0QYAcaJBP)
* [**Programiz**](https://www.programiz.com/online-compiler/81ZaBBS5oRCQS)

Oppure testa la versione web:
* [**Sito live**](https://montyhall.pages.dev/)
* [**Repository**](https://github.com/samuelefrasca/montyhall-simulator)
---

### Come funziona?
A differenza della versione classica a 3 porte, questo script ti permette di giocare con **n** porte:
1. Scegli il numero totale di porte (minimo 3).
2. Effettui la tua prima scelta.
3. Il conduttore rivela tutte le porte contenenti capre, tranne la tua e un'ultima porta chiusa.
4. **La domanda cruciale:** Ti conviene cambiare o restare sulla tua scelta iniziale?

### La Matematica dietro il codice
Più porte aggiungi, più diventa vantaggioso cambiare. La formula generale per la probabilità di vittoria cambiando è:

$$P(\text{vittoria cambiando}) = \frac{n-1}{n}$$

*Esempio: Con 100 porte, se cambi hai il **99%** di probabilità di vincere.*

## Eseguire da codice sorgente

```bash
git clone https://github.com/samuelefrasca/montyhall-simulator-py
cd montyhall-simulator-py
python montyhall.py
```
---

> **Nota:** Il ritardo prima di svelare le porte è puramente scenico (aggiunto con `time.sleep()`), non si tratta di un calo di prestazioni.
