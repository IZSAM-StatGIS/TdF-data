<img src="https://github.com/IZSAM-StatGIS/TdF-data/raw/main/loghi.png" alt="loghi"></img>
## Introduzione
L’Istituto Zooprofilattico Sperimentale dell’Abruzzo e del Molise “G. Caporale” fa parte del Gruppo di Lavoro che analizza i dati sulla mappatura della *Terra dei Fuochi*.

Il Ministro delle Politiche Agricole, Alimentari e Forestali, il Ministro dell’Ambiente e della Tutela del Territorio e del Mare e il Ministro della Salute, hanno firmato la Direttiva per lo svolgimento delle indagini tecniche per la mappatura dei terreni della Regione Campania destinati all’agricoltura, in ottemperanza al Decreto Legge del 10 Dicembre 2013 “Disposizioni urgenti dirette a fronteggiare emergenze ambientali e industriali ed a favorire lo sviluppo delle aree interessate”.

La mappatura, eseguita anche attraverso strumenti di telerilevamento, è finalizzata ad accertare l’eventuale esistenza di effetti contaminanti a causa di sversamenti e smaltimenti abusivi anche mediante combustione.

Le indagini sono state affidate al Consiglio per la Ricerca e la Sperimentazione in Agricoltura, l’Istituto Superiore per la Protezione e la Ricerca Ambientale, l’Istituto Superiore di Sanità e l’Agenzia Regionale per la Protezione Ambientale in Campania, che potranno avvalersi del Nucleo Operativo Ecologico dei Carabinieri, del Corpo Forestale dello Stato, del Comando Carabinieri Politiche Agricole e Alimentari e altri organi dello Stato.

La Direttiva prevede che dati e informazioni saranno condivisi dagli Enti coinvolti *“anche attraverso l’utilizzo della struttura informatica dell’Istituto Zooprofilattico Sperimentale dell'Abruzzo e del Molise per la raccolta delle informazioni, l’esecuzione delle procedure di classificazione e la registrazione dei terreni oggetto di indagine”* (Art. 1).

Oltre all’IZS dell’Abruzzo e del Molise, del gruppo di lavoro fanno parte rappresentanti di CREA, ISPRA, ISS, AGEA, Regione Campania, ARPAC, IZS del Mezzogiorno (Campania e Calabria) e Università degli Studi di Napoli Federico II.
</div>

## Contenuti
Questo repository raccoglie e mette a disposizione della cittadinanza (con licenza <a href="https://creativecommons.org/licenses/by/4.0/deed.it" target="_blank">CC-BY-4.0</a>) i dati prodotti dal Gruppo di Lavoro. 

### Particelle catastali classificate

Dataset geografico, disponibile in formato *GeoJSON* ed *ESRI Shapefile*, delle particelle catastali **classificate sulla base delle restrizioni ai fini dell'uso agricolo**.

https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/particelle_classificate.geojson<br/>
https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/particelle_classificate.zip

 |Nome colonna|Informazione contenuta|
 |------------|----------------------|
 |CODICE| Codice particella|
 |COMUNE| Comune in cui ricade la particella|
 |CL_USO_AGR| Classificazione ai fini dell'uso agrigolo|
 |CL_RISK| Classi di rischio presunta|
 |PRMB_SUOLO| Parametri borderline nel suolo|
 |PRMC_SUOLO| Parametri critici nel suolo|
 |RIFIUTI| Presenza di rifiuti|
 |COLTURE| Colture campionate|
 |PRESCR| Prescrizioni|
 |DECRETO| Riferimento normativo al Decreto|
 |IND_GEOMAG| Esito indagine geomagnetometrica|


 |Classe|Definizione|
 |------|-----------|
 |A| Terreni idonei alle produzioni agroalimentari|
 |A1| Terreni idonei alle produzioni agro-alimentari, previa rimozione dei rifiuti ed analisi delle aree di sedime|
 |B| Terreni con limitazione a determinate produzioni agroalimentari in determinate condizioni|
 |C| Terreni idonei alle produzioni non agroalimentari|
 |D| Terreni con divieto di produzioni agroalimentari e silvo pastorali| 
 |VALUTAZIONE SOSPESA |Valutazione sospesa|
 |-|Nessuna classificazione|
 
 *Prescrizioni*
|Prescrizione|Definizione|
|-------------------|-----------|
|r|Rimozione riufiuti e analisi delle aree di sedime|
|c|Certificazione per i prodotti agroalimentari attestante la conformità alla normativa vigente|
|a|Caratterizzazione ambientale ai sensi dell'art. 242 del D.Lgs 152/2006|
|m|Esecuzione di indagini supplementari (scavi, trincee) volte a confermare o meno la presenza di rifiuti interrati|
|p|Estensione delle indagini effettuate alle particelle confinanti|
|int-p|Interdizione al pascolo|
|int-f|Interdizione alle produzioni foraggere|
|int-20|Interdizione alla coltivazione della porzione di particella dei primi 20 metri a partire dal canale perimetrale della discarica fino alla messa in sicurezza delle discariche ai sensi del D.M. n. 169/2021|
 
*Parametri critici nel suolo*
|Nota|Definizione|
|-|--------------------------|
| * |Concentrazione inquinante di poco superiore alle CSC e probabilmente ascrivibile a fenomeni di inquinamento diffuso|
| ** |In applicazione del principio di precauzione è stata estesa a tutta la particella la classe più restrittiva|


### Comuni indagati
Dataset geografico, disponibile in formato *GeoJSON* ed *ESRI Shapefile*, con i limiti dei Comuni ricadenti nell'area di studio.

https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/comuni_indagati.geojson<br/>
https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/comuni_indagati.zip

### Risultati analisi campioni di suolo e vegetali
Dataset in formato *CSV*. 

https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/risultati_suolo.csv

https://github.com/IZSAM-StatGIS/TdF-data/blob/main/data/risultati_vegetali.csv


