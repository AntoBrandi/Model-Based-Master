# Model-Based-Master
Progetto del gruppo 'GM' realativo all'insegnamento di Model Based Design all'interno del master intitolato 'The future of engineering and manufacturing: Industry 4.0'.

### Authors:
* [Antonio Brandi](https://github.com/AntoBrandi)
* [Michael Scarcia](https://github.com/Michael29011994)
* [Mustafa Uğur Eren](https://github.com/Sarlken)

### Vending Machine
Progettazione attraverso il pacchetto StateFlow di MATLAB di una macchina automatica per l'erogazione di caffè o bevande.
Utilizzo del modulo Requirements di MATLAB per la valutazione del soddisfaciumento dei requisiti

### Pick & Place
Progettazione e Sviluppo di un robot che effettui operazioni di pick and place e che quindi interagisca con un magazzino per il prelievo di materiale,
uno spazio di lavoro condiviso con un operatore per l'assemblaggio ed una stazione di deposito del prodotto finito.
Si è partiti con la traduzione delle specifiche date da un cliente all'interno di un file excel dei requisiti e ad una progettazione dell'inteo sistema
attraverso il pacchetto di matlab System Composer, progettando prima le sinogle componenti del sistema, poi i loro collegamenti ed infine si sono organizzate
le singole componenti in macro componenti logiche.
Tale progettazione ha consentito poi una implementazione in Simulink del comportamento di ciascuna componente con l'utilizzo della libreria StateFlow.
Allo stesso tempo, i singoli comportamenti Simulink associati a ciascuna componente sono anche stati unificati all'interno di un unico file Simulink per il 
test complessivo del sistema.
Infine, le componenti del sistema così sviluppato sono state dotate, attraverso il pacchetto Requirement Manager di MATLAB dei requisiti elaborati in precedenza
e sono stati lanciati divbersi test per la verifica degli stessi e delle peformances complessive del sistema attraverso la Metric Dashboard di MATLAB.
