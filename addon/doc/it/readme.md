# Focus Highlight #

* Autori: Takuya Nishimoto, Karl-Otto Rosenqvist
* Scarica la [versione stabile][2]
* Scarica la [versione in sviluppo][1]

Disegnando un rettangolo colorato, questo addon consente agli utenti
ipovedenti, educatori vedenti o agli sviluppatori di tenere traccia della
posizione dell'oggetto su cui si trova il navigatore ad oggetti, oppure
dell'oggetto che ha il focus.

Sono utilizzati i colori seguenti:

* Un rettangolo formato da sottili linee verdi tratteggiate e punteggiate,
  per indicare che NVDA è in modalità navigazione e la posizione del
  navigatore ad oggetti
* Un Rettangolo sottile rosso indica che NVDA è in modalità navigazione,
  questo è l'oggetto o il controllo  focalizzato.
* Un Rettangolo spesso rosso, per indicare che ci si trova in modalità
  navigazione e il navigatore di oggetti e l'oggetto mirato si
  sovrappongono.
* Un rettangolo spesso e blu con linee sottili e punteggiate sta ad indicare
  che NVDA è in modalità focus, ad esempio ciò che scriviamo viene
  visualizzato a schermo oppure il tasto premuto viene passato al controllo.

Per attivare il rilevamento degli oggetti, premere NVDA + Alt + P. Puoi
assegnare altri gesti usando la finestra di dialogo Gesti e tasti di
immissione. Funziona con NVDA 2018.3 o versioni successive. Altrimenti, è
necessario disabilitare o disinstallare l'addon stesso per far sì che gli
oggetti non vengano più tracciati.

è possibile utilizzare le voci seguenti se la categoria Focus Highlight è
disponibile:

* Rendi la modalità focus predefinita: questa casella di controllo è
  abilitata per impostazione predefinita. Quando è deselezionato, questo
  componente aggiuntivo si comporta come la versione 5.6 o versioni
  precedenti, ovvero, se la modalità di navigazione non è disponibile per
  un'app, lo stato attivo viene mostrato utilizzando il rettangolo rosso
  spesso.
* Focus in modalità focus, Focus in modalità navigazione, navigatore ad
  oggetti Ognuno di questi gruppi contiene Colore, Spessore e Stile.

    * Colore: Questo campo di testo consente di digitare il codice colore
      HTML, ovvero un numero esadecimale di sei caratteri. Ad esempio,
      "ffffff" è bianco, "ff0000" è rosso e così via. Si noti che "000000"
      non può essere utilizzato.
    * Spessore: digitare un valore compreso tra 1 e 30 per modificare lo
      spessore della casella.
    * Stile: le opzioni sono Solido, Tratteggiato, Punto, Punto tratteggiato
      e Punto-punto.

* Ripristina impostazioni predefinite: questo pulsante consente di
  ripristinare le impostazioni sui valori predefiniti originali.

## Cambiamenti per la 6.3. ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Fixed the issue that dash styles of focus (in browse mode) and navigator
  object are not able to change.
* Risolto il problema per cui il pulsante "Annulla" del pannello
  impostazioni non funzionava dopo aver premuto il pulsante "Ripristina
  impostazioni predefinite".

## Cambiamenti per la 6.2. ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Ora puoi attivare e disattivare il tracciamento degli oggetti utilizzando
  NVDA + Alt + P. ha contribuito per questo Karl-Otto Rosenqvist 

## Cambiamenti per la 6.1 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Risolto [il bug](https://github.com/nvdajp/focusHighlight/issues/14) with
  the latest development versions of NVDA.
* è ora disponibile la categoria Focus Highlight nelle impostazioni di
  NVDA. Funziona dalla versione 2018.3 in poi
* [Discussioni sulla personalizzazione dei
  colori](https://github.com/nvdajp/focusHighlight/issues/3)
* [discussioni su 'Rendere la modalità focus
  predefinita'](https://github.com/nvdajp/focusHighlight/issues/13)

## Cambiamenti per la 6.0. ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Risolto [il bug](https://github.com/nvdajp/focusHighlight/issues/13)
  inerente la modalità navigazione.
* Da questa versione, se la modalità navigazione di NVDA non è disponibile
  per un'applicazione, viene sempre mostrato che NVDA è in modalità focus
  per l'applicazione, anziché utilizzare il rettangolo spesso rosso.
* Lo spessore della linea che rappresenta la modalità focus è stato
  dimezzato.

## Cambiamenti per 5.6 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Sistemata la compatibilità con NVDA snapshot alpha-16682.

## Changes for 5.5 ##

* Addresses the issue with NVDA 2018.4 and Firefox/Chrome web browsers.

## Changes for 5.4 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/11)
  regarding version compatibility.

## Changes for 5.3 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/10)
  regarding Chrome browser and application sleep mode.

## Changes for 5.2 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.

## Changes for 5.1 ##

* Removed debug log output.

## Cambiamenti per la 5.0. ##

* Sono stati modificati gli indicatori della modalità focus e del navigatore
  ad oggetti.
* Sono supportati monitor multipli
* Per la visualizzazione ora viene usata la tecnologia GDI Plus.

## Cambiamenti per la 4.0. ##

* Nasconde il rettangolo se l'applicazione corrente è in modalità riposo.

## Cambiamenti per la 3.0. ##

* Risolto un problema con le caselle combinate espanse.
* Risolto un problema con il gestore attività di Windows.
* Capacità di indicare la modalità focus.

## Cambiamenti per la 2.1 ##

* Nuove Traduzioni e aggiornamenti di quelle esistenti.

## Cambiamenti per la 2.0 ##

* L'aiuto è disponibile dalla gestione componenti aggiuntivi di NVDA.

## Cambiamenti per la 1.1 ##

* Modificato il navigatore ad oggetti, da rettangolo a linea frastagliata.
* Risolto un problema con il caricamento dei plugin.

## Cambiamenti per la 1.0 ##

* In Internet Explorer 10 e in Skype su Windows 8, risolto un problema con
  il navigatore ad oggetti.
* Versione iniziale.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
