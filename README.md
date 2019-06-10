# Test-provalab9

## Energia elettrica

Il  sistema  di  fatturazione  di  una  società  di  distribuzione  di  energia  elettrica  si  basa 
sull’interazione  tra  diversi  soggetti.  

Questo  documento,  destinato  all’attenzione  del responsabile  sviluppo  software,  presenta  un’analisi  del  problema  basata  su  informazioni ottenute da interviste effettuate negli ultimi due mesi.


La  società  di  distribuzione  (Società)  eroga  energia  elettrica  a  **utenti**  collegati  all’impianto  di distribuzione  mediante  un  allacciamento  controllato  da  un  dispositivo  elettronico  di  misura (**contatore**) in grado di registrare il consumo di energia, di fornire a richiesta della centrale di bassa  potenza  il  valore  della  **lettura**  corrente  dei  consumi,  di  segnalare  eventuali malfunzionamenti nell’impianto elettrico installato presso l’utenza.

La centrale di bassa potenza periodicamente  raccoglie  le  letture  e  le  invia  al  sistema  di  fatturazione  della  Società  che provvede al calcolo dell’importo relativo al consumo registrato dal contatore e all’emissione di una  **bolletta**  o  fattura.

Il  calcolo  dell’importo  è  effettuato  considerando  il  regime  fiscale applicato  a  ogni  utente  (esente  IVA  o  soggetto  a  IVA)  che  prevede,  quando  applicabile, un’imposizione determinata da un’aliquota (aliquota IVA, attualmente pari al 20%).

Inoltre, nel rispetto della normativa vigente, il calcolo dell’importo deve considerare una soglia (cosiddetta di  consumo  sociale)  sotto  la  quale  deve  essere  applicata  una  tariffa  ridotta  (costo  unitario sociale). Per consumi che superano questa soglia, l’importo deve essere calcolato applicando la tariffa piena (costo unitario).

Una volta emessa, la bolletta è spedita al domicilio dell’utente che può  provvedere  al  pagamento  presso  un  qualsiasi  ufficio  postale  (Posta).

Nel  caso  in  cui l’utente  abbia  domiciliato  le  bollette  presso  un  istituto  bancario,  la  bolletta  è  inviata  anche all’istituto  (Banca)  che  provvede  automaticamente  al  suo  pagamento  alla  data  di  scadenza indicata. 

In questo caso, la bolletta inviata all’utente è stampata in modo che non possa essere pagata presso un ufficio postale. 

Un utente può essere intestatario di più  **contratti**, ognuno associato a un contatore. 

Periodicamente, la Società provvede alla verifica dei pagamenti delle bollette, mediante un processo di accreditamento. 

I pagamenti effettuati presso la Banca e la Posta sono incrociati con le bollette emesse. 

In casi di morosità grave, la Società si riserva il diritto di sospendere l’erogazione dell’energia elettrica. 

****

**Domanda n.1**.Dare un diagramma di classi relativo a **bolletta**, **utenti**, **lettura**, **contatore**, **Posta e Banca**. 

**Domanda n.2**. Dare  un  diagramma  dei  casi  d’uso  che  comprenda GestioneLetture, EmissioneBollette, Accreditamento Bollette.  Fornire brevi descrizioni.



 

