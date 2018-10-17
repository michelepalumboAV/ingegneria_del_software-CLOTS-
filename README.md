# ingegneria_del_software-CLOTS-
Il sistema CLOTS è stato implementato secondo la modalità di sviluppo Three Tier, che rende il sistema aperto a modifiche in quanto separa le interfacce dalle applicazioni logiche. La piattaforma è stata decomposta in vari sottosistemi, al fine di facilitare il suo design e la sua implementazione. La decomposizione si propone di minimizzare le dipendenza (coupling) fra i sottosistemi identificati e di massimizzare la coesione all’interno degli stessi. Si è deciso ,inoltre, di fare affidamento anche ad un’architettura Client/Server in quanto si adatta bene alla scelta dei design goal ed al tipo di software da sviluppare. Tale architettura facilita la progettazione e l’implementazione del sistema per come è stato richiesto dal cliente. La presenza di un server permette ad un certo numero di client di condividere tali risorse, lasciando che sia il server a gestire gli accessi ad esse. Il software client è di limitata complessità in quanto lavora solo come interfaccia verso il server, offrendo disponibilità di lettura e scrittura tramite i pulsanti operativi come “Visualizza Prodotto”, “Acquista”, ecc. Il software server, oltre alla gestione logica del sistema, utilizza tutte le tecniche di gestione degli accessi, allocazione e rilascio delle risorse, condivisione e sicurezza dei dati o delle risorse. Inerentemente al nostro sistema CLOTS, il server sarà rappresentato dal browser sul quale verrà aperto il sito del negozio, ed utilizzato il database di quest’ultimo, insieme ad un DBMS che ne permetterà l’utilizzo per modifiche ed interrogazioni. La macchina server comunicherà con i terminali client attraverso lo stesso browser utilizzato dagli utenti. Inoltre, si servirà di opportuni protocolli di trasmissione, come http o ftp, che permetteranno una corretta comunicazione con i terminali client. Il server analizza le richieste di servizio, le soddisfa e notifica infine i risultati ai rispettivi client mediante dei messaggi.


<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
