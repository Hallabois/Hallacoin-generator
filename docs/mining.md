# Louhimisohjelman asennus

Ohje olettaa, että sinulla on [Hallacoin asennettu](https://hallabois.github.io/Hallacoin-ohjeet/asennus) ohjeiden mukaan ja että sinulla on tiedostopäätteiden näyttö päällä (pitäisi olla, jos olet seurannut ohjeita sivulta)

Ohjekuvat otettu Bravella mutta prosesssi on samanlainen Firefoxilla ja muilla selaimilla

---

Lataa [cpuminer](https://sourceforge.net/projects/cpuminer/files/latest/download)


![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/1.png)

Jos vastaan tulee viesti, että asennus on estetty, mene Chromen latauksiin ja paina "Pidä haitallinen tiedosto". Chrome tekee tämän kaikilla kryptovaluuttaminereilla, eikä ohjelma ole haittaa tekevä. 

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/2.png)
![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/3.png)


Avaa kansio, mihin tiedosto ladattiin. (Ladatut tiedostot on oletuskansio). Valitse ladattu tiedosto ja paina ylhäältä pura. 

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/4.png)


Valitse "Pura kaikki" ja paina sen jälkeen tulevassa ikkunassa "Pura".

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/5.png)


Tee uusi tiedosto right clickkamalla ikkunasta ja valitsemalla Uusi -> Tekstitiedosto.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/6.png)


Nimeä tiedosto mihin tahansa, mutta muuta .txt pääte .bat-iksi. Valitse kyllä.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/7.png)


Right clickkaa juuri tehdystä .bat tiedostosta ja valitse Muokkaa

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/8.png)


Kopioi komento: `minerd -o http://localhost:9332/ --user darius --pass rucker --coinbase-addr=`. Älä sulje vielä tiedostoa.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/9.png)


Siirry kansioon, johon [Hallacoin](https://hallabois.github.io/Hallacoin-ohjeet/asennus) on asennettu. (C:\Program Files\Hallacoin). Right clickkaa Hallacoin-qt.exe tiedostosta, ja valitse luo pikakuvake.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/10.png)


Windows ilmoittaa, että pikakuvaketta ei voida luoda kansioon. Valitse kyllä.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/11.png)


Mene työpöydällesi ja valitse uusi Hallacoin pikakuvake. Right clickkaa siitä ja valitse "Ominaisuudet".

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/12.png)


Lisää "Kohde"-kentän perään `server -addresstype=legacy`. Paina OK.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/13.png)


Avaa pikakuvake. Kun Hallacoin Core avautuu, mene Vastaanota -> Vastaanota maksu

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/14.png)


Paina alhaalta "Kopioi osoite". Tämä kopioi Hallacoin-lompakkosi osoitteen, jota voit käyttää maksujen pyyntöön.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/15.png)


Avaa .bat tiedosto uudestaan ja liitä perään kopioitu Hallacoin-osoitteesi.

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/16.png)


Tallenna tiedosto. 

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/17.png)


Käynnistä nyt tekemäsi .bat tiedosto. Tietokoneesi alkaa louhimaan Hallacoinia!

![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/18.png)
![](https://raw.githubusercontent.com/hallabois/Hallacoin-ohjeet/main/mining-kuvat/19.png)


---


# Louhimisen käynnistäminen 

- Käynnistä Hallacoin core-pikakuvake työpöydältäsi.
- Avaa kansio, jonne latasit cpuminerin ja teit .bat-tiedostosi. 
- Avaa .bat tiedostosi. Hallacoinia pitäisi alkaa tulemaan tilillesi! 
