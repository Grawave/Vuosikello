# Vuosikello
Vuosikello on työkalu, jonka avulla työntekijät näkevät ja hahmottavat vuoden aikataulun yhdellä silmäyksellä. Sovellus sisältää myös yksilönäkymän (kaikki yhden tapahtuman tiedot) ja kuukausinäkymän.

Vuosikello on kehitetty Kuntaliitolle. Tällä sivulla on toistaiseksi kuvausta vain yleisestä toiminnallisuudesta ja testauksesta.

Käyttöohjeet lötyvät [tästä](Dokumentaatio/ohjekirja.pdf)

### Toteutus
Vuosikello on toteutettuu Javalla. Graafinen käyttöliittymä on tehty Swing kirjasaton komponenteilla (tapahtumien paikat on kovakoodattu GroupLayoutiin).

Tapahtumat luetaan excel taulukosta käyttämällä [apache POI APIa](https://poi.apache.org/).

### Lyhyt kuvaus
Vuosinäkymässä on neljänlaisia tapahtumia, kahteen lehteen liittyviä julkaisupäivämääriä (musta ja oranssi), tärkeitä tapahtumia (sininen), tapahtumia (vihreä).Värimaailma on asiakkaan toiveiden mukainen.

Klikkaamalla tapahtumasta saa kaiken tapahtumaan liittyvän tiedon näkyviin. Klikkaamalla kuukauden nimestä pääsee kuukausinäkymään. Menusta voi vaihtaa vuotta.

![Näkymä] (Dokumentaatio/testiNakyma.png)
### Projektin tilanne
Projekti on vielä beta vaiheessa, kuukausinäkymä ja värimaailma ovat vielä työnalla.

