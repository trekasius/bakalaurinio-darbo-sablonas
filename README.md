# Baigiamojo darbo LaTeX šablonas

Čia yra neoficialus **VGTU Fundamentinių mokslų fakulteto Matematinės statistikos
katedros** baigiamųjų darbų LaTeX šablonas. Nors viršelis sudarytas bakalauriniam
darbui, bet šį šabloną galima nesunkiai perdaryti į magistrinį, kursinį arba kitą 
rašto darbą.


## Trumpai apie kai kurias technines detales

Baigiamojo darbo šablonas sudarytas LaTeX `article` klasės dokumento pagrindu 
ir, naudojant įvairius LaTeX paketus, pritaikytas tekstui lietuvių kalba:

  * `bd-sablonas.tex` failo koduotė UTF-8;
  * tekste naudojamas Latin Modern šriftas;
  * pirma pastraipos eilutė atitraukiama nuo krašto;
  * skaičiuose po kablelio nededamas tarpas;
  * po skyrių ir poskyrių numerių dedamas taškas;
  * sutvarkytas lentelių ir paveiksliukų numeravimas.

**Padaryti dar kai kurie dalykai:**

  * nustatytas pusantrinis tarpas tarp eilučių;
  * paraščių plotis keičiamas pagal poreikį;
  * į turinį įtraukiami nenumeruoti skyriai: *santrauka*, *įvadas*, *išvados* ir *literatūros sąrašas*;
  * išspręsta problema dėl paketo hyperref klaidos, kuri kyla dėl dviejų titulinių puslapių.

Darbo autorius, savaime aišku, turi nurodyti savo pavardę, darbo pavadinimą ir
visus kitus duomenis, kurie rašomi ant viršelio ir titulinio puslapio. Be to,
autoriaus vardas ir darbo pavadinimas įrašomi ir į PDF metaduomenis. Juos
nurodyti galima per paketo `hyperref` nustatymus. Universiteto herbas ant
viršelio ir kiti darbe naudojami paveiksliukai turi būti `/figures` kataloge.

Su standartiniu [MikTex](http://miktex.org/) `pdflatex` šį šabloną sukompiliuoja
be klaidų: ` 0 error(s), 0 warning(s), 0 overfull box(es), 0 underfull box(es)`

**Kai kurie dalykai nepadaryti:**

  * literatūros sąrašui sudaryti nenaudojamas BibTeX;
  * visas darbas ir jo priedai rašomi viename faile.


## Pabaigai 

Šis šablonas platinamas laisvai ir be jokių apribojimų, tačiau būtų malonu,
jeigu informuotumėte  autorių, kad jį kažkur naudojate.
