# Istakni fokus (Focus highlight) #

* Autori: Takuya Nishimoto, Karl-Otto Rosenqvist
* Preuzmi [stabilnu verziju][2]
* Preuzmi [razvojnu verziju][1]

Ovaj NVDA dodatak omogućuje slabovidnim korisnicima, slijepim učiteljima ili
razvojnim programerima praćenje navigacijskog objekta i fokusiranog
objekta/kontrole pomoću obojenog pravokutnika.

Dodatak koristi slijedeće boje:

* Pravokutnik sa zelenim tankim rubom, iscrtkan točkama i crticama – znači
  da se NVDA nalazi u modusu čitanja. Pravokutnik označava navigacijski
  objekt.
* Prvokutnik sa crvenim tankim rubom – znači da se NVDA nalazi u modusu
  čitanja. Pravokutnik označava fokusirani objekt/kontrolu.
* Prvokutnik sa crvenim debelim rubom – znači da se NVDA nalazi u modusu
  čitanja. Pravokutnik označava navigacijski objekt i objekta fokusa, koji
  se preklapaju.
* Prvokutnik s plavim iscrtkanim debelim rubom – znači da se NVDA nalazi u
  modusu fokusa, tipkanje se prosljeđuje u kontrolu.

Za uključivanje i isključivanje praćenja objekata, pritisni
NVDA+Alt+P. Dodatku je moguće dodijeliti druge geste u dijaloškom okviru
Ulazne geste. Napomena: dodatak radi s NVDA 2018.3 ili novijom verzijom. U
ostalim slučajevima treba isključiti ili deinstalirati dodatak, kako bi se
onemogućilo praćenja objekata.

Kad je kategorija „Istakni fokus” dostupna u dijaloškom okviru za NVDA
Postavke, moguće je koristiti sljedeće stavke.

* Odredi modus fokusa kao standardni: Potvrdni okvir je standardno
  uključen. Kad se isključi, ovaj se dodatak ponaša kao verzija 5.6 ili
  prethodne verzije, tj. ako za aplikaciju nije dostupan modus čitanja,
  fokus se prikazuje pomoću debelog crvenog pravokutnika.
* Fokus u modusu fokusa, Fokus u modusu čitanja, Navigacijski objekt – svaki
  od njih sadrži boju, debljinu i stil.

    * Boja: U ovom polju je moguće upisati HTML kod za boju kao
      šesteroznamenkasti (heksadecimalni) broj. Npr, „ffffff” je bijela,
      „ff0000” je crvena itd. Napomena: „000000” nije moguće koristiti.
    * Debljina: U ovom polju je moguće odrediti debljinu ruba
      pravokutnika. Moguće vrijednosti su 1 do 30.
    * Stil: Moguće vrijednosti su neisprekidano, iscrtkano, točkasto,
      točkasto sa crticom, dvotočkasto sa crticom.

* Vrati na zadano: Ovim gumbom se postavke resetiraju na izvorne
  vrijednosti.

## Promjene u verziji 6.3 ##

* Novi i ažurirani prijevodi.
* Riješen je problem s iscrtkanim stilovima za fokus (u modusu čitanja) i
  navigacijski objekt, koje nije bilo moguće promijeniti.
* Riješen je problem s gumbom „Odustani” na ploči s postavkama, koji nakon
  primjene gumba „Vrati na zadano” nije radio.

## Promjene u verziji 6.2 ##

* Novi i ažurirani prijevodi.
* Sad je moguće uključiti i isključiti praćenje objekata pomoću tipki
  NVDA+Alt+P. Ovo je razvio Karl-Otto Rosenqvist.

## Promjene u verziji 6.1 ##

* Novi i ažurirani prijevodi.
* Rješava [problem](https://github.com/nvdajp/focusHighlight/issues/14) u
  vezi sa zadnjom razvojnom verzijom NVDA čitača.
* Kategorija „Istakni fokus” je sada dostupna u dijaloškom okviru za NVDA
  Postavke. Radi samo s NVDA verzijom 2018.3 ili novijom.
* [Diskusija o prilagođavanju
  boja](https://github.com/nvdajp/focusHighlight/issues/3)
* [Diskusija o „Odredi modus fokusa kao
  standardni”](https://github.com/nvdajp/focusHighlight/issues/13)

## Promjene u verziji 6.0 ##

* Novi i ažurirani prijevodi.
* Rješava [problem](https://github.com/nvdajp/focusHighlight/issues/13) u
  vezi s modusom čitanja.
* U ovoj verziji je uvedeno sljedeće: ako modus čitanja za NVDA nije
  dostupan za aplikaciju, uvijek se pokazuje da je NVDA u modusu fokusiranja
  za aplikaciju, umjesto da se koristi crveni debeli pravokutnik.
* Debljina ruba koji predstavlja modus fokusiranja smanjena je na pola.

## Promjene u verziji 5.6 ##

* Novi i ažurirani prijevodi.
* Rješava problem kompatibilnosti s NVDA snimkom alfa-16682.

## Promjene u verziji 5.5 ##

* Rješava problem s NVDA 2018.4 i Firefox/Chrome web preglednicima.

## Promjene u verziji 5.4 ##

* Novi i ažurirani prijevodi.
* Rješava [problem](https://github.com/nvdajp/focusHighlight/issues/11) u
  vezi s kompatibilnosti verzija.

## Promjene u verziji 5.3 ##

* Novi i ažurirani prijevodi.
* Rješava [problem](https://github.com/nvdajp/focusHighlight/issues/10), u
  vezi s Chrome preglednikom i aplikacijskom modusu mirovanja.

## Promjene u verziji 5.2 ##

* Novi i ažurirani prijevodi.

## Promjene u verziji 5.1 ##

* Uklonjen je rezultat zapisa uklanjanja grešaka.

## Promjene u verziji 5.0 ##

* Indikatori za objekt navigacije i modus fokusa su promijenjeni.
* Podrška za višestruke monitore.
* Sada se koristi GDI plus tehnologija za crtanje.

## Promjene u verziji 4.0 ##

* Sakrij pravokutnik, ako je trenutna aplikacija u modusu mirovanja.

## Promjene u verziji 3.0 ##

* Ispravljena greška vezana uz prošireni odabirni okvir.
* Ispravljena greška vezana uz Windows Task Manager.
* Sposobnost da prepozna modus fokusiranja.

## Promjene u verziji 2.1 ##

* Novi i ažurirani prijevodi.

## Promjene u verziji 2.0 ##

* Pomoć dodatka dostupna je u upravljaču dodataka.

## Promjene u verziji 1.1 ##

* Rub pravokutnika navigacijskog objekta je promijenjen u nazubljeni oblik.
* Ispravljena greška kod ponovnog učitavanja dodataka.

## Promjene u verziji 1.0 ##

* U Internet Exploreru 10 i Skypeu na Windowsima 8, ispravljen je problem sa
  objektom navigatora.
* Prva verzija.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
