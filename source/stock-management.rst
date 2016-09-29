
Varastonhallinta
================

Shuup-verkkokaupassa on sisäänrakennettu varastonhallintajärjestelmä.
Varastonhallintaa ei ole aktivoitu kaupan hallintapaneelissa
oletuksena, mutta kauppias voi aktivoida varastonhallinnan
muutamalla helpolla toimenpiteellä. Varastonhallinnan käyttöönotto
on ohjattu prosessi Shuup-kaupan hallintapaneelissa.

Koska kaikki tuotteet eivät aina ole varastoitavia (kuten
ladattavat tuotteet), on hyvä pitää mielessä, että voidakseen
hallita tuotevarastoa on sinne kuuluvat tuotteet ensin merkittävä
`Varastoiduksi`. Lisäksi, varaston aktivoiminen edellyttää, että
kauppaan on lisätty vähintään yksi `Toimittaja`. Varastoa voidaan
hallita hallintapaneelissa helposti minkä tahansa varastoidun tuotteen
kautta, tai siihen tarkoitetussa `Tuotteet / Varastonhallinta` –näkymässä.


Varastonhallinnan aktivointi
----------------------------

**Aseta toimittajan varasto varastoitu-tilaan näin:**

1. Kirjaudu Shuup-kauppasi hallintapaneeliin osoitteessa https://kauppasiurl.com/sa
2. Avaa hallintapaneelin valikko vasemmasta yläkulmasta
3. Valitse **Tuotteet / Toimittajat** ja avaa
   `Yksinkertainen toimittaja` –moduuli toimittajataulukosta
4. Rastita ruutu kohtaan `Varastoitu` ja valitse `Tallenna`.


.. tip::

    Shuupissa voidaan käyttää useita toimittajamoduuleita
    ja kullakin niistä voi olla oma varasto.

Tuotteen asettaminen varastoiduksi
----------------------------------

Seuraavaksi tulee määrittää, mitkä tuotteet ovat varastoitavia.
Valitse mitkä tuotteet haluat näkyviin varastossasi. Tuotteet
löydät hallintapaneelin valikosta kohdasta **Tuotteet / Tuotteet**

Avaa halutun tuotteen asetukset ja siirry vasemman laidan
valikosta välilehdelle **Lisätietoja**. Valitse kohdan
**Varasto** pudotusvalikosta `Varastoitu`.

.. tip::

    Tämä toimenpide aktivoi varastonhallinnan kyseiselle tuotteelle.
    Tästä eteenpäin tämän tuotteen varastoa voidaan hallita
`Varastonhallinnassa <Varastonhallinta>`_

Varaston hallinnointi
---------------------

Varaston hallinnointi Shuupissa on yksinkertaisen selkeää.
Varastoa voidaan hallita minkä tahansa yksittäisen tuotteen kautta
hallintapaneelin valikon kohdassa `Tuotteet` tai siihen erityisesti
suunnitellussa `Varastonhallinta`-näkymässä, joka löytyy myös
hallintapaneelin valikosta.

Varastonhallinta käyttäytyy molemmissa käyttötapauksissa samalla
tavalla riippumatta siitä, haluaako kauppias hallita vain yhden
tuotteen varastoa tai useampaa tuotevarastoa kerralla. Ainoa ero on se,
että `Varastonhallinta`-näkymässä kauppias näkee kaikki tuotteet
yhdellä listalla ja hallinnoida näiden varastoja. `Tuotteet`-valikon
näkymässä varastoa hallitaan kerrallaan yhden valitun tuotteen osalta.

Tällä tavoin varaston hallinta on helppoa, oli kauppias sitten halukas
muuttamaan varastoasetuksia selatessaan yksittäisiä tuotteita, tai
halutessaan lisätä useita tuotteita kerralla.

.. tip::

    Kun varastoa lisätään, tulisi aina lisätä tuotteelle tiedot
    myyntihinnasta kaupan valuutassa ja varastoon lisättävien tuotteiden
    määrä. Nämä tiedot vaikuttavat varastoraportteihin.


How to manage stock on a product
--------------------------------

1. Decide which products stock you want to manage, find the product in
   **Products**
2. Open up the product and scroll down for **Stock management** tab

.. tip::

    Ennen kuin siirryt hallinnoimaan tuotteen varastointia,
    varmista että molemmat, tuotteen toimittaja ja tuote, on
    asetuksissa merkitty varastoiduiksi.

**Lisää varastoon:** Syötä tuotteen ostohinta sekä kappalemäärä
ja valitse **Lisää varastoon**.

**Poista varastosta:** Syötä miinusmerkkinen arvo, joka vastaa
poistettavien tuotteiden määrää, syötä tuotteen ostohinta sekä
kappalemäärä ja valitse **Poista varastosta**.

.. tip::

    Varastosi fyysinen saldo, looginen saldo, arvo per yksikkö ja
    kokonaisarvo päivittyvät automaattisesti jokaisen varastoon
    lisäämisen ja varastosta poistamisen jälkeen.


How to manage stocks in general
-------------------------------

1. Siirry `Varastonhallintaan` kaupan hallintapaneelin valikossa
   kohdasta **Tuotteet / Varastonhallinta**.
2. Etsi tuotetta, jonka varastoinnin asetuksia haluat muuttaa.

.. tip::

    Ennen kuin siirryt hallinnoimaan tuotteen varastointia, varmista
    että molemmat, tuotteen toimittaja ja tuote, on asetuksissa
    merkitty varastoiduiksi.

**Lisää varastoon:** Syötä tuotteen ostohinta sekä kappalemäärä ja
valitse **Lisää varastoon**.

**Poista varastosta:** Syötä miinusmerkkinen arvo, joka vastaa
poistettavien tuotteiden määrää, syötä tuotteen ostohinta sekä
kappalemäärä ja valitse **Poista varastosta**.


.. tip::

    Varastosi fyysinen saldo, looginen saldo, arvo per yksikkö ja
    kokonaisarvo päivittyvät automaattisesti jokaisen varastoon
    lisäämisen ja varastosta poistamisen jälkeen.
