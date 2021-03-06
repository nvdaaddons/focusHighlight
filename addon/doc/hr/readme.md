# oznaka fokusa / focus highlight #

* Autor: Takuya Nishimoto
* Preuzmite [stabilnu inačicu][2]
* preuzmite [Razvojnu inačicu][1]

Ovaj dodatak omogućuje slabovidnim korisnicima, učiteljima bez problema sa
vidom, ili razvojnim programerima praćenje objekta navigatora NVDA i
fokusiranog objekta/kontrole uz pomoć nacrtanog obojenog pravokutnika.

The following colors are used by this addon:

* Green thin dashed-dotted line rectangle shows NVDA is in browse mode, and
  this is the navigator object.
* Red thin rectangle shows NVDA is in browse mode, and this is the focused
  object/control.
* Red thick rectangle shows NVDA is in browse mode, and this is both the
  navigator object and the focused object which are overlapping.
* Blue thick dotted line rectangle indicates NVDA is in focus mode, i.e.,
  key types are passed to the control.

Da biste onemogućili pračenje objekata, uklonite dodatak.

## Changes for 6.0 ##

* Novi i ažurirani prijevodi.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/13)
  regarding the browse mode.
* Since this version, if the browse mode of NVDA is not available for an
  application, it is always shown that NVDA is in focus mode for the
  application, rather than using the red thick rectangle.
* The thickness of the line representing the focus mode has been reduced to
  half.

## Changes for 5.6 ##

* Novi i ažurirani prijevodi.
* Addresses the compatibility issue with NVDA snapshot alpha-16682.

## Changes for 5.5 ##

* Addresses the issue with NVDA 2018.4 and Firefox/Chrome web browsers.

## Changes for 5.4 ##

* Novi i ažurirani prijevodi.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/11)
  regarding version compatibility.

## Changes for 5.3 ##

* Novi i ažurirani prijevodi.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/10)
  regarding Chrome browser and application sleep mode.

## Changes for 5.2 ##

* Novi i ažurirani prijevodi.

## Changes for 5.1 ##

* Removed debug log output.

## Changes for 5.0 ##

* Indicators of navigator object and focus mode were changed.
* Podržano je više zaslona.
* Sada se koristi GDI plus tehnologija za crtanje.

## Changes for 4.0 ##

* Sakrij pravokutnik ako je trenutna aplikacija u režimu spavanja.

## Changes for 3.0 ##

* Ispravljena greška vezana uz prošireni odabirni okvir.
* Fixed issue with Windows Task Manager.
* Sposobnost da prepozna režim fokusiranja.

## Changes for 2.1 ##

* Novi i ažurirani prijevodi.

## Izmjene u inačici 2.0 ##

* Pomoč dodatka dostupna je u upravitelju dodataka.

## izmjene u inačici 1.1 ##

* Izmjenjen pravokutnik objekta navigatora u nazubljenu liniju.
* Ispravljena greška kod ponovnog učitavanja dodataka.

## Promjene u inačici  1.0 ##

* U Internet Exploreru 10 i Skypeu na Windowsima 8, ispravljen je problem sa
  objektom navigatora.
* Prva inačica.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
