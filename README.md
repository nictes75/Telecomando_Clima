# Telecomando_Clima
Telecomando climatizzatore in yaml per home assistant

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

Premendo nel display sopra la parole MODE visualizza l'ultima modalità eseguita dal climatizzatore.
