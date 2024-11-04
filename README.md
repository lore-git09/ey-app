# ey-app 

Descrizione dell' app 

esercizio per il coloquoi con lazienda ey 
1. Configurazione dell'ambiente di sviluppo: Ide Java, come Eclipse o IntelliJ. 
2. Creazione di un progetto Spring Boot
3. Implementazione dell'entità:
Creare le seguenti classe Java che rappresentano 
l'oggetto Persona , aventi i seguenti campi : id, nome , cognome , codice fiscale, dataNascita 
l’oggetto Residenza aventi i seguenti campi : id, indirizzo,cap, città, id_anagrafica 
Per la creazione degli oggetti usare le annotazioni di JPA (@Entity, @Id, etc.) necessarie per indicare che queste classi saranno gestite da dei repository 
Per la tabella Residenza deve esserci Il vincolo che la colonna id_anagrafica sia contenuto nella colonna id della tabella Persona 
4. Creazione dei repository:
Creare le interfaccia che estendono JpaRepository per gestire l'accesso ai dati delle entità (PersonaRepository, ResidenzaRepository ). 
5. Creazione dei seguenti endpoint: 
controller che recupera la lista delle persone presenti nel db 
controller che aggiunge l’indirizzo per un Persona presente nel DB 
controller per modificare l’indirizzo per una Persona presente nel 
DB 
controller per cancellare una Persona nel DB 
controller per che dato un indirizzo restituisca la lista delle 
persone che vivono presso un certo indirizzo 
Utilizzare i metodi di PersonaRepository, ResidenzaRepository per interagire con il database. 
Per la creazione del DB e l’impostazione della connessione usare una DB in memory H2 https://www.baeldung.com/spring-boot-h2-database 
6. Testare le diverse funzionalità attraverso Postman.
7. Opzionale Implementa la gestione degli errori e la validazione dei dati 
di ingresso
8. Creazione di un applicazione Angular che interagisca con il BE implementato 
sopra :
per ciascun endpoint predisporre l’analoga funzionalità frontend che 
richiami i servizi dall’1 all 5. 

