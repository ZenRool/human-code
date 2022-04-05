7.
Scansionare un documento su più fogli fronte-retro\
# La pratica perduta\
Finalmente sono riuscito a ritrovare quella pratica che sembrava essere svanita nel nulla! Che poi, possibile che nel 2021 ci siano ancora così tanti fogli di carta in giro per l’ufficio?! Ora ci penso io: una bella scansione e l’archiviamo in formato digitale, così la prossima volta so già dove andare a cercarla! L’unica pecca è che lo scanner non ha il fronte-retro automatico e mi tocca farlo a mano. Va beh, poco male, almeno sono pochi fogli!


## PSEUDO CODICE\


action -Porto la pratica nella stanza dello scanner\
action -Accendo computer associato allo scanner\
action -Accendo lo scanner\
action -Apro il programma adibito alle scansioni\
\
se -Il computer non vede lo scanner\
    -action- Controllo che i cavi siano collegati\
    -action- Aggiorno i driver\
    -action- Riavvio il computer e lo scanner\
    -se- Da ancora problemi --> errore non posso finire esco dalla procedura\
\
--(punto di ritono 1)\
action -apro lo sportello dello scanner\
se -ci sta un altro foglio nello scanner\
    -action- tolgo il foglio\
    -action- archivio il foglio in una pila diversa a quella della pratica\
fine se\
action -prendo il foglio più in alto della pila della pratica\
action -appoggio il foglio nello scanner\
action -chiudo lo sportello dello scanner\ 
action -do il comando di scansione\
fino a quando finisce la scansione del foglio -se da errore --> esco dalla procedura\
se -il foglio ha un retro\
    -action -apro lo sportello dello scanner\
    -action -giro il foglio\
    -action -chiudo lo sportello dello scanner\
    -action -do il comando di scansione\
    -fino aquando finisce la scansione del foglio -se da errore --> esco dalla procedura\
fine se\
se la pratica ha ancora fogli\
    -torno -al punto di ritorno 1\
fine se\
action -apro lo sportello dello scanner\
action -tolgo il foglio\
action -spengo lo scanner\
action -salvo i fogli scansionati nel file "pratica.pdf"\
se -il computer non mi serve più\
    -spengo il computer

