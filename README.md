# Struttura di un database.

## INFO
E' un modello di struttura di un database, nei dati sono presenti attributi, che sono:

 NOTNULL dove indichiamo che il dato deve essere per forza salvato, in caso di errore, ritorniamo alla situazione precedente.
 
 NULL dove indichiamo che il dato potrebbe avere il valore NULL e in questo caso il dato viene salvato ugualmente.

 DEFAULT dove indichiamo che se il dato non ha un valore, ne avrà uno di default,
 in questo caso l'ho usato nel chilometraggio, perchè se l auto è nuova avrà 0 km, e nella disponibilità perchè il valore sarà un valore booleano ( 0 o 1).

 AUTO INCREMENT dove indichiamo che per ogni dato inserito il valore aumenta di +1, in questo caso lo uso per ID in modo che ogni volta che un dato viene salvato, viene dato un valore all ID automaticamente. 

 I dati passati con:
 VARCHAR(N) lasciamo una piccola libertà sulla lunghezza della stringa, Il valore di N lo inseriamo noi in base alle esigenze. Esempio per la Marca o per il Nome, possiamo inseirire fino a 10 caratteri.

 DECIMAL(I,D) indichiamo un numero con I sono i numeri massimo totali, con D sono i numeri dopo la "," .

 YEARS indichiamo solamente l anno.

 DATETIME indichiamo anno-mese-giorni ore-minuti-secondi (YYYY-MM-GG HH:II:SS).

