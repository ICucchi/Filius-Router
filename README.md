# Filius-Router
Nel primo esercizio che abbiamo affrontato in classe l'obiettivo era fare in modo che due PC disposti su due reti diverse, si raggiungano via Ping(I due notebook sono stati configurati con la dhcp).
Il ping viene richiamato utilizzando il comando a riga di comando, in combinazione con l'indirizzo IP o il nome host del computer di destinazione, per determinare se un altro computer in una rete locale o pubblica collegata può essere raggiunto.
Se il router non risponde al ping effettuato si può intuire che il computer sia raggiungibile, ma che non risponde automaticamente alla richiesta a causa della sua configurazione.
Come output, il comando ping ci da delle informazioni:
Tempo di risposta in millisecondi (ms) e il periodo di validità dei pacchetti ICMP.

Un pacchetto ICMP (Internet Control Message Protocol) è un tipo di pacchetto di dati utilizzato per il controllo e la segnalazione degli errori nella comunicazione di rete, inoltre viene utilizzato dai dispositivi di rete come ad esempio i router per inviare segnalazioni di errore o messaggi di controllo ad altri dispositivi di rete.
I pacchetti ICMP contengono informazioni sullo stato e le condizioni di rete, inclusi messaggi di errore come "host irraggiungibile" o "timeout".

Il motivo per cui inizialmente non si riusciva a concludere l'esercizio è perchè i ping tra le reti diverse non avvenivano non avendo configurato l'ip del defaul gateway agli host.
                                     

