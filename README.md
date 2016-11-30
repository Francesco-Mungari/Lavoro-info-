Esercitazione Pratica 30 novembre 2016 - 3CI
Utilizzando le funzioni, implementare un servizio bancario che effettui le seguenti operazioni:
\n1.Prelievo
\n2.Versamento
\n3.Pagamento Bolletta
\n4.Visualizzazione saldo
\n5.Esci
All’avvio del programma il saldo è 1000.00 euro, e le 4 operazioni devono essere svolte nel
seguente modo:
E' presente un codice di riconoscimento che abilita l'accesso al menù. Tale codice è formato
da 4 cifre.
1.prelievo, passandogli il saldo deve mostrare i tagli del prelievo (20,50,100 euro), l’utente
sceglie e se l’importo è maggiore o uguale del saldo disponibile, verrà effettuata
l’operazione e il prelievo restituirà un intero con l’importo del prelievo (attenzione. se
l’importo è 0 significa che non si ha sufficiente credito)

2.Versamento, passandogli il saldo deve mostrare i tagli del versamento (come prima) e
restituire il valore scelto che incrementerà il saldo.

3.Pagamento della bolletta, passando il saldo, deve verificare che il pagamento non lo renda
negativo e restituire l’importo pagato o 0 in caso di credito insufficiente.

4.Restituisce il saldo disponibile.
