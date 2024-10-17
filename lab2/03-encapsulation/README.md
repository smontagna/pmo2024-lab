# Programmazione ad Oggetti - Laboratorio 02

#### Principio di incapsulamento

* Analizzare la classe `oop.lab02.encapsulation.Student`
* Si noti che:
    - I campi sono ora privati: un client della classe non sarà mai influenzato dalla modifica di meri aspetti implementativi
    - Sono stati introdotti dei selettori per ottenere le proprietà dell'oggetto: `getName()`, `getSurname()`, ...
* Si modifichino similmente le classi `Calculator` e `Smartphone` contenute nel package `oop.lab03.encapsulation`:
    - Si rendano privati tutti i campi
    - Si introducano selettori opportuni per recuperare o modificare le proprietà di interesse

#### Il metodo `toString()`

* Analizzare `AccountHolder` contenuta nel package `oop.lab03.bank`
* Modella un generico utilizzatore di conto bancario, identificato da un id
* È realizzata applicando i principi di incapsulamento e information hiding (che andranno applicati *sempre* d'ora in poi ad *ogni* classe che costruiremo).
* Si implementi il metodo `String toString()` lasciato incompleto (si ricordi che `String toString()` è il metodo convenzionalmente usato in Java per ottenere la rappresentazione testuale di un oggetto).

#### Costruzione di classi incapsulate

* Si completi la classe `SimpleBankAccount` seguendo le istruzioni riportate nei commenti della medesima
* Si testi l'implementazione utilizzando la classe `oop.lab02.bank.TestSimpleBankAccount`.
