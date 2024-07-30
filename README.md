# Telecomando_Clima
Telecomando climatizzatore in yaml per home assistant

SPENTO
![telecomando](https://github.com/user-attachments/assets/90036c3c-504a-4d89-8597-329177fc33b3)


ACCESO
![telecomando2](https://github.com/user-attachments/assets/6bdcd711-1f6e-4baa-ac13-14d20497474b)


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
