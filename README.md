# empathetic-dialogues-explorations
This project aims at better understanding dialogues in the ED dataset. Pursuant to this end, we deploy several pre-trained models to categorise dialogues in ED into various dimensions. These dimensions are:

1) Emotional content. We categorised each dialogue in ED into one of 32 emotion classes with a (finetuned distBERT model)[https://huggingface.co/bdotloh/distilbert-base-uncased-empathetic-dialogues-context]
2) Empathy. We categorised listener's responses using the empathy detection module from Sharma el al., 2020 ([paper](https://arxiv.org/pdf/2009.08441.pdf), [code](https://github.com/behavioral-data/Empathy-Mental-Health)) 
