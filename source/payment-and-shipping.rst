Maksaminen ja toimitukset
=========================

Shuupissa maksu- ja toimitustapoihin liittyvät valinnat ovat
yhteydessä valikoituihin palveluntarjoajiin. Palveluntarjoajat
voivat olla Shuupin sisäänrakennettuja toimitus- ja maksutapoja
tai ulkopuolisia toimitus- ja maksutapoja, jotka voidaan liittää
Shuupiin liitännäisenä.

Palveluntarjoajat
~~~~~~~~~~~~~~~~~

Maksu- tai toimituspalvelun tarjoajan luominen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Siirry `Palveluntarjoajat`-ylläpitosivulle valitsemalla
   `Palveluntarjoajat` `Maksaminen ja toimitus` –kategoriasta
   Shuup hallintapaneelin valikossa.

   .. image:: payment-and-shipping/service-providers-menu.png

2. Valitse `Uusi palveluntarjoaja` `Palveluntarjoajat`
   -ylläpitosivun työkalupalkista.

   .. image:: payment-and-shipping/new-service-provider-button.png

3. Valitse palveluntarjoajan *Tyyppi* pudotusvalikosta.

   .. image:: payment-and-shipping/new-service-provider.png

   .. note::
      Osa palveluntarjoajaluokista edellyttää lisäkenttien täyttämistä.
      Kun valitset jonkun näistä luokista, vaaditut lisäkentät tulevat
      automaattisesti näkyviin.

4. Syötä `nimi`, `logo`, `käytössä`-status ja täytä mahdolliset lisäkentät.

   .. image:: payment-and-shipping/new-carrier.png

5. Valitse `Tallenna` vahvistaaksesi palveluntarjoajan luomisen.

6. Kun olet tallentanut, valitse `Luo maksutapa` tai `Luo toimitustapa`
   luodaksesi maksu- tai toimitustavan, joka on yhteydessä tähän
   maksupalvelun tarjoajaan.

   Katso `Maksutavan luominen`_ and `Toimitustavan luominen`_.

   .. image:: payment-and-shipping/create-payment-method.png

Maksutavat
~~~~~~~~~~

Maksutavan luominen
^^^^^^^^^^^^^^^^^^^

1. Siirry Maksutavat-ylläpitosivulle valitsemalla `Maksutavat`
   `Maksaminen ja toimitus` –kategorista Shuup hallintapaneelin
   valikossa.

   .. image:: payment-and-shipping/payment-methods-menu.png

2. Valitse `Uusi maksutapa` `Maksutavat`-ylläpitosivun työkalupalkista.

   .. image:: payment-and-shipping/new-payment-method-button.png

3. Valitse uusi maksupalveluntarjoaja `Maksupalvelun tarjoaja`
   -pudotusvalikosta sekä maksupalvelu `Palvelu`-pudotusvalikosta.

   .. image:: payment-and-shipping/select-payment-method-provider.png

4. Syötä kenttiin muut tiedot maksutavasta.

   .. image:: payment-and-shipping/new-payment-method.png

5. Valitse `Tallenna` vahvistaaksesi maksutavan luomisen.

Toimitustavat
~~~~~~~~~~~~~

Toimitustavan luominen
^^^^^^^^^^^^^^^^^^^^^^

1. Siirry Toimitustavat-ylläpitosivulle valitsemalla `Toimitustavat`
   `Maksaminen ja toimitus` –kategoriasta Shuup hallintapaneelin valikossa.

   .. image:: payment-and-shipping/shipping-methods-menu.png

2. Valitse `Uusi toimitustapa` `Toimitustavat`-ylläpitosivun työkalupalkista.

   .. image:: payment-and-shipping/new-shipping-method-button.png

3. Valitse toimituspalveluntarjoaja `Kuljetusliike`-pudotusvalikosta
   sekä haluttu toimituspalvelu `Palvelu`-pudotusvalikosta.

   .. image:: payment-and-shipping/select-shipping-method-provider.png

4. Syötä kenttiin muut tiedot toimitustavasta.

   .. image:: payment-and-shipping/new-shipping-method.png

5. Valitse `Tallenna` vahvistaaksesi toimitustavan luomisen.

Käyttäytymiskomponentit
~~~~~~~~~~~~~~~~~~~~~~~

Kun asiakas siirtyy kassalle, hänelle esitetään kaikki mahdolliset
maksutapavaihtoehdot tilauksen tekemiseen.

Se, mitä maksutapavaihtoehtoja tilauksen tekemiseen tarjotaan, riippuu
maksutavalle määritetystä käyttäytymisestä, joka koostuu
`käyttäytymiskomponenteista`.

Käyttäytymiskomponentit ovat pohjimmiltaan yksittäisiä komponentteja,
jotka yhteen laitettuna määrittävät:

1. Onko tietty maksutapa valittavissa tilaukselle vai ei
2. Kyseisen maksutavan kustannuksen, mikäli maksutapa on valittavissa

Shuup sisältää seuraavat peruskomponentit (käyttäytymiskomponentteja
voidaan lisätä myös lisäosina :ref:`Addons`):

Kiinteä kustannus
    Lisää kiinteä kustannus.
Häviävä kustannus
    Lisää kustannus, joka on voimassa vain tiettyyn tilauksen arvoon asti.
Painorajat
    Rajoita palvelun saatavuutta perustuen tuotteiden kokonaispainoon.
Painon mukaan määräytyvä hinnoittelu
    Lisää kustannus jos tuotteiden kokonaispaino osuu määrättyyn
    painohaarukkaan.

.. note::
   Jos tilaukselle on useita mahdollisia painon mukaan määräytyviä
   hintahaarukoita, valitaan niistä automaattisesti alin hinta.

Käyttäytymiskomponentin lisääminen toimitus- tai maksutapaan
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Siirry maksutapojen tai toimitustapojen ylläpitosivulle valitsemalla
   `Maksutavat tai Toimitustavat` `Maksaminen ja toimitus` –kategoriasta
   Shuup hallintapaneelin valikosta.

   .. image:: payment-and-shipping/payment-methods-menu.png

2. Valitse taulukosta se toimitus- tai maksutapa, johon haluat lisätä
   käyttäytymiskomponentteja.

   .. image:: payment-and-shipping/select-payment-method.png

3. Valitse `Käyttäytyminen`-välilehti vasemmanpuoleisesta valikosta.

   .. image:: payment-and-shipping/behavior-tab.png

4. Valitse käyttäytymiskomponentin tyyppi `Käyttäytymiskomponentin tyyppi`
   –pudotusvalikosta ja valitse `Lisää komponentti` lisätäksesi tyhjän
   lomakkeen valitulle käyttäytymiskomponentille.

   .. image:: payment-and-shipping/add-component.png

5. Syötä halutut asetukset uudelle käyttäytymiskomponentille ja toista
   tarvittaessa lisätäksesi lisää käyttäytymiskomponentteja.

6. Valitse `Tallenna` tallentaaksesi käyttäytymiskomponentin valitulle
   toimitus- tai maksutavalle.
