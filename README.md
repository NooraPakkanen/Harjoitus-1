# Debianin asentaminen virtuaaliboxiin

Tein harjoituksen 18.1.2023 ja jatkoin hieman vielä seuraavanakin päivänä 19.1.2023.

Aloitin harjoituksen lataamalla Debian iso tiedoston nettisivuilta (https://cdimage.debian.org/images/unofficial/non-free/images-including-firmware/current-live/amd64/iso-hybrid/). Latasin sivulta tiedoston debian-live-11.6.0-amd64-xfce+nonfree.iso. Tiedosto latautui ongelmitta. 

Seuraavaksi asensin virtualboxin osoitteesta https://www.virtualbox.org/wiki/Downloads. Latasin  VirtualBox 7.0.6 platform packages  version macOs Intel hosts. Käyttöjärjestelmänä minulla on macOs. Virtualbox latautui ongelmitta.

Seuraavaksi yritin asentaa virtuaalikonetta virtualboxissa. Tämä olikin kohta, johon sitten jumiuduin, enkä lopulta päässyt eteenpäin tehtävissä. Yritin luoda ohjeiden (Tero Karvinen 2023) mukaan  virtuaalikonetta ja laitoin kuvissa 1,2 ja 3 näkyviä asetuksia virtuaalikoneelle. 

Kun lopuksi yritin luoda koneen, sain kuvassa 4 olevan ilmoituksen, jonka mukaan virtuaalikonetta ei voi luoda.

Selvittelin asiaa virtuaaliboxista löytyvistä ohjeista ja löysin tiedon, että virtuaalikoneen asennus vaatii riittävästi tilaa myös omalta koneeltani. Kuvassa 5 on esitetty löytämäni virtualboxin ohje. 

Ilmeisesti virtuaalikoneen luomisessa luodaan kansio omalle koneelleni ja se vaatii tilaa. Oletuksena oli 20 GB, jota en lähtenyt muokkaamaan. Tosin mikäli ymmärsin ohjeista oikein, niin suositus olisi ollut jopa 60GB ja ilmeisesti tämän verran tilaa tarvitaan myös omalta koneeltani, mutta en ole asiasta varma. Koneellani on levytilaa vapaana ainoastaan hieman yli 20 GB (20,36 GB). Tämä ei todennäköisesti riitä, vaan tilaa pitäisi olla enemmän. Yritin siivoilla pois ylimääräisiä tiedostoja ynnä muuta, mutta se ei näköjään vielä riittänyt. Suurempi siivoaminen vaatii sen verran enemmän aikaa, että en tähän hätään ehtinyt sitä tehdä. Kokeilen myöhemmin (tehtävän palautuksen jälkeen, ennen seuraavaa tuntia), josko riittävä tiedostojen poistaminen auttaisi ja vapauttaisi riittävästi tilaa. Muita ratkaisuja ongelmaan en tähän hätään keksinyt. Tehtävän tekeminen jäi siis kesken.


Lähteet:

Virtuaalikoneen asennus. Karvinen, Tero. Linux palvelimet -kurssi 2023. Luettavissa: https://terokarvinen.com/2021/install-debian-on-virtualbox/. Luettu 18.1.2023.


