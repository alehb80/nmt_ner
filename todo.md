#TODO

1. grid search per trovare il giusto assetto di iperparametri
2. beam search per avere piu traduzioni da dare in pasto alla fase di ner tagging
3. implementa la metrica per il ner tagging in inglese
4. implementa il ner tagging in latino con la metrica
5. confronta le metriche
6. confronto con baseline



##tip

* prova ad aggiungere layer alla rete (eventuali encoder o decoder) (https://github.com/google/seq2seq/blob/master/example_configs)

* se i risultati non sono buoni fare fine tuning su modelli pre addestrati in latino sul task di translation.