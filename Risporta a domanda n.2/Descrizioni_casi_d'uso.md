# Risposta a domanda n.2

## Breve descrizione dei casi d'uso

*Nome caso d’uso*: **Gestione Letture**

*Descrizione*: il sistema preleva la lettura dal contatore, e le registra in una base dati DBLetture.

*Nome caso d’uso*: **Emissione Bollette**

*Descrizione*: periodicamente,  il  sistema  stampa,  per  l’invio  all’Utente,  usando  dati prelevati  dal  DBUtente,  le  bollette  relative  all’ultima  lettura,  e  le  registra  nel  DBBollette;  nel caso di bollette domiciliate le invia pure elettronicamente alla Banca, per il pagamento.

*Nome caso d’uso*: **Accreditamento Bollette**

*Descrizione:* periodicamente il sistema riceve elettronicamente il pagamento delle bollette dalla posta e dalla banca, e li registra nel database delle bollette. periodicamente,  estraendo  le informazioni dal DBBollette, stampa i solleciti per i clienti morosi, usando i dati del DBUtenti.

