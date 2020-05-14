# Focus Highlight #

* Autori: Takuya Nishimoto, Karl-Otto Rosenqvist
* Scarica la [versione stabile][2]
* Scarica la [versione in sviluppo][1]

Disegnando un rettangolo colorato, questo addon consente agli utenti
ipovedenti, educatori vedenti o agli sviluppatori di tenere traccia della
posizione dell'oggetto su cui si trova il navigatore ad oggetti, oppure
dell'oggetto che ha il focus.

Sono utilizzati i colori seguenti:

* Un rettangolo delimitato da una sottile linea verde tratteggiata e
  punteggiata indica che NVDA è in modalità navigazione e la posizione del
  navigatore ad oggetti.
* Un Rettangolo sottile rosso indica che NVDA è in modalità navigazione e
  questo è l'oggetto o il controllo  focalizzato.
* Un Rettangolo spesso rosso indica che ci si trova in modalità navigazione
  e questi sono il navigatore a oggetti e l'oggetto focalizzato, che si
  sovrappongono.
* Un rettangolo spesso e blu con linee punteggiate sta ad indicare che NVDA
  è in modalità focus, ossia che ciò che scriviamo viene visualizzato a
  schermo oppure il tasto premuto viene passato al controllo.

Per attivare il tracciamento degli oggetti, premere NVDA + Alt + P. Puoi
assegnare altri gesti usando la finestra di dialogo Gesti e tasti di
immissione. Funziona con NVDA 2018.3 o versioni successive. Altrimenti, è
necessario disabilitare o disinstallare l'addon stesso per far sì che gli
oggetti non vengano più tracciati.

Quando la categoria Focus Highlight è disponibile nella finestra
impostazioni di NVDA, è possibile utilizzare le voci seguenti:

* Rendi la modalità focus predefinita: questa casella di controllo è
  abilitata per impostazione predefinita. Quando è deselezionata, questo
  componente aggiuntivo si comporta come la versione 5.6 o versioni
  precedenti, ossia, se la modalità navigazione non è disponibile per
  un'app, viene mostrato il focus utilizzando il rettangolo rosso spesso.
* Focus in modalità focus, Focus in modalità navigazione, navigatore ad
  oggetti: Ognuno di questi gruppi contiene Colore, Spessore e Stile.

    * Colore: Questo campo editazione consente di digitare il codice colore
      HTML, ossia un numero esadecimale di sei cifre. Ad esempio, "ffffff" è
      bianco, "ff0000" è rosso e così via. Si noti che "000000" non può
      essere utilizzato.
    * Spessore: digitare un valore compreso tra 1 e 30 per modificare lo
      spessore della casella.
    * Stile: le opzioni sono Solido, Tratteggiato, Punto, tratteggiato-Punto
      e tratteggiato-Punto-punto.

* Ripristina impostazioni predefinite: questo pulsante consente di
  ripristinare le impostazioni ai valori predefiniti originali.

## Novità nella versione 6.3 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Risolto un problema per cui lo stile tratteggiato del focus (in modalità
  navigazione) e del navigatore a oggetti non possono cambiare.
* Risolto il problema per cui il pulsante "Annulla" del pannello
  impostazioni non funzionava dopo aver premuto il pulsante "Ripristina
  impostazioni predefinite".

## Novità nella versione 6.2. ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Ora puoi attivare e disattivare il tracciamento degli oggetti utilizzando
  NVDA + Alt + P. ha contribuito per questo Karl-Otto Rosenqvist 

## Novità nella versione 6.1 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Affrontato [il
  problema](https://github.com/nvdajp/focusHighlight/issues/14) con le
  ultime versioni in sviluppo di NVDA.
* è ora disponibile la categoria Focus Highlight nella finestra impostazioni
  di NVDA. Funziona dalla versione 2018.3 in poi.
* [Discussioni sulla personalizzazione dei
  colori](https://github.com/nvdajp/focusHighlight/issues/3)
* [discussioni su 'Rendere la modalità focus
  predefinita'](https://github.com/nvdajp/focusHighlight/issues/13)

## Novità nella versione 6.0. ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Affrontato [il
  problema](https://github.com/nvdajp/focusHighlight/issues/13) inerente la
  modalità navigazione.
* Da questa versione, se la modalità navigazione di NVDA non è disponibile
  per un'applicazione, viene sempre mostrato che NVDA è in modalità focus
  per l'applicazione, anziché utilizzare il rettangolo spesso rosso.
* Lo spessore della linea che rappresenta la modalità focus è stato
  dimezzato.

## Novità nella versione 5.6 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Sistemata la compatibilità con NVDA snapshot alpha-16682.

## Novità nella versione 5.5 ##

* Affronta il problema che si verifica con  NVDA 2018.4 e i webbrowser
  Firefox/Chrome.

## Novità nella versione 5.4 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Affronta [il problema](https://github.com/nvdajp/focusHighlight/issues/11)
  riguardante la compatibilità tra le versioni.

## Novità nella versione 5.3 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Affronta [il problema](https://github.com/nvdajp/focusHighlight/issues/10)
  che riguarda il browser Chrome e la  modalità riposo dell'applicazione

## Novità nella versione 5.2 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.

## Novità nella versione 5.1 ##

* Rimosso l'output del log di debug .

## Novità nella versione 5.0. ##

* Sono stati modificati gli indicatori della modalità focus e del navigatore
  ad oggetti.
* Sono supportati monitor multipli.
* Per la visualizzazione ora viene usata la tecnologia GDI Plus.

## Novità nella versione 4.0. ##

* Nasconde il rettangolo se l'applicazione corrente è in modalità riposo.

## Novità nella versione 3.0. ##

* Risolto un problema con le caselle combinate espanse.
* Risolto un problema con il gestore attività di Windows.
* Capacità di indicare la modalità focus.

## Novità nella versione 2.1 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.

## Novità nella versione 2.0 ##

* L'aiuto è disponibile dalla gestione componenti aggiuntivi di NVDA.

## Novità nella versione 1.1 ##

* Modificato il navigatore ad oggetti, da rettangolo a linea frastagliata.
* Risolto un problema con "ricarica plugin".

## Novità nella versione 1.0 ##

* In Internet Explorer 10 e in Skype su Windows 8, risolto un problema con
  il navigatore ad oggetti.
* Versione iniziale.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
