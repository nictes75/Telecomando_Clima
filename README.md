# Telecomando_Clima
Telecomando climatizzatore in yaml per home assistant


![telecomando](https://github.com/user-attachments/assets/33560f0b-fe44-4dd1-a32b-684f157239a5)




Per utilizzare il codice dovete sostituire l'entita CLIMATE con la vostra e se volete il logo del vostro climatizzatore.

In configuration.yaml dovete aggiungere un entità input_bolean:

clima_last_operation:
  name: clima_last_operation
  initial: off  



Il progetto prevede che il climatizzatore possa fare le sequenti funzioni:
- dry
- cool
- heat
- fan_only

In modalità OFF, premendo nel display sopra la parole MODE visualizza l'ultima modalità eseguita dal climatizzatore.

Nei file è disponibile anche il logo (ge-logo-small.png)
