# Health Data Browser

Visual analytics tool for medical research teams

* To download large data sets by building a virtual data warehouse 

* From public health data repositories worldwide

* With an editable list of sources

* Acessed through standard web service protocols.

SourceForge site: http://healthdata.sourceforge.io

## Adatpumpa (ETL)
Az adatbusz nemzetközi szabványokra épülne, nyilvános ingyenes data martokra kapcsolódnánk, lenne a config oldalon 1 lista + hozzáadás gomb. Az orvosok közül a legokosabb (avagy a helyi IT arc) fölépítené fasza bonyolult query-jét a vizuális felületen, majd megnyomná a nagy piros gombot & akkor a szoftver le- & betöltene minden szükséges adatot, ez eltartana 1 darabig, utána mehetnének a többi doktorok & doktorinák a homokozóba játszani.

* Upstream: OLTP rendszerekből fölszívni az adatokat valamilyen tárházba. Nem vállalom!
* Midstream: fasza nemzetközi standard adatmodellek értelmezése, hogy le ne dobjon az adatbuszról a sofőr!
* Downstream: adat leszívása tárházakból valamilyen prezentáló cuccba. Ezt fogjuk csinálni, yeah!!!

## Adatmedence (Data Lake)
A big data ülepítőhelye valami nem túl bonyolult NoSQL cucc lenne (amúgy elsőre a Hadoop jutott eszembe) ahová XML adatfájlokat lehetne betölteni, hogy a bennük rejlő adatokat rá lehessen kapcsolni a query-gazda szemantikai modelljére - lásd rögtön alább! Nem akarok a big datára nagyon durván rámenni, mert sajnos csak 1 seggem van, ami tehát csak 1 lóra elegendő (avagy annak 1 bizonyos testrészére) de hogy menő legyek, azért gondoltam, ezt is ideírom.

## Prezentációs léjer
Open Source adatmodellező library: csillag, hópehely, galaxis, satöbbi yeah!!! Imádjuk.

* Csillag: tény-tábla + dimenzió-táblák
* Hópehely: tény-tábla + dimenzió-táblák re-normalizálva
* Galaxis: több tény-tábla, dimenzió-táblákon át lehet ugrálni köztük.

## Felhasználók
Túlképzett pályakezdő orvos-kutatók & egészségügyi szakemberek sok szabad idővel, csak épp kevés pénzzel. Keresik még nagyon a helyüket az orvos-világban, mint én az IT világban, összehordja a szemetet a szél. Szeretnék néhány ilyen embert bevonni, hogy ők béta-teszteljék majd a szotvert. Kevés feature lenne sok dokumentációval, vicces olvasmányos írások + 10-20 perces screencast videók is fölkerülnének a saját YouTube-csatornámra. Veszedelmesen profi jútyúb-influenszer vagyok, úgy vigyázz!!!

## Felhők
* Infrastruktúra a felhőben: virtuális gép készítése, hogy egyből 1 konténerbe be lehessen rakni.
* Platform a felhőben: valamelyik népszerű platformra installáló szkript
* Szoftverek a felhőben: Google Drive esetleg érdekelhet minket!

## Stack
Best of breed legyen, légyszi! Én szeretném összerakni FOS komponensekből, igen, imádom a fost. Free & open source, bocsi, csak vicceltem, na, vicceltem. Annyi, hogy nem valami milliárdos licenszű szuper integrált multi barbiházban szeretnék hülyéskedni, noha bár azt is ledokumentálhatnám gyönyörű screenshot-okkal & szépen csillogó UML diagramokkal, hogy a szakdoga meglegyen kettesre, de nem biztos, hogy egyrészt meglenne kettesre, másrészt az önbecsülésemet hogy nem rombolná le.
