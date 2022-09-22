ES_002 VLAN

In questo esercizio abbiamo introdotto le VLAN su cisco packet tracer.
La struttura è composta da due switch di cui uno è collegato a 4 pc e l'altro è collegato a altri 2 pc e il primo switch.
Dallo switch abbiamo configurato le 2 VLAN asegnando il VID e il loro nome(10:robotici/20:informatici).
Abbiamo creato 2 file diversi perchè in uno usiamo il PORT ACCCES quindi si utilizzano 2 cavi(1 per ogni VLAN) per collegare i 2 switch mentre nel
TRUNK serve solo un cavo perchè attraverso quel cavo tutte le VLAN possono comunicarci attraverso.

Dopo aver configurato il tutto si va in simulazione; Apriamo il prompt di uno dei pc di una VLAN a scelta e con il comando (ping 192.168.1.255(indirizzo di broadcast)) noteremo che il pacchetto verrà inviato
a tutti i computer della stessa VLAN mentre se proviamo manualmente a inviare un pacchetto da un pc di una VLAN al pc di un'altra VLAN il pacchetto non verrà inviato perchè impossibile comunicare tra due VLAN diverse.
