# Porovaaka 1.8.2 – Windows-asennus

**[Lataa asennuspaketti (ZIP)](https://github.com/paliskuntainyhdistys/Porovaaka/releases/download/v1.8.2-painorajat-20261103/Porovaaka-1.8.2-Windows-x64.zip)**

Windows 10/11, Intel/AMD x64. Suomenkielinen aloitusohje toimii myös ilman internetiä.

**Päivitetty 3.11.2026:** painovaroituksen rajat ovat nyt **10–100 kg**.
Jos asensit jo 1.8.2:n, suorita tämä päivitetty asennusohjelma sen päälle.
Versionumero pysyy 1.8.2:ssa, ja punnitukset sekä asetukset säilyvät.

1. Lataa ZIP yllä olevasta linkistä.
2. Napsauta ladattua tiedostoa hiiren oikealla painikkeella: **Pura kaikki… → Pura**.
3. Avaa puretusta kansiosta **ALOITA-TASTA.html**.
4. Valitse ohjeesta **Asennan ensimmäistä kertaa** tai **Porovaaka on jo asennettu**.
   Ohje kertoo, mitä avataan ja missä järjestyksessä.
5. Jätä asennuksessa **Luo Porovaaka-pikakuvake työpöydälle** valituksi.
   Käynnistä ohjelma jatkossa työpöydän vihreästä Porovaaka-kuvakkeesta.

Puretun kansion ensimmäisellä tasolla on vain kolme kohdetta:

| Tiedosto tai kansio | Käyttötarkoitus |
|---|---|
| **ALOITA-TASTA.html** | Avaa ensin. Asennusohje avautuu selaimessa. |
| **Porovaaka-Setup-1.8.2.exe** | Asennusohjelma, joka avataan ohjeen vaiheessa 2. |
| **Lisatiedostot** | Aloitusasetukset, lisäohjeet, ajurit ja teknisen tuen tiedot. |

Ensiasennuksen asetustiedosto on **Lisatiedostot → Aloitusasetukset** -kansiossa.
Se tuodaan Porovaakan sisältä ennen ensimmäisen erän luomista. Päivityksessä
asetuksia ei tuoda uudelleen; ota ensin varmuuskopio, sulje Porovaaka ja suorita
asennusohjelma samalla Windows-tilillä. Punnitukset ja asetukset säilyvät.

## Uutta versiossa 1.8.2 (3.11.2026)

- **Painovaroitus** näkyy alle 10 kg:n ja yli 100 kg:n painoille molemmissa
  punnitusnäkymissä. Tasan 10 kg ja 100 kg eivät anna varoitusta. Positiivisen
  painon voi tallentaa varoituksesta huolimatta.
- **Nopeampi tallennus** palauttaa kohdistuksen Pilttanumeroon onnistuneen
  tietokantatallennuksen jälkeen. Punnitustaulukkoa ja Keskittymistilaa päivitetään
  kevyemmin myös historian kasvaessa.
- **Varmuuskopiointi taustalla**: erillinen varmuuskopio voi olla hetken jäljessä
  jo tallennetuista punnituksista. Häiriöstä näkyy pysyvä ilmoitus, ja ohjelma
  yrittää uudelleen. Suljettaessa ohjelma odottaa viimeisintä varmuuskopiota.
- **Sisäelimet**-painike on suoraan Vie Lukuporo-tiedosto- ja Lähetyslista-painikkeiden
  vieressä. Piltta-/painohaku vie vähemmän tilaa.
- Uuden erän **Punnituspäivä** ja **Teurastuspäivä** ovat erilliset päivämäärät.
  Molemmat näkyvät Lähetyslistan Teurastamo-osassa Punnituserän ja Ruhon lämpötilan
  välissä, myös PDF:ssä ja Excelissä. Vanhan puuttuvan teurastuspäivän kohdalla
  lukee **Ei tallennettu**.


[Erillinen asennusohjelma](https://github.com/paliskuntainyhdistys/Porovaaka/releases/download/v1.8.2-painorajat-20261103/Porovaaka-Setup-1.8.2.exe)
ja [SHA-256-tarkistussummat](https://github.com/paliskuntainyhdistys/Porovaaka/releases/download/v1.8.2-painorajat-20261103/SHA256SUMS.txt)
ovat saatavilla myös erikseen.

## Aiemmat versiot

[Alkuperäinen 1.8.2-paketti](https://github.com/paliskuntainyhdistys/Porovaaka/releases/tag/v1.8.2)
säilyy saatavilla.

[Porovaaka 1.8.1](https://github.com/paliskuntainyhdistys/Porovaaka/releases/tag/v1.8.1)
ja sitä vanhemmat julkaisut säilyvät [julkaisuhistoriassa](https://github.com/paliskuntainyhdistys/Porovaaka/releases).

Versio 1.8.2 päivittää tietokannan ja varmistaa automaattisen varmuuskopion ennen
muutosta. **Paluu versioon 1.8.1 edellyttää ennen päivitystä otetun varmuuskopion
palauttamista.** Päivityksen jälkeiset punnitukset eivät sisälly tähän varmuuskopioon.
