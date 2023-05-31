# Datasets

In questa pagina raccogliamo una lista di dataset per la lingua italiana.

## Pretraining

I seguenti dataset possono essere usati per allenare modelli del linguaggio generici (*pretraining*) prima del *fine-tuning* su task specifici

- [Clean mc4-IT](https://huggingface.co/datasets/gsarti/clean_mc4_it) è un subset della porzione italiana del web crawl [mc4](https://huggingface.co/datasets/mc4) con procedure di filtering aggiuntive, contenente un totale di circa 103 milioni di documenti e 41 miliardi di parole.

## Fine-tuning

I seguenti dataset possono essere utilizzati per addestrare modelli del linguaggio a eseguire task specifici

- [CHANGE-IT](https://huggingface.co/datasets/gsarti/change_it) contiene 152'000 di titoli e articoli di giornale estratti dai quotidiani Il Giornale e La Repubblica, e può essere utilizzato per task di headline generation e style transfer.

- Il Corpus Italiano di Accettabilità Linguistica [ItaCoLA](https://huggingface.co/datasets/gsarti/itacola) include quasi 10'000 frasi con annotazioni di accettabilità linguistica aggiunte dagli autori, ed un subset aggiuntivo che include annotazioni di accettabilità più granulari riguardanti vari fenomeni linguistici.

- [Fauno StackOverflow](https://huggingface.co/datasets/andreabac3/StackOverflow-Italian-Fauno-Baize) include 57'046 samples in a conversational setting. Il conversational setting prevede la chat tra un umano e un assistente AI che lo supporta a trovare la soluzione ad un problema tecnico. Questo dataset è stato utilizzato per addestrare Fauno un Italian Conversational LLM.

- [Fauno Quora](https://huggingface.co/datasets/andreabac3/Quora-Italian-Fauno-Baize) Include 54'456 samples in a conversational setting. Il conversational setting prevede la chat tra un umano e un assistente AI che lo supporta a trovare la soluzione. Questo dataset è stato utilizzato per addestrare Fauno un Italian Conversational LLM.

- [Fauno MedQuad](https://huggingface.co/datasets/andreabac3/MedQuaAD-Italian-Fauno-Baize) Include 46'867 samples in a conversational setting. Il conversational setting prevede la chat tra un umano e un assistente AI che lo supporta a trovare la soluzione in ambito sanitario. Questo dataset è stato utilizzato per addestrare Fauno un Italian Conversational LLM.


