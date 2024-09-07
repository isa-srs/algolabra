# Määrittelydokumentti

Harjoitustyön aiheena on Connect Four -peli. Aiheen ydin on tekoäly, jota vastaan pelaaja pelaa. Tekoäly etsii kullakin kierroksella siirron, joka sillä hetkellä veisi tietokoneen lähimmäksi mahdollista voittoa. 

## Projektin toteutus

Ohjelmointikielenä on Python. Vertaisarvioin mielellään vain Python-töitä. Dokumentaation kieli on suomi, mutta voin vertaisarvioida myös englanninkielisiä projekteja.

Pelissä tulen toteuttamaan [minimax-algoritmin](https://en.wikipedia.org/wiki/Minimax) ja [alfa-beta-karsinnan](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning) sekä hyödynnän sanakirjaa tietorakenteena.

Ratkaistava ongelma on suotuisimman siirron löytäminen ja mahdollisimman nopeasti. Pelaaja tekee omat siirtonsa ja tekoäly etsii jokaisella kierroksella mahdollisimman hyvän siirron päihittääkseen pelaajan.

Minimax-algoritmin aikavaativuus on O(b^d) ja tilavaativuus O(b*d), missä d on eteenpäin katsottavien vuorojen määrä ja b on mahdollisten siirtojen määrä yhdellä vuorolla.

**Opinto-ohjelma:** Tietojenkäsittelytieteen kandidaatti