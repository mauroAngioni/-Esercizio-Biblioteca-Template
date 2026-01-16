# -Esercizio-Biblioteca-Template

# Esercitazione Lab informatica
**Classe:** 4AIT  
**Data:** 13/01/2026

## Obiettivo della prova
Si vuole implementare un programma a supporto per i prestiti di una Biblioteca. Nella Biblioteca, interessa registrare i dati degli utenti (**nome**, **cognome** e **recapito**), e tenere traccia dei prestiti da essi effettuati. Ogni prestito è composto da un **libro**, un **utente**, dalla **data di prestito**, quella di **scadenza**, e dalla **data di effettiva restituzione**.

## Requisiti del progetto

Dopo aver tracciato il **diagramma UML**, completo di tutti i metodi necessari, si implementino nelle classi opportune i seguenti metodi:

1.  **Costruttori delle classi**: Inizializzazione corretta degli attributi.
2.  **Gestione Utenti**: Implementare i metodi `registraUtente()` e `eliminaUtente()`.
3.  **Visualizzazione**: Il metodo opportuno che consenta di stampare tutti i dati dell’utente.
4.  **Statistiche**: Un metodo per contare i prestiti effettuati da un certo utente, cercandolo per **nome** e **cognome**.

## Implementazione del Test (Classe Lancio)
Si implementi poi una classe **Lancio**, con un metodo `main`, che consenta di:
*   Creare un oggetto **Biblioteca** ed aggiungerci alcuni utenti e prestiti.
*   Stampare a video i dati di tutti gli utenti registrati.
*   Stampare il numero di prestiti effettuati dall'utente **"Mario Rossi"**.

---

### Note Integrative per lo svolgimento:
*   **Gestione della memoria**: Per la memorizzazione di utenti e prestiti all'interno della Biblioteca, utilizzare degli **array di oggetti**.
*   **Semplificazione**: Per semplicità, si può supporre che **non esista un catalogo di libri** (il libro nel prestito può essere gestito come una semplice stringa o un oggetto base senza una collezione dedicata).
*   **Relazioni tra classi**: Prestare attenzione ai concetti di aggregazione (tra Prestito e Utente) e composizione (tra Biblioteca e le sue liste di oggetti).

