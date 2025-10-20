# FDSML_RecommenderSystem

Questo progetto si concentra sullo sviluppo di un sistema di raccomandazione ibrido, combinando regole di associazione e algoritmi di machine learning per fornire suggerimenti personalizzati agli utenti. I sistemi di raccomandazione sono strumenti chiave per la personalizzazione dei contenuti e trovano applicazione in diversi ambiti, tra cui e-commerce, servizi di streaming e social network. Il loro obiettivo principale è supportare l'utente nella scelta tra un insieme molto ampio di opzioni, fornendo suggerimenti rilevanti basati sulle preferenze esplicite o implicite.

## 🎯 Obiettivi

Negli ultimi anni, gli approcci ibridi hanno mostrato grande potenziale, combinando le capacità predittive dei modelli statistici con la conoscenza implicita nelle regole di associazione. L'obiettivo di questo progetto è studiare:
- **RQ1**: Quanto è efficace il post-processing delle regole di associazione nel migliorare la qualità degli item suggeriti?
- **RQ2**: Un approccio ibrido, che combina regole di associazione e algoritmi di machine learning, può migliorare la qualità delle raccomandazioni rispetto al solo post-processing delle regole?

## 📁 Struttura del Repository

- `models/`: contiene il da modelli addestrati;
- `results/`: include le association rules e i frequent patterns estratti;
- `semilavorati/`: contiene la documentazione dell'intero progetto;
- `main.ipynb`: notebook principale che guida l'intero flusso di lavoro;
- `requirements.txt`: elenco delle librerie e dipendenze necessarie;

## 📊 Dataset 
Il dataset utilizzato, *Netflix Movie Rating*, è reperibile su Kaggle al [seguente indirizzo](https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset?select=Netflix_Dataset_Movie.csv) Si suggerisce di salvarlo all'interno della cartella dataset.
