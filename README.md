# ASDT
Two projects from asdt course, both are compressed files

1. first one has the different assignments from first weeks
2. second has the rat maze that needed to be edited

The program is now zipped in a week2_seuraava_taso, which has tasks untill 10 points.
The zip has the final version in "labyrintti3" and the previous stage tests are included also.

Kohdat jotka olen suorittanut arvosteltavasta tehtävästä 2 (WEEK2):

1) toimiva rinnakkainen prosessitoteutus missä rotat (lapsiprosessit) liikkuvat itsenäisesti labyrintissa, parent prosessi odottaa kaikkien rottien pääsemistä suuaukolle ja ohjelma poistuu
-testattavat asiat: useiden prosessien käsittely ja yksinkertainen jaetun muistin käyttäminen prosessien välillä tiedonvälittämisessä
(2p)

3) toimiva rinnakkainen säietoteutus missä rotat (tehdyt säikeet) liikkuvat itsenäisesti labyrintissa,, main() - säie odottaa kaikkien rottien pääsemistä suuaukolle ja ohjelma poistuu
-testattavat asiat: useiden säikeiden käsittely omassa ohjelmassa, huom! voinet yhtä hyvin käyttää tässä 1) tehtävän jaettua muistia yhden prosessin sisällä
(2p)

4) toimiva prosessien välinen jaetun muistin toteutus labyrintin kokoiselle rottien sijaintikartalle (esimerkiksi labyrinttia vastaava kaksi-ulotteinen C-kielen taulukko mihin rotta merkitsee sijaintinsa) joka pysyy koko ajan hallitusti ajantasaisena, toteuta siis eksklusiivinen kirjoitus
-testattavat asiat: prosessien välinen writer-synkronointi semaforia käyttäen
(2p)

5) toimiva säikeiden välinen toteutus labyrintin kokoiselle rottien sijaintikartalle joka pysyy koko ajan ajantasaisena, toteuta eksklusiivisuus
-testattavat asiat: säikeiden välinen eksklusiivisuus
(2p)

6) toimiva prosessien systeemin suspend-toiminnalisuus jäädytetyn labyrinttitilanteen talteenottamista varten
-testattavat asiat: edistyneempi prosessien hallinta
(2p)

7) toimiva säikeiden suspend-toiminnallisuus (et voi käyttää ainkaan signaaleja säikeiden kanssa!) - main() säie siis toimii kuin parent prosessi edellä, toteuta säikeiden käsittelymenetelmillä
-testattavat asiat: edistyneempi säikeiden hallinta ja mutex/cond_variable käyttö
(2p)

8) toimiva FIFO rajattu rengaspuskuri (bounder buffer) joidenkin prosessien välillä: keksi itse miten sitä käytät ohjelmassa, esim parent voisi kirjoittaa jotain viestejä (=producer) kelle tahansa rotalle (=consumer) aika ajoin - viesteille voi keksiä hyödyntämiskeinon tai sitten ei, tämä ei ole onnaista tehtävässä, tässä tietenkin taas käytettävä jaettua muistia puskurille
-testattavat asiat: rajatun puskurin käyttö prosessien välillä (synkronointi)
(1p)

9) toimiva FIFO rengaspuskuri (bounded buffer) säikeiden välillä: kuten yllä mutta säikeiden tapauksessa
-testattavat asiat: bounder buffer säikeillä (synkronointi)
(1p)
