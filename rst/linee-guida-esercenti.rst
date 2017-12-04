Linee guida per esercenti
=========================

La Legge n. 232 dell'11 dicembre 2016 assegna un bonus di 500 euro ai cittadini
residenti in Italia (in possesso, ove previsto, di permesso di soggiorno in
corso di validità) che compiono diciotto anni nel 2017.

La gestione del bonus può avvenire tramite qualunque tipo device
(smartphone, tablet, computer) connesso ad Internet, sia da parte
dei diciottenni che da parte degli esercenti (soggetti pubblici o
privati) presso i quali acquistare i prodotti previsti riconducibili
alle seguenti categorie: cinema, musica e concerti, eventi
culturali, libri, musei, monumenti, parchi naturali ed aree
archeologiche, teatro e danza, corsi di musica, di teatro o di
lingua straniera.

In particolare, nella web app gli esercenti avranno a disposizione
le seguenti funzionalità:

1. registrazione al servizio;

2. vendita attraverso esercizio fisico oppure on line

3. controllo e riscossione dei buoni di acquisto

4. fatturazione


1. Registrazione al servizio
----------------------------

"18app" può essere utilizzato solo dagli esercenti con credenziali di accesso
ai Servizi Telematici dell'Agenzia delle Entrate e che hanno incaricato dei
soggetti ad operare per proprio conto. Gli esercenti si devono, quindi,
obbligatoriamente registrare alla web app per poter vendere i propri prodotti.

Le fasi della registrazione:

-  **entro il 30 giugno 2018** registrazione alla web app con
   indicazione dei dati generali dell'esercente (dati anagrafici, di
   residenza, codice ATECO, recapiti telefonici, mail ed eventuale sito
   internet, accettazione della normativa vigente).

-  **entro il 30 giugno 2018** indicazione di categorie di prodotto e
   prodotti vendibili sia nel proprio esercizio fisico che in quello
   online.

Al termine della registrazione, il sistema assegnerà automaticamente
a ciascun esercente un "codice esercente" di 5 caratteri
alfanumerici da utilizzare in fase di riscossione dei buoni. Gli
esercenti possono modificare le informazioni registrate ogni qual
volta vorranno (ad esempio: variazione dati,
inserimento/cancellazione dei punti vendita fisici).


2. Vendita
----------

La web app mette a disposizione degli esercenti 2 tipologie di vendita:
nell'esercizio fisico oppure on-line (in fase di registrazione è possibile
indicare l'utilizzo anche di entrambe le tipologie). In caso di vendita
nell'esercizio fisico, l'esercente può indicare tutti i punti vendita dove i
diciottenni potranno esibire i "buoni" di spesa con l'indicazione delle
categorie di prodotto e dei prodotti disponibili. I punti vendita potranno
essere geolocalizzati nell'applicazione dei 18enni.

In caso di vendita online, l'esercente dovrà prima dotarsi di un
certificato da applicare al web-service (vd. `Allegato 1`_)
richiamabile dai propri sistemi per la verifica e validazione dei
buoni di spesa.

In particolare dovrà:

-  richiedere il certificato in fase di registrazione;

-  scaricare il certificato nei propri sistemi;

-  verificare l'istallazione del certificato tramite specifica chiamata
   del web-service, come da indicazioni in `Allegato 1`_. 

Si precisa che sarà possibile anche per gli esercenti che scelgono
la vendita presso l'esercizio fisico scegliere l'utilizzo delle API
services che prevedono il download ed istallazione di un certificato
nei propri sistemi, secondo il procedimento descritto per la vendità
online.

Si precisa, inoltre, che per gli esercenti che utilizzeranno il
web-services per la validazione dei buoni sono previsti i seguenti
stati di lavorazione legati alle attività di configurazione dei
propri sistemi in cui dovrà essere istallato il certificato:

+----------------+--------+-------------------------------------------------------+
| -  da attivare |     -> |     certificato da scaricare dall' applicazione 18app |
+----------------+--------+-------------------------------------------------------+
| -  attivabile  |     -> |     certificato scaricato, ma non istallato           |
+----------------+--------+-------------------------------------------------------+
| -  attivo      |     -> |     certificato istallato (vd. `Allegato 1`_).        |
+----------------+--------+-------------------------------------------------------+

..


3. Controllo e riscossione dei buoni d'acquisto
-----------------------------------------------

A partire da settembre 2017 e fino al 31 dicembre 2018 gli esercenti possono
verificare e riscuotere i buoni generati dai 18enni nati nel 1999 nelle
funzionalità dell'applicazione loro dedicate ed identificati da uno specifico
codice.

La verifica e validazione è differente in caso di vendita
nell'esercizio fisico oppure online.


Verifica in caso di vendita nell'esercizio fisico
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Nell'area non autenticata della web app gli esercenti possono;

-  indicare il codice del buono esibito dal beneficiario insieme al
   "codice esercente";

-  leggere il QR code o il codice a barre del buono.

In caso di riconoscimento del codice del buono, la web app
restituisce le informazioni generali dell'acquisto (categoria di
prodotto, bene, importo e cognome/nome del beneficiario);
eventualmente l'esercente può verificare il beneficiario anche
tramite l'esibizione di un documento d'identità. A questo punto,
l'esercente può validare il buono esibito consentendo di "scalare"
l'importo dal bonus totale di 500 euro del diciottenne.


Verifica in caso di vendita online
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Nel proprio sito internet, l'esercente consente al diciottenne di
indicare il codice del buono da verificare e riscuotere tramite
chiamata al web-service le cui specifiche sono reperibili
nell'`Allegato 1`_.

Gli esercenti possono visualizzare la lista dei buoni riscossi
utilizzando eventuali filtri di ricerca per data di generazione del
buono e/o per tipologia di vendita (esercizio fisico oppure online),
per categoria di prodotto e per buoni fatturati o data fatturare.

Nelle liste verrano visualizzate le seguenti informazioni:

-  categoria di prodotto

-  dettagli del prodotto acquistato (tipologia ed esercente/punto
   vendita)

-  identificativo del buono

-  identificativo della fattura elettronica in cui è stato indicato il
   bene acquistato

-  informazione sull'eventuale download della lista esportabile in
   formato .csv.


Le liste visualizzate potranno essere scaricate in formato .csv per facilitare
la preparazione della fattura elettronica.

Nella "lista dei buoni", resa disponibile nella web app 18app, gli
esercenti possono, inoltre, verificare se il numero di buoni
convalidati coincide con quello delle fatture.


4. Fatturazione
---------------

Agli esercenti viene riconosciuto un credito per ogni buono riscosso da dichiarare in sede di fatturazione elettronica.

L'esercente dovrà preparare la fattura in formato elettronico
secondo il tracciato stabilito per la fatturazione elettronica verso
la pubblica amministrazione ("Schema del file xml FatturaPA -
versione 1.1" reperibile nel sito
`www.fatturapa.gov.it, <http://www.fatturapa.gov.it/>`__ sezione
Norme e regole, Documentazione FatturaPA).

La valorizzazione degli elementi del tracciato xml dovrà rispettare
i requisiti formali e di obbligatorietà previsti e, con particolare
riferimento al blocco 2.2.1 <DettaglioLinee>, dovrà tener conto
delle indicazioni riportate nel documento "\ **Linee guida
fatturazione esercente**\ " disponibili nell'applicazione 18app.



.. _Allegato 1:

Allegato 1 – Specifica WS online
--------------------------------



Servizio Web per verifica voucher degli esercenti
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Gli esercenti registrati al servizio "\ **18app**\ " per la vendita
online potranno validare nei propri sistemi i voucher di acquisto di
beni da parte dei 18enni utilizzando uno specifico servizio web di
cui si forniscono di seguito le specifiche di utilizzo.

**In merito agli endpoint, si precisa che al momento l'indirizzo referenziato nel wsdl** 
(`http://bonus.mibact.it/VerificaVoucher <http://bonus.mibact.it/VerificaVoucher>`__) **è provvisorio.** 

Il servizio web di **verifica del voucher** da parte degli esercenti
rende disponibili 2 principali operazioni ("\ **Check** \ " e
"\ **Confirm**\ "). La seguente descrizione delle operazioni è
necessaria per valorizzare adeguatamente i campi di input. Pertanto
le operazioni esposte dall'interfaccia wsdl possono essere descritte
come segue:


**1. Check**

+-------------+---------------------------+---------------------+
|     INPUT:  | tipo operazione           |     *"1", "2"*      |
|             |                           |                     |
+-------------+---------------------------+---------------------+
|             | codice voucher            |                     |
|             |                           |                     |
+-------------+---------------------------+---------------------+
|             |                           |                     |
|     OUTPUT: |                           |     *CF o Nome e    |
|             |     nominativo            |     Cognome*        |
|             |     beneficiario          |                     |
+-------------+---------------------------+---------------------+
|             |     partita IVA esercente |                     |
+-------------+---------------------------+---------------------+
|             |                           | *cinema, teatro,    |
|             |     ambito                | libreria…*          |
+-------------+---------------------------+---------------------+
|             |     bene                  | *libri,             |
|             |                           | spettacoli…*        |
+-------------+---------------------------+---------------------+
|             |     importo               | *importo totale del |
|             |                           | voucher*            |
+-------------+---------------------------+---------------------+

Se **tipo operazione** verrà valorizzato con **"1"**, il check del
voucher restituirà all'esercente i campi previsti in output senza
consumare il voucher e quindi senza scalare l'importo dal borsellino
del beneficiario. Questa modalità di utilizzo dell'operazione non è
obbligatoria, ma lascia all'esercente la possibilità di eseguire un
controllo tra il nominativo del beneficiario e quello del suo
cliente in sessione.

Se **tipo operazione** verrà valorizzato con **"2"**, il check del
voucher consumerà direttamente l'importo, scalandolo dal borsellino
del beneficiario, e restituirà comunque le informazioni previste in
output. L'esercente potrà scegliere di usare direttamente questa
modalità oppure effettuare due chiamate successive: la prima per il
controllo del beneficiario e la seconda per l'effettivo utilizzo del
voucher.

Il sequence diagram seguente descrive ad alto livello l'interazione
tra i vari sistemi coinvolti, nei casi fin qui descritti:

|image0|



**2. Confirm**

+-------------+---------------------+---------------------+
|     INPUT:  |     tipo operazione |     *"1"*           |
|             |                     |                     |
+-------------+---------------------+---------------------+
|             |     codice voucher  |                     |
+-------------+---------------------+---------------------+
|             |     importo         |     *confermato     |
|             |                     |     dall'esercente* |
+-------------+---------------------+---------------------+
|     OUTPUT: |     esito           |                     |
+-------------+---------------------+---------------------+


In questa versione del servizio il **tipo operazione** verrà
valorizzato sempre con **"1"** e l'esercente potrà comunicare la
quota utilizzata rispetto all'importo totale del voucher,
momentaneamente impegnato. Il sistema scalerà l'importo dal
borsellino del beneficiario, riaccreditando la parte non utilizzata,
calcolata come differenza tra il valore totale del voucher e
l'importo comunicato dall'esercente.

L'\ **esito** dell'operazione (**"OK"** / **"KO"**) sarà restituito
all'esercente che potrà eventualmente fornire un feedback al
beneficiario.



Modalità di autenticazione
~~~~~~~~~~~~~~~~~~~~~~~~~~

Per consumare il web service di verifica del voucher, ogni esercente
dovrà essere dotato di un **certificato di autenticazione** da
installare nel proprio client del servizio e da utilizzare nella
chiamata SOAP per effettuare l'autenticazione in modalità SSL con
certificato client.

Tale certificato X509 sarà generabile e scaricabile in formato .cer
direttamente tramite l'applicazione web dedicata agli esercenti, in
area autenticata. In particolare il processo di generazione del
certificato prevede due step:

1. Il primo step di richiesta del certificato; a seguito di questa
operazione il sistema prende in carico la richiesta.

2. Il secondo step di verifica esito della richiesta; questa operazione
controlla se è pronto il certificato emesso da CA dedicata ed
eventualmente lo rende disponibile per il download.

Durante il primo step sarà necessario caricare un file .der
rappresentante la richiesta di certificato alla CA dedicata al
progetto. Tale csr deve presentare le seguenti caratteristiche:

- Algoritmo generazione chiavi: RSA

- Lunghezza chiavi: 2048 bit

Una volta scaricato il certificato X509 va installato, insieme alla
corrispondente chiave privata, nel client utilizzato per il servizio
di verifica voucher. Pertanto l'evento di download del certificato
non può rappresentare la definitiva attivazione dell'esercente. E'
stato previsto uno step di attivazione, di tipo "Check" con i
seguenti valori di input:

- tipo operazione = 1

- codice voucher = 11aa22bb

Questa operazione equivale ad una transazione di attivazione, il cui
unico effetto è quello di portare l'esercente nello stato attivo. Da
questo momento in poi i beneficiari potranno generare voucher reali
per tale esercente.

Endpoint del servizio

Il servizio risponde ai seguenti endpoint
`https://wstest.18app.italia.it/VerificaVoucherWEB/VerificaVoucher <https://wstest.18app.italia.it/VerificaVoucherWEB/VerificaVoucher>`__
(ambiente di prova)
`https://ws.18app.italia.it/VerificaVoucherWEB/VerificaVoucher <https://ws.18app.italia.it/VerificaVoucherWEB/VerificaVoucher>`__
(ambiente reale)


Codici di errore
~~~~~~~~~~~~~~~~

La seguente tabella rappresenta i possibili errori gestiti dal
sistema:

+-----------------------------------+-----------------------------------+
|     **Codice/Code**               |     **Descrizione/Description**   |
+===================================+===================================+
|     01                            |     Errore nel formato dei        |
|                                   |     parametri in input,           |
|                                   |     verificarli e riprovare       |
+-----------------------------------+-----------------------------------+
|                                   |     Error in the input            |
|                                   |     parameters, check and try     |
|                                   |     again                         |
+-----------------------------------+-----------------------------------+
|     02                            |     Il buono richiesto non è      |
|                                   |     disponibile sul sistema o è   |
|                                   |     già stato riscosso o          |
|                                   |     annullato                     |
+-----------------------------------+-----------------------------------+
|                                   |     The requested voucher is not  |
|                                   |     available on the system. It   |
|                                   |     could be already collected or |
|                                   |     canceled                      |
+-----------------------------------+-----------------------------------+
|     03                            |     Impossibile attivare          |
|                                   |     l'esercente. Verificare che i |
|                                   |     dati siano corretti e che     |
|                                   |     l'esercente non sia già stato |
|                                   |     attivato                      |
+-----------------------------------+-----------------------------------+
|                                   |     Impossible to activate the    |
|                                   |     user. Please verify input     |
|                                   |     parameters and that the user  |
|                                   |     has not been already          |
|                                   |     activated.                    |
+-----------------------------------+-----------------------------------+
|     04                            |     L'importo richiesto è         |
|                                   |     superiore all'importo del     |
|                                   |     buono selezionato             |
+-----------------------------------+-----------------------------------+
|                                   |     The amount claimed is greater |
|                                   |     than the amount of the        |
|                                   |     selected voucher              |
+-----------------------------------+-----------------------------------+
|     05                            |     Non si può verificare o       |
|                                   |     consumare il buono poichè     |
|                                   |     l'esercente risulta non       |
|                                   |     attivo                        |
+-----------------------------------+-----------------------------------+
|                                   |     User inactive, voucher        |
|                                   |     impossible to verify.         |
+-----------------------------------+-----------------------------------+
|     06                            |     Ambito e bene del buono non   |
|                                   |     coincidono con ambiti e beni  |
|                                   |     trattati dall'esercente       |
+-----------------------------------+-----------------------------------+
|                                   |     Category and type of this     |
|                                   |     voucher are not aligned with  |
|                                   |     category and type managed by  |
|                                   |     the user.                     |
+-----------------------------------+-----------------------------------+

|image1|


Esempi di request/response
~~~~~~~~~~~~~~~~~~~~~~~~~~

Di seguito si riportano due esempi di request e relativa response,
sia per l'operation "Check" che per l'operation "Confirm".

"Check"

Check request:

.. code-block:: xml

    <soapenv:Envelope
    xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
    xmlns:ver="http://bonus.mibact.it/VerificaVoucher/">
    <soapenv:Header/>
    <soapenv:Body>
    <ver:CheckRequestObj>
    <checkReq>
    <tipoOperazione>1</tipoOperazione>
    <codiceVoucher>2a75f266</codiceVoucher>
    <!--Optional:
    <partitaIvaEsercente>?</partitaIvaEsercente>
    -->
    </checkReq>
    </ver:CheckRequestObj>
    </soapenv:Body>
    </soapenv:Envelope> 
    
Check response:

.. code-block:: xml 

    <soapenv:Envelope
    xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
    <soapenv:Body>
    <a:CheckResponseObj
    xmlns:a="http://bonus.mibact.it/VerificaVoucher/">
    <checkResp>
    <nominativoBeneficiario>AAABBB10X10X111D</nominativoBeneficiario>
    <partitaIvaEsercente>01043931003</partitaIvaEsercente>
    <ambito>Teatro</ambito>
    <bene>Biglietti</bene>
    <importo>40.5</importo>
    </checkResp>
    </a:CheckResponseObj>
    </soapenv:Body>
    </soapenv:Envelope>

"Confirm"

|image2|


Confirm request:

.. code-block:: xml

    <soapenv:Envelope
    xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
    xmlns:ver="http://bonus.mibact.it/VerificaVoucher/">
    <soapenv:Header/>
    <soapenv:Body>
    <ver:ConfirmRequestObj>
    <checkReq>
    <tipoOperazione>1</tipoOperazione>
    <codiceVoucher>2a75f266</codiceVoucher>
    <importo>30.20</importo>
    </checkReq>
    </ver:ConfirmRequestObj>
    </soapenv:Body>
    </soapenv:Envelope> 
    
Confirm response:

.. code-block:: xml

    <soapenv:Envelope
    xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
    <soapenv:Body>
    <a:ConfirmResponseObj
    xmlns:a="http://bonus.mibact.it/VerificaVoucher/">
    <checkResp>
    <esito>OK</esito>
    </checkResp>
    </a:ConfirmResponseObj>
    </soapenv:Body>
    </soapenv:Envelope>


WSDL VerificaVoucher.wsdl
~~~~~~~~~~~~~~~~~~~~~~~~~

targetnamespace: `**http://bonus.mibact.it/VerificaVoucher/** <http://bonus.mibact.it/VerificaVoucher/>`__


+------------------+----------------------+----------------------------------------------+------------------+----------------------------------------------+
| services         | bindings             | porttypes                                    | messages         | types                                        |
|                  |                      |                                              |                  |                                              |
+------------------+----------------------+----------------------------------------------+------------------+----------------------------------------------+
| VerificaVoucher_ | VerificaVoucherSOAP_ | :ref:`VerificaVoucher <VerificaVoucherPort>` | CheckRequest_    | Check_                                       |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              | CheckResponse_   | CheckRequestObj_                             |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              | ConfirmRequest_  | :ref:`CheckResponse <CheckResponseType>`     |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              | ConfirmResponse_ | CheckResponseObj_                            |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              |                  | Confirm_                                     |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              |                  | ConfirmRequestObj_                           |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              |                  | :ref:`ConfirmResponse <ConfirmResponseType>` |
|                  |                      |                                              |                  |                                              |
|                  |                      |                                              |                  | ConfirmResponseObj_                          |
|                  |                      |                                              |                  |                                              |
+------------------+----------------------+----------------------------------------------+------------------+----------------------------------------------+



attributeFormDefault: 

elementFormDefault:

targetNamespace:	http://bonus.mibact.it/VerificaVoucher/


+---------------------+------------------+
| Elements            | Complex types    |
+---------------------+------------------+
| CheckRequestObj_    | Check_           |
|                     |                  |
| CheckResponseObj_   | CheckResponse_   |
|                     |                  |
| ConfirmRequestObj_  | Confirm_         |
|                     |                  |
| ConfirmResponseObj_ | ConfirmResponse_ |
+---------------------+------------------+

.. _VerificaVoucher:    

service **VerificaVoucher**

+---------+----------------------------------------------------------------------------------------------------------------+
| diagram | |image4|                                                                                                       |
+---------+----------------------------------------------------------------------------------------------------------------+
| ports   | **VerificaVoucherSOAP**                                                                                        |
|         |                                                                                                                |
|         | *binding*        :ref:`tns:VerificaVoucherSOAP <VerificaVoucherSOAP>`                                          |
|         |                                                                                                                |
|         | *extensibility*  :code:`<soap:address location="https://bonus.mibact.it/VerificaVoucherWEB/VerificaVoucher"/>` |
+---------+----------------------------------------------------------------------------------------------------------------+
| source  | .. code-block:: xml                                                                                            |
|         |                                                                                                                |
|         |    <wsdl:service name="VerificaVoucher">                                                                       |
|         |     <wsdl:port name="VerificaVoucherSOAP" binding="tns:VerificaVoucherSOAP">                                   |
|         |      <soap:address                                                                                             |
|         |      location="https://bonus.mibact.it/VerificaVoucherWEB/VerificaVoucher"/>                                   |
|         |     </wsdl:port>                                                                                               |
|         |    </wsdl:service>                                                                                             |
|         |                                                                                                                |
+---------+----------------------------------------------------------------------------------------------------------------+


.. _VerificaVoucherSOAP:

binding **VerificaVoucherSOAP**


+---------------+-------------------------------------------------------------------------------------------------------+
| diagram       | |image5|                                                                                              |       
+---------------+-------------------------------------------------------------------------------------------------------+
| type          | :ref:`tns:VerificaVoucher <VerificaVoucherPort>`                                                      |
+---------------+-------------------------------------------------------------------------------------------------------+
| extensibility | :code:`<soap:binding style="document" transport="http://schemas.xmlsoap.org/soap/http"/>`             |
|               |                                                                                                       |
+---------------+-------------------------------------------------------------------------------------------------------+
| operations    | **Check**                                                                                             |
|               |                                                                                                       |
|               | *extensibility* :code:`<soap:operation soapAction="http://bonus.mibact.it/VerificaVoucher/Check"/>`   |
|               |                                                                                                       |
|               | *input*         :code:`<soap:body use="literal"/>`                                                    |
|               |                                                                                                       |
|               | *output*        :code:`<soap:body use="literal"/>`                                                    |
|               |                                                                                                       |
|               | **Confirm**                                                                                           |
|               |                                                                                                       |
|               | *extensibility* :code:`<soap:operation soapAction="http://bonus.mibact.it/VerificaVoucher/Confirm"/>` |
|               |                                                                                                       |
|               | *input* :code:`<soap:body use="literal"/>`                                                            |
|               |                                                                                                       |
|               | *output* :code:`<soap:body use="literal"/>`                                                           |
+---------------+-------------------------------------------------------------------------------------------------------+
| used by       | Port VerificaVoucherSOAP_ in Service VerificaVoucher_                                                 |
+---------------+-------------------------------------------------------------------------------------------------------+
| source        | .. code-block:: xml                                                                                   |
|               |                                                                                                       |
|               |     <wsdl:binding name="VerificaVoucherSOAP" type="tns:VerificaVoucher">                              |
|               |      <soap:binding style="document" transport="http://schemas.xmlsoap.org/soap/http"/>                |
|               |      <wsdl:operation name="Check">                                                                    |
|               |       <soap:operation soapAction=`"http://bonus.mibact.it/VerificaVoucher/Check"/>                    |
|               |       <wsdl:input>                                                                                    |
|               |        <soap:body use="literal"/>                                                                     |
|               |       </wsdl:input>                                                                                   |
|               |       <wsdl:output>                                                                                   |
|               |        <soap:body use="literal"/>                                                                     |
|               |       </wsdl:output>                                                                                  |
|               |      </wsdl:operation>                                                                                |
|               |      <wsdl:operation name="Confirm">                                                                  |
|               |       <soap:operation soapAction=`"http://bonus.mibact.it/VerificaVoucher/Confirm"/>                  |
|               |       <wsdl:input>                                                                                    |
|               |        <soap:body use="literal"/>                                                                     |
|               |       </wsdl:input>                                                                                   |
|               |       <wsdl:output>                                                                                   |
|               |        <soap:body use="literal"/>                                                                     |
|               |       </wsdl:output>                                                                                  |
|               |     </wsdl:operation>                                                                                 |
|               |    </wsdl:binding>                                                                                    |
+---------------+-------------------------------------------------------------------------------------------------------+

.. _`VerificaVoucherPort`:

porttype **VerificaVoucher**

+------------+------------------------------------------------------+
| diagram    | |image6|                                             |
+------------+------------------------------------------------------+
| operations | **Check**                                            |
|            |                                                      |
|            | *input* :ref:`tns:CheckRequest <CheckRequest>`       |
|            |                                                      |
|            | *output* :ref:`tns:CheckResponse <CheckResponse>`    |
|            |                                                      |
|            | **Confirm**                                          |
|            |                                                      |
|            | *input* :ref:`tns:ConfirmRequest <ConfirmRequest>`   |
|            |                                                      |
|            | *output* :ref:`tns:ConfirmResponse <ConfirmResponse>`|
+------------+------------------------------------------------------+
| used by    | binding `VerificaVoucherSOAP`_                       |
+------------+------------------------------------------------------+
| source     | .. code-block:: xml                                  |
|            |                                                      |
|            |    <wsdl:portType name="VerificaVoucher">            |
|            |    <wsdl:operation name="Check">                     |
|            |    <wsdl:input message="tns:CheckRequest"/>          |
|            |    <wsdl:output message="tns:CheckResponse"/>        |
|            |    </wsdl:operation>                                 |
|            |    <wsdl:operation name="Confirm">                   |
|            |    <wsdl:input message="tns:ConfirmRequest"/>        |
|            |    <wsdl:output message="tns:ConfirmResponse"/>      |
|            |    </wsdl:operation>                                 |
|            |    </wsdl:portType>                                  |
+------------+------------------------------------------------------+



.. _CheckRequest:

message **CheckRequest**

+---------+------------------------------------------------------------------+
| parts   | **parameters**                                                   |
|         |                                                                  |
|         | *element* :ref:`tns:CheckRequestObj <CheckRequestObj>`           |
+---------+------------------------------------------------------------------+
| used by | Operation                                                        |
|         | `Check`_  [1]_                                                   |
|         | in PortType                                                      |
|         | :ref:`VerificaVoucher <VerificaVoucherPort>`  [1]_               |
+---------+------------------------------------------------------------------+
| source  | .. code-block:: xml                                              |
|         |                                                                  |
|         |    <wsdl:message name="CheckRequest">                            |
|         |     <wsdl:part name="parameters" element="tns:CheckRequestObj"/> |
|         |    </wsdl:message>                                               |
+---------+------------------------------------------------------------------+

.. _CheckResponse:

message **CheckResponse**

+---------+-------------------------------------------------------------------+
| parts   | **parameters**                                                    |
|         |                                                                   |
|         | *element*                                                         |
|         | :ref:`tns:CheckResponseObj <CheckResponseObj>`                    |
+---------+-------------------------------------------------------------------+
| used by | Operation                                                         |
|         | `Check`_ [1]_                                                     |
|         | in PortType                                                       |
|         | :ref:`VerificaVoucher <VerificaVoucherPort>` [1]_                 |
+---------+-------------------------------------------------------------------+
| source  | .. code-block:: xml                                               |
|         |                                                                   |
|         |    <wsdl:message name="CheckResponse">                            |
|         |     <wsdl:part name="parameters" element="tns:CheckResponseObj"/> |
|         |    </wsdl:message>                                                |
+---------+-------------------------------------------------------------------+

.. _ConfirmRequest:

message **ConfirmRequest**

+---------+--------------------------------------------------------------------+
| parts   | **parameters**                                                     |
|         |                                                                    |
|         | *element*                                                          |
|         | :ref:`tns:ConfirmRequestObj <ConfirmRequestObj>`                   |
+---------+--------------------------------------------------------------------+
| used by | Operation                                                          |
|         | `Check`_ [1]_                                                      |
|         | in PortType                                                        |
|         | :ref:`VerificaVoucher <VerificaVoucherPort>` [1]_                  |
+---------+--------------------------------------------------------------------+
| source  | .. code-block:: xml                                                |
|         |                                                                    |
|         |    <wsdl:message name="ConfirmRequest">                            |
|         |     <wsdl:part name="parameters" element="tns:ConfirmRequestObj"/> |
|         |    </wsdl:message>                                                 |
+---------+--------------------------------------------------------------------+

.. _ConfirmResponse:

message **ConfirmResponse**

+---------+---------------------------------------------------------------------+
| parts   | **parameters**                                                      |
|         |                                                                     |
|         | *element*                                                           |
|         | :ref:`tns:ConfirmResponseObj <ConfirmResponseObj>`                  |
+---------+---------------------------------------------------------------------+
| used by | Operation                                                           |
|         | `Check`_ [1]_                                                       |
|         | in PortType                                                         |
|         | :ref:`VerificaVoucher <VerificaVoucherPort>` [1]_                   |
+---------+---------------------------------------------------------------------+
| source  | .. code-block:: xml                                                 |
|         |                                                                     |
|         |    <wsdl:message name="ConfirmResponse">                            |
|         |     <wsdl:part name="parameters" element="tns:ConfirmResponseObj"/> |
|         |    </wsdl:message>                                                  |
+---------+---------------------------------------------------------------------+

.. _CheckRequestObj:

element **CheckRequestObj**

+------------+-------------------------------------------------------+
| diagram    | |image7|                                              |
+------------+-------------------------------------------------------+
| namespace  | http://bonus.mibact.it/VerificaVoucher/               |
+------------+-------------------------------------------------------+
| properties | content complex                                       |
+------------+-------------------------------------------------------+
| children   | :ref:`checkReq <checkReq>`                            |
+------------+-------------------------------------------------------+
| source     | .. code-block:: xml                                   |
|            |                                                       |
|            |    <xsd:element name="CheckRequestObj">               |
|            |     <xsd:complexType>                                 |
|            |      <xsd:sequence>                                   |
|            |       <xsd:element name="checkReq" type="tns:Check"/> |
|            |      </xsd:sequence>                                  |
|            |     </xsd:complexType>                                |
|            |    </xsd:element>                                     |
+------------+-------------------------------------------------------+



element **CheckRequestObj/checkReq**
 
+------------+-----------------------------------------------------------------------------------------------------+
| diagram    | |image8|                                                                                            |
+------------+-----------------------------------------------------------------------------------------------------+
| type       | :ref:`tns:Check <Check>`                                                                            |
+------------+-----------------------------------------------------------------------------------------------------+
| properties | content complex                                                                                     |
+------------+-----------------------------------------------------------------------------------------------------+
| children   | :ref:`tipoOperazione <tipoOp>`  :ref:`codiceVoucher <codVouc>`  :ref:`partitaIvaEsercente <pIvaEs>` |
+------------+-----------------------------------------------------------------------------------------------------+
|            | .. code-block:: xml                                                                                 |
|            |                                                                                                     |
| source     |    <xsd:element name="checkReq" type="tns:Check"/>                                                  |
+------------+-----------------------------------------------------------------------------------------------------+

.. _CheckResponseObj:

element **CheckResponseObj**

+------------+----------------------------------------------------------------+
| diagram    | |image9|                                                       |
+------------+----------------------------------------------------------------+
| namespace  |     http://bonus.mibact.it/VerificaVoucher/                    |
+------------+----------------------------------------------------------------+
| properties |     content complex                                            |
+------------+----------------------------------------------------------------+
| children   | :ref:`checkResp <checkResp>`                                   |
+------------+----------------------------------------------------------------+
|            | .. code-block:: xml                                            |
|            |                                                                |
| source     |    <xsd:element name="CheckResponseObj">                       |
|            |     <xsd:complexType>                                          |
|            |      <xsd:sequence>                                            |
|            |       <xsd:element name="checkResp" type="tns:CheckResponse"/> |
|            |      </xsd:sequence>                                           |
|            |     </xsd:complexType>                                         |
|            |    </xsd:element>                                              |
+------------+----------------------------------------------------------------+


.. _`checkResp`:

element **CheckResponseObj/checkResp**

+------------+-------------------------------------------------------------+
| diagram    | |image10|                                                   |
+------------+-------------------------------------------------------------+
| type       | :ref:`tns:CheckResponse <CheckResponse>`                    |
+------------+-------------------------------------------------------------+
| properties |     content complex                                         |
+------------+-------------------------------------------------------------+
| children   | :ref:`nominativoBeneficiario  <nomBen>`                     |
|            | :ref:`partitaIvaEsercente <pIvaEs>`                         |
|            | :ref:`ambito <ambito>`  :ref:`bene <bene>`                  |
|            | :ref:`importo <importo>`                                    |
+------------+-------------------------------------------------------------+
|            | .. code-block:: xml                                         |
|            |                                                             |
| source     |    <xsd:element name="checkResp" type="tns:CheckResponse"/> |
+------------+-------------------------------------------------------------+

.. _ConfirmRequestObj:

element **ConfirmRequestObj**

+------------+---------------------------------------------------------+
| diagram    | |image11|                                               |
+------------+---------------------------------------------------------+
| namespace  |     http://bonus.mibact.it/VerificaVoucher/             |
+------------+---------------------------------------------------------+
| properties |     content complex                                     |
+------------+---------------------------------------------------------+
| children   | :ref:`checkReq <checkReq>`                              |
+------------+---------------------------------------------------------+
|            | .. code-block:: xml                                     |
|            |                                                         |
| source     |    <xsd:element name="ConfirmRequestObj">               |
|            |     <xsd:complexType>                                   |
|            |      <xsd:sequence>                                     |
|            |       <xsd:element name="checkReq" type="tns:Confirm"/> |
|            |      </xsd:sequence>                                    |
|            |     </xsd:complexType>                                  |
|            |    </xsd:element>                                       |
+------------+---------------------------------------------------------+


.. _`checkReq`:

element **ConfirmRequestObj/checkReq**

+------------+------------------------------------------------------+
| diagram    | |image12|                                            |
+------------+------------------------------------------------------+
| type       | :ref:`tns:Confirm <Confirm>`                         |
+------------+------------------------------------------------------+
| properties |     content complex                                  |
+------------+------------------------------------------------------+
| children   | :ref:`tipoOperazione <tipoOp>`                       |
|            | :ref:`codiceVoucher <codVouc>`                       |
|            | :ref:`importo <importo>`                             |
+------------+------------------------------------------------------+
|            | .. code-block:: xml                                  |
|            |                                                      |
| source     |    <xsd:element name="checkReq" type="tns:Confirm"/> |
+------------+------------------------------------------------------+

.. _ConfirmResponseObj:

element **ConfirmResponseObj**

+------------+------------------------------------------------------------------+
| diagram    | |image13|                                                        |
+------------+------------------------------------------------------------------+
| namespace  |     http://bonus.mibact.it/VerificaVoucher/                      |
+------------+------------------------------------------------------------------+
| properties |     content complex                                              |
+------------+------------------------------------------------------------------+
| children   | :ref:`checkResp <checkResp>`                                     |
+------------+------------------------------------------------------------------+
|            | .. code-block:: xml                                              |
|            |                                                                  |
| source     |    <xsd:element name="ConfirmResponseObj">                       |
|            |     <xsd:complexType>                                            |
|            |      <xsd:sequence>                                              |
|            |       <xsd:element name="checkResp" type="tns:ConfirmResponse"/> |
|            |      </xsd:sequence>                                             |
|            |     </xsd:complexType>                                           |
|            |    </xsd:element>                                                |
+------------+------------------------------------------------------------------+


element **ConfirmResponseObj/checkResp**

+----------------+---------------------------------------------------------------+
| diagram        | |image14|                                                     |
+----------------+---------------------------------------------------------------+
| type           | :ref:`tns:ConfirmResponse <ConfirmResponse>`                  |
+----------------+---------------------------------------------------------------+
|     properties |     content complex                                           |
+----------------+---------------------------------------------------------------+
|     children   | :ref:`esito <esito>`                                          |
+----------------+---------------------------------------------------------------+
|                | .. code-block:: xml                                           |
|                |                                                               |
|     source     |    <xsd:element name="checkResp" type="tns:ConfirmResponse"/> |
+----------------+---------------------------------------------------------------+

.. _Check:

complexType **Check**

+-----------+-----------------------------------------------------------------+
| diagram   | |image15|                                                       |
+-----------+-----------------------------------------------------------------+
| namespace |     http://bonus.mibact.it/VerificaVoucher/                     |
+-----------+-----------------------------------------------------------------+
| children  | :ref:`tipoOperazione <tipoOp>`                                  |
|           | :ref:`codiceVoucher <codVouc>`                                  |
|           | :ref:`partitaIvaEsercente <pIvaEs>`                             |
+-----------+-----------------------------------------------------------------+
| used by   | element                                                         |
|           | :ref:`CheckRequestObj/checkReq <checkReq>`                      |
+-----------+-----------------------------------------------------------------+
|           | .. code-block:: xml                                             |
|           |                                                                 |
| source    |     <xsd:complexType name="Check">                              |
|           |      <xsd:sequence>                                             |
|           |       <xsd:element name="tipoOperazione" type="xsd:string"      |
|           |     minOccurs="1" maxOccurs="1"/>                               |
|           |       <xsd:element name="codiceVoucher" type="xsd:string"       |
|           |     minOccurs="1" maxOccurs="1"/>                               |
|           |       <xsd:element name="partitaIvaEsercente" type="xsd:string" |
|           |     minOccurs="0" maxOccurs="1"/>                               |
|           |      </xsd:sequence>                                            |
|           |     </xsd:complexType>                                          |
+-----------+-----------------------------------------------------------------+


.. _`tipoOp`:

element **Check/tipoOperazione**

+------------+----------------------------------------------------------+
| diagram    | |image16|                                                |
+------------+----------------------------------------------------------+
| type       |     **xsd:string**                                       |
+------------+----------------------------------------------------------+
| properties |     content simple                                       |
+------------+----------------------------------------------------------+
|            |  .. code-block:: xml                                     |
|            |                                                          |
| source     |     <xsd:element name="tipoOperazione" type="xsd:string" |
|            |     minOccurs="1" maxOccurs="1"/>                        |
+------------+----------------------------------------------------------+


.. _`codVouc`:

element **Check/codiceVoucher**

+------------+---------------------------------------------------------+
| diagram    | |image17|                                               |
+------------+---------------------------------------------------------+
| type       |     **xsd:string**                                      |
+------------+---------------------------------------------------------+
| properties |     content simple                                      |
+------------+---------------------------------------------------------+
|            |  .. code-block:: xml                                    |
|            |                                                         |
| source     |     <xsd:element name="codiceVoucher" type="xsd:string" |
|            |     minOccurs="1" maxOccurs="1"/>                       |
+------------+---------------------------------------------------------+


.. _`pIvaEs`:

element **Check/partitaIvaEsercente**
        
+------------+---------------------------------------------------------------+
| diagram    | |image18|                                                     |
+------------+---------------------------------------------------------------+
| type       |     **xsd:string**                                            |
+------------+---------------------------------------------------------------+
| properties |     minOcc 0                                                  |
|            |                                                               |
|            |     maxOcc 1                                                  |
|            |                                                               |
|            |     content simple                                            |
+------------+---------------------------------------------------------------+
|            |  .. code-block:: xml                                          |
|            |                                                               |
| source     |     <xsd:element name="partitaIvaEsercente" type="xsd:string" |
|            |     minOccurs="0" maxOccurs="1"/>                             |
+------------+---------------------------------------------------------------+


.. _`CheckResponseType`:

complexType **CheckResponse**

+-----------+--------------------------------------------------------------------+
| diagram   | |image19|                                                          |
+-----------+--------------------------------------------------------------------+
| namespace |     http://bonus.mibact.it/VerificaVoucher/                        |
+-----------+--------------------------------------------------------------------+
| children  | :ref:`nominativoBeneficiario <nomBen>`                             |
|           | :ref:`partitaIvaEsercente <pIvaEs>`                                |
|           | :ref:`ambito <ambito>`                                             |
|           | :ref:`bene <bene>`                                                 |
|           | :ref:`importo <importo>`                                           |
+-----------+--------------------------------------------------------------------+
| used by   | element                                                            |
|           | :ref:`CheckResponseObj/checkResp <checkResp>`                      |
+-----------+--------------------------------------------------------------------+
|           | .. code-block:: xml                                                |
|           |                                                                    |
| source    |    <xsd:complexType name="CheckResponse">                          |
|           |     <xsd:sequence>                                                 |
|           |      <xsd:element  name="nominativoBeneficiario" type="xsd:string" |
|           |    minOccurs="1" maxOccurs="1"/>                                   |
|           |      <xsd:element name="partitaIvaEsercente" type="xsd:string"     |
|           |    minOccurs="1" maxOccurs="1"/>                                   |
|           |      <xsd:element name="ambito" type="xsd:string"                  |
|           |    minOccurs="1" maxOccurs="1"/>                                   |
|           |      <xsd:element name="bene" type="xsd:string"                    |
|           |    minOccurs="1" maxOccurs="1"/>                                   |
|           |      <xsd:element name="importo" type="xsd:double"                 |
|           |    minOccurs="1" maxOccurs="1"/>                                   |
|           |     </xsd:sequence>                                                |
|           |    </xsd:complexType>                                              |
+-----------+--------------------------------------------------------------------+


.. _`nomBen`:

element **CheckResponse/nominativoBeneficiario**

+------------+-----------------------------------------------------------------+
| diagram    | |image20|                                                       |
+------------+-----------------------------------------------------------------+
| type       |    **xsd:string**                                               |
+------------+-----------------------------------------------------------------+
| properties |    content simple                                               |
+------------+-----------------------------------------------------------------+
|            | .. code-block:: xml                                             |
|            |                                                                 |
| source     |    <xsd:element name="nominativoBeneficiario" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>                                |
+------------+-----------------------------------------------------------------+

.. _partitaIvaEsercente:

element **CheckResponse/partitaIvaEsercente**

+------------+---------------------------------------------------------------+
| diagram    | |image21|                                                     |
+------------+---------------------------------------------------------------+
| type       |     **xsd:string**                                            |
+------------+---------------------------------------------------------------+
| properties |     content simple                                            |
+------------+---------------------------------------------------------------+
|            | .. code-block:: xml                                           |
|            |                                                               |
| source     |     <xsd:element name="partitaIvaEsercente" type="xsd:string" |
|            |     minOccurs="1" maxOccurs="1"/>                             |
+------------+---------------------------------------------------------------+


.. _`ambito`:

element **CheckResponse/ambito**

+------------+-------------------------------------------------+
| diagram    | |image22|                                       |
+------------+-------------------------------------------------+
| type       |     **xsd:string**                              |
+------------+-------------------------------------------------+
| properties |     content simple                              |
+------------+-------------------------------------------------+
|            | .. code-block:: xml                             |
|            |                                                 |
| source     |    <xsd:element name="ambito" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>                |
+------------+-------------------------------------------------+


.. _`bene`:

element **CheckResponse/bene**

+------------+-----------------------------------------------+
| diagram    | |image23|                                     |
+------------+-----------------------------------------------+
| type       |     **xsd:string**                            |
+------------+-----------------------------------------------+
| properties |     content simple                            |
+------------+-----------------------------------------------+
|            | .. code-block:: xml                           |
|            |                                               |
| source     |    <xsd:element name="bene" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>              |
+------------+-----------------------------------------------+


.. _`importo`:

element **CheckResponse/importo**

+------------+--------------------------------------------------+
| diagram    | |image24|                                        |
+------------+--------------------------------------------------+
| type       |    **xsd:double**                                |
+------------+--------------------------------------------------+
| properties |    content simple                                |
+------------+--------------------------------------------------+
|            | .. code-block:: xml                              |
|            |                                                  |
| source     |    <xsd:element name="importo" type="xsd:double" |
|            |    minOccurs="1" maxOccurs="1"/>                 |
+------------+--------------------------------------------------+

.. _Confirm:

complexType **Confirm**

+-----------+-----------------------------------------------------------+
| diagram   | |image25|                                                 |
+-----------+-----------------------------------------------------------+
| namespace |     http://bonus.mibact.it/VerificaVoucher/               |
+-----------+-----------------------------------------------------------+
| children  | :ref:`tipoOperazione <tipoOp>`                            |
|           | :ref:`codiceVoucher <codVouc>`                            |
|           | :ref:`importo <importo>`                                  |
+-----------+-----------------------------------------------------------+
| used by   | element :ref:`ConfirmRequestObj/checkReq <checkReq>`      |
+-----------+-----------------------------------------------------------+
|           | .. code-block:: xml                                       |
|           |                                                           |
| source    |    <xsd:complexType name="Confirm">                       |
|           |     <xsd:sequence>                                        |
|           |      <xsd:element name="tipoOperazione" type="xsd:string" |
|           |    minOccurs="1" maxOccurs="1"/>                          |
|           |      <xsd:element name="codiceVoucher" type="xsd:string"  |
|           |    minOccurs="1" maxOccurs="1"/>                          |
|           |      <xsd:element name="importo" type="xsd:double"        |
|           |    minOccurs="1" maxOccurs="1"/>                          |
|           |     </xsd:sequence>                                       |
|           |    </xsd:complexType>                                     |
+-----------+-----------------------------------------------------------+


element **Confirm/tipoOperazione**

+------------+---------------------------------------------------------+
| diagram    | |image16|                                               |
+------------+---------------------------------------------------------+
| type       |     **xsd:string**                                      |
+------------+---------------------------------------------------------+
| properties |     content simple                                      |
+------------+---------------------------------------------------------+
|            | .. code-block:: xml                                     |
|            |                                                         |
| source     |    <xsd:element name="tipoOperazione" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>                        |
+------------+---------------------------------------------------------+

element **Confirm/codiceVoucher**

+------------+--------------------------------------------------------+
| diagram    | |image17|                                              |
+------------+--------------------------------------------------------+
| type       |     **xsd:string**                                     |
+------------+--------------------------------------------------------+
| properties |     content simple                                     |
+------------+--------------------------------------------------------+
|            | .. code-block:: xml                                    |
|            |                                                        |
| source     |    <xsd:element name="codiceVoucher" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>                       |
+------------+--------------------------------------------------------+

..

element **Confirm/importo**

+------------+---------------------------------------------------+
| diagram    | |image24|                                         |
+------------+---------------------------------------------------+
| type       |     **xsd:double**                                |
+------------+---------------------------------------------------+
| properties |     content simple                                |
+------------+---------------------------------------------------+
|            | .. code-block:: xml                               |
|            |                                                   |
| source     |     <xsd:element name="importo" type="xsd:double" |
|            |     minOccurs="1" maxOccurs="1"/>                 |
+------------+---------------------------------------------------+


.. _`ConfirmResponseType`:

complexType **ConfirmResponse**

+-----------+--------------------------------------------------+
| diagram   | |image26|                                        |
+-----------+--------------------------------------------------+
| namespace |     http://bonus.mibact.it/VerificaVoucher/      |
+-----------+--------------------------------------------------+
| children  | :ref:`esito <esito>`                             |
+-----------+--------------------------------------------------+
| used by   | element                                          |
|           | :ref:`ConfirmResponseObj/checkResp <checkResp>`  |
+-----------+--------------------------------------------------+
|           | .. code-block::xml                               |
|           |                                                  |
| source    |    <xsd:complexType  name="ConfirmResponse">     |
|           |     <xsd:sequence>                               |
|           |      <xsd:element name="esito" type="xsd:string" |
|           |    minOccurs="1" maxOccurs="1"/>                 |
|           |     </xsd:sequence>                              |
|           |    </xsd:complexType>                            |
+-----------+--------------------------------------------------+


.. _`esito`:

element **ConfirmResponse/esito**

+------------+------------------------------------------------+
| diagram    | |image27|                                      |
+------------+------------------------------------------------+
| type       |     **xsd:string**                             |
+------------+------------------------------------------------+
| properties |     content simple                             |
+------------+------------------------------------------------+
|            | .. code-block:: xml                            |
|            |                                                |
| source     |    <xsd:element name="esito" type="xsd:string" |
|            |    minOccurs="1" maxOccurs="1"/>               |
+------------+------------------------------------------------+

.. [1] Nota: Codice campo modificato.



.. |image0| image:: _images/esercenti/image1.png
.. |image1| image:: _images/esercenti/image2.jpeg
.. |image2| image:: _images/esercenti/image3.jpeg
.. |image4| image:: _images/esercenti/image4.png
   :width: 3.23748in
   :height: 0.49875in
.. |image5| image:: _images/esercenti/image5.png
   :width: 2.8175in
   :height: 2.26625in
.. |image6| image:: _images/esercenti/image6.png
   :width: 2.8175in
   :height: 2.26625in
.. |image7| image:: _images/esercenti/image7.png
   :width: 2.52in
   :height: 1.89in
.. |image8| image:: _images/esercenti/image8.png
   :width: 2.52877in
   :height: 0.30625in
.. |image9| image:: _images/esercenti/image9.png
   :width: 2.67741in
   :height: 0.30625in
.. |image10| image:: _images/esercenti/image10.png
   :width: 3.08875in
   :height: 1.855in
.. |image11| image:: _images/esercenti/image11.png
   :width: 2.61629in
   :height: 0.30625in
.. |image12| image:: _images/esercenti/image12.png
   :width: 2.65994in
   :height: 1.2775in
.. |image13| image:: _images/esercenti/image13.png
   :width: 2.76493in
   :height: 0.30625in
.. |image14| image:: _images/esercenti/image14.png
   :width: 2.33625in
   :height: 0.7in
.. |image15| image:: _images/esercenti/image15.png
   :width: 2.46753in
   :height: 0.88375in
.. |image16| image:: _images/esercenti/image16.png
   :width: 1.08498in
   :height: 0.30625in
.. |image17| image:: _images/esercenti/image17.png
   :width: 1.07624in
   :height: 0.30625in
.. |image18| image:: _images/esercenti/image18.png
   :width: 1.27748in
   :height: 0.30625in
.. |image19| image:: _images/esercenti/image19.png
   :width: 3.1327in
   :height: 1.46125in
.. |image20| image:: _images/esercenti/image20.png
   :width: 1.45255in
   :height: 0.30625in
.. |image21| image:: _images/esercenti/image21.png
   :width: 1.27748in
   :height: 0.30625in
.. |image22| image:: _images/esercenti/image22.png
   :width: 0.68249in
   :height: 0.30625in
.. |image23| image:: _images/esercenti/image23.png
   :width: 0.665in
   :height: 0.30625in
.. |image24| image:: _images/esercenti/image24.png
   :width: 0.73499in
   :height: 0.30625in
.. |image25| image:: _images/esercenti/image25.png
   :width: 2.3625in
   :height: 0.88375in
.. |image26| image:: _images/esercenti/image26.png
   :width: 2.30997in
   :height: 0.30625in
.. |image27| image:: _images/esercenti/image27.png
   :width: 0.665in
   :height: 0.30625in
