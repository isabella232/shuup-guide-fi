Tilaukset
=========

Tilauksen luominen
~~~~~~~~~~~~~~~~~~

Tilaus voidaan luoda kahdella eri tavalla –- asiakkaan toimesta
verkkokaupassa tai kauppiaan toimesta Shuup hallintapaneelissa.

Luodaksesi tilauksen Shuup hallintapaneelissa:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset`
Shuup hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse `Uusi tilaus` `Tilaukset`-ylläpitosivun työkalupalkista.

   .. image:: orders/new-order.png

3. Siirry `Asiakkaan tiedot` –välilehdelle ja valitse
   `Valitse olemassa oleva asiakas` avataksesi asiakkaan
   valintaikkunan tai valitse `Uusi asiakas` luodaksesi uuden
   asiakkaan tilauksen luonnin yhteydessä.

   .. image:: orders/customer-details.png

   Syötä tarvittavat osoitetiedot.

4. Valitse `Tilauksen sisältö` –osiossa `Lisää uusi rivi`
   lisätäksesi tyhjiä tilausrivejä tilaukseen.

   Nämä voivat olla tyyppiä tuote, muu tai teksti/kommentti.

   Jos lisäät tuotetta, valitsemalla `Valitse tuote` saat näkyviin
   tuotteiden valintaikkunan.

   .. image:: orders/add-new-line.png

   Voit valita jonkun näistä rivityypeistä tilaukselle:

    Tuoterivi
        Tuote, määrä ja mitkä tahansa halutut hinta- ja alennustiedot
    Muu rivi
        Muu hinnoittelurivi
    Teksti-/kommenttirivi
        Ei-hinnoiteltu tekstirivi

5. Optionally, the `Quick add product line` form can be used to quickly
   add product lines to the order. For example, this can be used when
   adding products using a barcode scanning device.

   To quick add products:

   a. Enter a product name, sku, or barcode number and select desired
      product from the dropdown results.
   b. Press the plus button to add the product line to order, or press
      the trash button to clear the input and select a new product.

      .. image:: orders/quick-add.png

6. Valitse toimitus- ja maksutavat tilaukselle niille osoitetuista
   pudotusvalikoista

   .. image:: orders/shipping-and-payment-methods.png

7. Valitse `Jatka` luodaksesi tilauksen.

   .. image:: orders/proceed-button.png

.. note::
   Jokaiselle tilaukselle on valittava toimitus- ja maksutapa.

.. note::
   Toimitus- ja maksutapasäännöt, verot ja mahdolliset lisäalennukset
   lasketaan tilaukseen seuraavaan vaiheeseen edettäessä.


Tilauksen muokkaaminen
~~~~~~~~~~~~~~~~~~~~~~

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset` Shuup
   hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus jota haluat muokata.

   .. image:: orders/select-order.png

3. Valitse `Muokkaa tilausta` tilausten työkalupalkista.

   .. image:: orders/edit-order-button.png

4. Tee halutut muutokset tilauksen sisältöön samalla tavalla kuin
   `tilausta luodessa <Tilauksen luominen>`_.

   .. image:: orders/edit-order-contents.png

5. Valitse `Jatka` tallentaaksesi muutokset tilauksen sisällössä.

   .. image:: orders/proceed-button.png


Tilausten lähetykset
~~~~~~~~~~~~~~~~~~~~

Tilauksen lähetyksen luominen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Luodaksesi lähetyksen tilaukselle:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset` Shuup
   hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jolle haluat luoda lähetyksen.

   .. image:: orders/select-order.png

3. Valitse `Luo lähetys` tilausten työkalupalkista.

   .. image:: orders/create-shipment-dropdown.png

4. Valitse kullekin tuotteelle haluttu lähetykseen sisällytettävä
   määrä. Voit helposti asettaa kaikille tuotteille saman
   toimitettavan määrän valitsemalla `Aseta lähetys kaikille tuotteille`.

   .. image:: orders/create-shipment.png

5. Valitse tavarantoimittaja pudotusvalikosta.

   .. image:: orders/supplier.png

6. Valitse `Luo lähetys` luodaksesi lähetyksen.

Lähetysluettelon tulostaminen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Tulostaaksesi lähetysluettelon tilauksen lähetykselle:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset` Shuup
   hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jonka lähetysluettelon haluat tulostaa.

   .. image:: orders/select-order.png

3. Luo tilauksen lähetys, mikäli et ole näin jo tehnyt.

   Katso `Tilauksen lähetyksen luominen`_

4. Valitse `Tulosta` Tilaukset-ylläpitosivun työkalupalkista.

   .. image:: orders/print-button.png

5. Valitse `Hae lähetysluettelo` tilauksen lähetykselle, jonka
   haluat tulostaa (kullakin tilauksella tulee olemaan yksi
   mahdollinen valinta).

   .. image:: orders/get-delivery-slip.png

6. Siirryt nyt lähetysluettelon PDF-näkymään, jonka voit joko
   tulostaa tai tallentaa tietokoneellesi selaimesi valikosta.

   .. image:: orders/delivery-slip.png

Tilauksen maksut
~~~~~~~~~~~~~~~~

Tilauksen maksujen katselu
^^^^^^^^^^^^^^^^^^^^^^^^^^

Nähdäksesi kaikki tilaukseen liittyvät maksut:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset`
   Shuup hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, johon liittyvät maksut haluat nähdä.

   .. image:: orders/select-order.png

3. Valitse `Maksut`-välilehti sivun vasemman laidan valikosta.

   .. image:: orders/payments-tab.png

4. Saat näkyviin listan kaikista kyseiseen tilaukseen
   liittyvistä maksuista.

   .. image:: orders/payments.png

Tilauksen maksun luominen
^^^^^^^^^^^^^^^^^^^^^^^^^

Luodaksesi tilaukselle maksun:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset`
   Shuup hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jolle haluat luoda maksun.

   .. image:: orders/select-order.png

3. Valitse `Luo maksu` sivun työkalupalkista.

   .. image:: orders/create-payment-dropdown.png

4. Syötä maksettu summa kenttään `Maksun määrä` tai valitse
   `Hae jäljellä oleva summa`, jolloin puuttuva kokonaissumma
   annetaan automaattisesti.

   .. image:: orders/create-payment.png

5. Valitse `Luo maksu` luodaksesi maksun.

Order Refunds
~~~~~~~~~~~~~

.. note::

   Orders can only be refunded once at least one payment has been
   created for the order.

   However, refund amounts are not restricted by existing payment
   amounts, meaning it is possible to refund more than has been
   actually payed.

   If an order cannot be refunded, it will not be visible in the
   `Actions` dropdown menu.

.. note::

   Once a refund has been created, it will appear as a refund line
   in the `Order Contents` tab.

Creating a Partial Refund
*************************

To create a partial refund for a particular amount or to refund
particular order line amounts:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a refund.

   .. image:: orders/select-order.png

3. Click `Create Refund` in the `Actions` dropdown in the admin
   page's toolbar.

   .. image:: orders/create-refund-dropdown.png

4. To create a refund for a particular line, select the matching line
   number from the `Line number` dropdown field.

   .. image:: orders/refund-line-form.png

   When refunding a product line, a field will appear to enter the
   quantity, as well as whether to restock the refunded products.

   .. note::
      A separate refund line will be created if returning both a
      quanity and an amount for a particular line.

5. Click the `Add More Refunds` button to add additional refund forms.

   .. image:: orders/add-more-refunds-button.png

6. Click the `Create Refund` to add the entered refund amounts to the
   order.

Creating a Full Refund
**********************

To create a full refund for an order:

1. Navigate to the Orders admin page by clicking `Orders` under the
   `Orders` category from the Shuup Admin menu.

   .. image:: orders/orders-menu.png

2. Select the order for which you want to create a refund.

   .. image:: orders/select-order.png

3. Click `Create Refund` in the `Actions` dropdown in the admin
   page's toolbar.

   .. image:: orders/create-refund-dropdown.png


4. Click the `Refund Entire Order` button in the admin page's toolbar.

   .. image:: orders/refund-entire-order-button.png

5. Review the order and refund amount information. To restock returned
   products, make sure the `Restock products` checkbox is selected.

6. Click the `Confirm Refund` to create a refund in the full amount.

Tilauksen peruuttaminen
~~~~~~~~~~~~~~~~~~~~~~~

.. note::
   Vain maksamattomia ja ei-toimitettuja tilauksia voidaan peruuttaa.

   Jos tilaus on maksettu tai toimitettu kokonaan, `Peruuta tilaus`
   –painike ei ole käytössä, eikä tilausta ole mahdollista peruuttaa.


Peruuttaaksesi tilauksen:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset`
   Shuup hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jonka haluat peruuttaa.

   .. image:: orders/select-order.png

3. Valitse `Peruuta tilaus` sivun työkalupalkista.

   .. image:: orders/cancel-order-button.png

Tilaus merkitään nyt `peruutetuksi` tilausten ylläpidon listalla.

Tilauksen asettaminen käsitellyksi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Kun tilaus on lähetetty toimitettavaksi, se voidaan asettaa
käsitellyksi.

Asettaaksesi tilaus käsitellyksi:

1. Siirry Tilaukset-ylläpitosivulle valitsemalla `Tilaukset` Shuup
   hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jonka haluat asettaa käsitellyksi.

   .. image:: orders/select-order.png

3. Valitse `Aseta käsitellyksi` sivun työkalupalkista.

   .. image:: orders/set-complete-button.png

Tilaus on nyt asetettu `käsitellyksi`.

.. note::
   Jos tilausta ei voida asettaa käsitellyksi (kaikkia tuotteita ei
   ole lähetetty), `Aseta käsitellyksi` –painike ei ole käytössä,
   eikä tilausta ole mahdollista asettaa käsitellyksi.

Tilausvahvistuksen tulostaminen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Siirry Tilaukset-ylläpitosivulle valitsemalla
   `Tilaukset` Shuup hallintapaneelin valikossa.

   .. image:: orders/orders-menu.png

2. Valitse tilaus, jonka tilausvahvistuksen haluat tulostaa.

   .. image:: orders/select-order.png

3. Valitse `Tulosta` sivun työkalupalkista.

   .. image:: orders/print-button.png

4. Valitse `Hae tilausvahvistus` pudotusvalikosta.

   .. image:: orders/get-order-confirmation.png

5. Siirryt nyt tilausvahvistuksen PDF-näkymään, jonka voit joko
   tulostaa tai tallentaa tietokoneellesi selaimesi valikosta.

   .. image:: orders/order-confirmation.png
