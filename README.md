# urpojentaisto

VIRUSTORJUNTA SAATTAA HERJATA PELIÄ KÄYNNISTÄESSÄ. Tällöin aseta Urpojen Taisto.exe sallittujen sovellusten listalle, jos haluat pelata.

---URPOJEN TAISTO 1.0.0---
(c) Tuukka Jurvakainen / TuxuGames 2010 


Sisältö:
1. YLEISTÄ
   - 1.1. Tietoa pelistä
2. NÄPPÄIMET
   - 2.1. Normaalipelin näppäimet
   - 2.2. Urpo-pelin näppäimet
3. OHJEET OMAN KENTÄN TEKOON
   - 3.1. Normaalipelin kentän teko
   - 3.2. Urpo-pelin kentän teko
4. MUUTA


1.YLEISTÄ
--------------------

Urpojen Taisto on TuxuGamesin tuottama peli, jossa
on tarkoituksena tuhota vastustaja.
Tuhoaminen tapahtuu pommeilla ym. aseilla.

Tämä on pelin versio 1.0.0 Uudemmat versiot julkaistaan
TuxuGamesin kotisivuille, osoitteeseen:
http://koti.mbnet.fi/tuxu 
tai
tuxu.urli.net  


1.1 Tietoa pelistä
------------------------

Urpojen Taisto on ensisijaisesti kaksinpelattava peli.
Pelissä on kaksi eri pelityyppiä. Normaali ja Urpo.

Normaalissa pelityypissä taistellaan pienellä areenalla.
Normaalipelissä on mahdollisuus tavallisen kaksinpelin
sijaan pelata tietokonevastusta vastaan. Tällöin
kenttää valittaessa on valittava "Tietokone vs. Pelaaja".

Urpo-pelityypissä kentät ovat isommat ja niissä voi käyttää
erilaisia taisteluajoneuvoja (katapultti, ilmalaiva).
Urpo-pelissä ei ole tietokonevastusta. 

Molempiin pelityyppeihin on mahdollista tehdä omia kenttiä.
Lue lisää kohdasta kolme "OHJEET OMAN KENTÄN TEKOON"
  



2.NÄPPÄIMET
----------------------
Yleiset näppäimet:

Musiikki pois: M



2.1 Normaalipelin näppäimet
-----------------------------

Pelaaja1:

Ohjaus: sivunuolet
Hyppy: ylänuoli 
Pommi: . (piste)
Aseen vaihto: Enter

Pelaaja2:

Ohjaus: AD
Hyppy: W
Pommi: vasen ctrl
Aseen vaihto: Q


2.2. Urpo-pelin näppäimet
----------------------------------------

Pelaaja1:

Ohjaus: sivunuolet
Hyppy: ylänuoli 
Ilmalaivaan sisään: alanuoli
Pommi: . (piste)
Aseen vaihto ilmalaivassa: Enter


Katapultin liikutus: 
Alanuoli pohjaan katapultin kohdalla, liikuta sivunuolista

Katapultilla ampuminen:
Katapultin kohdalla paina  pommitusnäppäin pohjaan.
Silloin voimamittari alkaa latautua.
Kun voimaa on mielestäsi riittävästi, 
päästä näppäin pohjasta.



Pelaaja2:

Ohjaus: AD
Hyppy: W
Ilmalaivaan sisään: S
Pommi: vasen ctrl
Aseen vaihto ilmalaivassa: Q

Katapultin liikutus: 
S pohjaan katapultin kohdalla, liikuta A:sta ja D:stä

Katapultilla ampuminen:
Katapultin kohdalla paina  pommitusnäppäin pohjaan.
Silloin voimamittari alkaa latautua.
Kun voimaa on mielestäsi riittävästi, 
päästä näppäin pohjasta. 

-----------------------------------------------------



3.OHJEET OMAN KENTÄN TEKOON
--------------------------------------

Urpojen Taistoon on mahdollista tehdä omia kenttiä.
Tähän tarkoitukseen tarvitset vain piirto-ohjelman
(Paint käy hyvin) sekä Urpo-pelissä myös Notepadin
tai vastaavan tekstitiedoston teko-ohjelman.



3.1. Normaalipelin kentän teko
---------------------------------------

Nämä kentän teko-ohjeet toimivat 
Normaalipelityypin kenttiä tehdessä.

Piirrä piirto-ohjelmalla 800x600 kokoinen kuva.
Väritä tyhjäksi/ilmaksi haluamasi alueet MUSTALLA.
Tallenna kenttäsi KENTÄT-KANSIOON ja PNG-FORMAATISSA.
Nyt kenttäsi pitäisi toimia itse pelissä.



3.2. Urpo-pelin kentän teko
----------------------------------------

Piirrä piirto-ohjelmalla 1000x750 kokoinen kuva.
Väritä tyhjäksi/ilmaksi haluamasi alueet MUSTALLA.
Tallenna kenttäsi URPOKENTÄT-KANSIOON ja PNG-FORMAATISSA.

Luo sitten tekstitiedosto(.txt) vaikka Notepadilla.
Kirjoita sitten Notepadiin ukkojen, ilmalaivojen ja
katapulttien aloituskoordinaatit  näin:

810
300
120
300
jne.

Ensimmäinen koordinaatti ensimmäisellä rivillä, toinen toisella jne.
Tässä mitä mikäkin rivi tarkoittaa:

tykki1 x-sijainti
tykki1 y-sijainti
tykki2 x-sijainti
tykki2 y-sijainti
ilmalaiva1 x-sijainti
ilmalaiva1 y-sijainti
ilmalaiva2 x-sijainti
ilmalaiva2 y-sijainti
ukko1 x-sijainti
ukko1 y-sijainti
ukko2 x-sijainti
ukko2 y-sijainti

Tallenna tekstitiedosto(.txt) SAMALLA NIMELLÄ KUIN KENTTÄ
URPOKENTÄT-kansioon.

Nyt kenttäsi pitäisi toimia itse pelissä. Katso esimerkkiä valmis
kentistä.

------------------------------------------------------------------


4.MUUTA
----------------------------------------

Pelin lähdekoodin voit ladata TuxuGamesin kotisivuilta:
http://koti.mbnet.fi/tuxu 
tai
tuxu.urli.net  

Lähdekoodi, kuvat yms. vapaasti muokattavista/käytettävissä. 
Muista mainita aina tekijän nimi!(TuxuGames, tuxu.urli.net)
Jos aiot julkaista uuden, muokatun version Urpojen Taistosta, 
niin lähetä se tarkastettavaksi osoitteeseen tuxu@mbnet.fi. 
Peli tarkastetaan ja laitetaan ladattavaksi TuxuGamesin virallisille 
nettisivuille.
 
 
