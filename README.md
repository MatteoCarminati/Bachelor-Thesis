# ITALIANO
Il progetto di tesi, realizzato in collaborazione con un collega, consiste nello sviluppo di una serra completamente automatizzata realizzata attraverso il controllore Raspberry e una serie di sensori e di attuatori necessari per poter implementare le funzioni di misura e di controllo per il rilevamento dei parametri ambientali.
Con lo scopo di avere un accesso ai dati più gradevole il sistema Embedded è stato integrato con un'architettura Cloud e un’applicazione mobile ad essa collegata, la quale permette all’utente utilizzatore di consultare lo stato del sistema.
La prima è stata creata mediante i servizi di Amazon Web Services (AWS), per poter archiviare in remoto le informazioni della serra; la seconda, invece, è stata sviluppata sfruttando Flutter (framework open source di proprietà di Google), attraverso il linguaggio di programmazione Dart.
Il progetto di tesi è quindi suddivisibile in tre unità principali:
- il sistema Embedded, interamente dedicato al controllo di parametri ambientali e al funzionamento della serra stessa;
- l’architettura Cloud, usata per salvare nel Cloud i dati processati dalla scheda Raspberry;
- l’applicazione Mobile, utilizzata per monitorare il sistema da remoto e visualizzare lo stato dei parametri.

Nel file RelazioneTesi.pdf è contenuta la tesi di laurea che mostra nel dettaglio l'intero progetto.
Nella cartella "Codici" sono contenute le sotto-cartelle:
- "AWS" contenente i codici per l'aplicativo cloud realizzato sfruttando Amazon Web Service.
- "Sistema Embedded" contenente il codice relativo al controllo e alla gestione dell'intero embedded system.
Nella cartella "AppMobile" sono contenuti invece i codici relativi all'applicazone mobile dedicata.


# ENGLISH 
The thesis project, developed in collaboration with a colleague, involves the creation of a fully automated greenhouse using a Raspberry controller and a series of sensors and actuators necessary to implement measurements and control functions for environmental parameter detection. 
To enhance data accessibility, the Embedded system has been integrated with a Cloud architecture and a connected mobile application, allowing the end user to check the system's status.
The Cloud architecture, created using Amazon Web Services (AWS), stores greenhouse information remotely. 
The mobile application, developed using Flutter (an open-source framework owned by Google) and the Dart programming language, enables users to monitor the system and view parameter statuses.
The thesis project can be divided into three main units:
- The Embedded system, dedicated to controlling environmental parameters and the greenhouse's operation.
- The Cloud architecture, used to store processed data from the Raspberry board in the Cloud.
- The Mobile application, used to remotely monitor the system and visualize parameter statuses.

The thesis document itself is contained in the file "RelazioneTesi.pdf" (unfortunately it is written only in italian) providing a detailed overview of the entire project. 
Within the "Codici" folder, there are two subfolders:
- "AWS," which contains the codes for the cloud application developed using Amazon Web Services.
- "Sistema Embedded", containing the code related to the control and management of the embedded system.
In the "AppMobile" folder, you will find the codes related to the dedicated mobile application.