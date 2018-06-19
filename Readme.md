Questo repository un'integrazione a:

https://github.com/pkp/omp/tree/master/locale/

della versione 3.1.1-1 di di Open Monograph Press ed è creato per fornire una traduzione italiana stabile e condivisa.

Changelog:

19/6/19: Allineati alla attuale distribuzione (3.1.1-1) di OMP i file: admin.xml, default.xml, editor.xml

15/6/18: Alla creazione il pacchetto è un collage di diverse traduzioni e adattamenti fatti fino alle release precedenti alla linea di versioni 3.0

-------------------------

Per installare questa traduzione:
1) scarica il pacchetto e scompattalo,

2) aggiungi la cartella it_IT alla installazione di OMP: *my_omp/locale*. 

3) aggiungi questa stringa al file: *registry/locale.xml*

		<locale key="it_IT" complete="false" name="Italiano" iso639-2b="ita" iso639-3="ita" />

4) accedi al tuo sistema come amministratore di sistema e vai alla pagina delle lingue;

5) seleziona la *checkbox* accanto alle impostazioni locali appena registrate in **Install New Locales** e fai clic su **Install**;

6) dopo il ricaricamento della pagina, seleziona la *checkbox* accanto alle impostazioni internazionali appena installate accanto a **Supported Locales** e fare clic su **Save**.

7) Sarà quindi necessario visitare casa editrice che si sta amministrando e attivare la lingua dalla pagina **Language** di **Journal / Conference Manager**. Puoi farlo selezionando la casella accanto a Localizzazioni supportate e facendo clic su Salva.

NB: visita la pagina delle informazioni di sistema (http: // <tuo-sito> /index.php/index/admin/systemInfo) e controlla la variabile "registry_dir" per assicurarti di modificare il locales.xml corretto

Reference

[https://pkp.sfu.ca/wiki/index.php?title=Translating_OxS](https://pkp.sfu.ca/wiki/index.php?title=Translating_OxS)
