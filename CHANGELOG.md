# [1.1.0] - 11/03/2026
- Nuova colonna **"Estensione"** 
- Implementato sorting alfanumerico
- Rimossa estensione dai tag del file
- Cambiato nome colonna da **"Data Ultima Modifica"** a **"Data modifica"**
- Ridimensionata grandezza colonne
- Diminiuita grandezza del font nella colonna **"Percorso"**

# [1.1.1] - 12/03/2026
- Sorting customizzato per le colonne **"Data modifica"** e **"Dimensione"**
- Ottimizzazione codice per miglioramento prestazioni

# [1.2.0] - 13/03/2026
- Nuova label indicante la dimensione complessiva dei file visualizzati e di quelli totali
- Possibilità di aggiungere un font personalizzato inserendo la seguente proprietà nel file _style.json_ ed aggiungendo all'interno della cartella _resources_ un file con estensione _.ttf_ chiamato esattamente **font.ttf**
```
...
"font": "$resource",
...
```
- Risolto un bug che apriva il file errato e/o assegnava un tag errato dopo aver utilizzato il sort della tabella 
- Aggiunti controlli di validazione specifici all'inserimento del tag
- Cambiato formato visualizzazione di **Data modifica** da **dd/MM/yyyy - HH:mm** a **dd/MM/yyyy HH:mm**
- Aumentato effetto gradiente al backgrounds

# [1.2.1] - 13/03/2026
- Aggiornato testo della label di dimensione e numero file
- Ottimizzazione codice

# [1.3.0] - 03/04/2026
- Aggiunto tooltip sulle colonne **"Nome"** e **"Percorso"**
- Riorganizzata posizione colonne