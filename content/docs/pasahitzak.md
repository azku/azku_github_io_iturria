---
title: Pasahitz kudeatzailea
type: docs
---

Konputagailuen munduan autentikazioa eta autorizazioaren kudeaketa landu beharreko gaia da erabiltzaile guztiontzat. Bide publikoetatik gidatzean ditzakegun seinaleak identifikatu behar diren bezala, inguru digitaletan aritzerakoan gutxieneko batzu egon beharko litzateela pentsatzen duen horietakoa naiz.

## Pasahitza - zaharra baina azkarra
Gure pasahitz maiteak ahanzturara bidaliko omen zituen mila eta bat alternatiba ikusi ditut urteetan.
Errealitatea da, gaur egun, 2025ean behitzat, pasahitzak direla webgune gehienetara sartzeko, gehiengoak erabiltzen duen autetikazio tresna.

## Ez errepikatu mesedez
Gero eta gehiago behartzen gaituzte erabiltzaileak pasahitzak konplexuak sortzera. Horrela, alfabetuko karaktereez aparte, zenbakiak eta karaktere ez alfanumerikoak sartzera behartzen gaituzte.
Pasahitz seguruak sortzea ideia hona da. Pashitz hauek gogoratzea zaila egiten zaigu ordea, eta honek pasahitzen berrerabilpenera eraman gaitzake. Alegia, pasahitz bera erabiltzera webgune ezberdinetan edo helburu desberdinetarako. Hau oso praktika kaxkarra da eta ekidin behar dugu.

## Pasahitz Kudeatzaileak
Beraz, gizakiontzak gogoratzeko pasahitz zailak eta asko sortu behar baditugu, nola gogoratuko ditugu?
Erantzuna: ez ditugu gogoratu behar, pasahitz kudeatzaile bat erabiltzea aitortzen da gaur egun praktika egokitzat.

## Zein ordea?
Hemen gusto eta kolore asko ditugu. Ni ez naiz produktu desberdinak baloratzera sartuko. Denean daude abantailak eta desabantailak, baita nik proposatuko dudanean: Unixetik datorre **pass** programa.

## Zer da pass?
Enkriptatzeko gpg programa erabiltzen duen kudeatzaile sinple bat da. Autentikazio helburu bakoitza fitxategi desberdin batean gordetze  du eta denak enkriptatu egiten ditu. Oinarrian GPG enkripzioa eta fitxategi sistema besterik ez ditu erabiltzen.

## Linux
GNU/Linux sistema eragileetan, ohikoa da sistemako paketeekin batera instalatzeko aukera izatea. Archlinuxen kasu partikularrean adibidez ``pacman -S pass`` bidez instalatzen da.
GPG instalatuta izateaz gain, gako publiko/pribatu pare bat sortu beharko dugu: ``gpg --expert --full-gen-key`` erabili daiteke horretarako. 
    Pass erabiltzen hasteko prest geundeke. Lehenengo pausoa gordailua hasieratzea litzateke. Edozein kasutan, [pass-en dokumentazioan](https://git.zx2c4.com/password-store/about/) oso ondo azaltzen da bere funtzionamendua.

### Emacs
Emacsek pass **Password-Store** modua dauka. Honek pass programa erabiltzen du eta bertako pasahitzak emacs bidez atzitzeko aukera eskaintzen du. Emcaseko Melpa pakeeten listan pass (Major mode for password-store.el) bezala agertzen da.

## Windowsen emandako pausoak

Windowsen ez dut lortu oraindik emacs bitartez erabiltzerik. Ala era badago pass-winmenu izeneko programa bat eta honek Windoseko menu bezala pasahitzak atzitzeko aukera ematen du.

Horretarako lehenik git instalatu eta errepositorioa inportatu beharko dugu. Nire kasuan, pass gordailua beste konputagailu batean sort
ua nuen eta horregaitik da inportazioa lehenengo pausoa.

Ondoren gpg4win instalatu eta gako pribatua inportatu. Beste konputagailuan gakoa exportatu behar izan dugu lehenik.

pass-winmenu jeitsi deskromprimitu eta dokumentuen direktoriora eraman. Guk gpg4win instalatu dugunez, pass-winmenu.yaml fitxategian ondorengo aldaketa egin behar da: ``gpg-path: 'gpg'``


