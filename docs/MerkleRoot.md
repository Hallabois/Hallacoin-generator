# Merkle-juuren rakentaminen
1. ```sudo pip install scrypt construct==2.5.2```
2. ```git clone git@github.com:Hallabois/GenesisH0.git```
3. ```cd GenesisH0```
4. ```python3 genesis.py -a scrypt -z "Kiitos kaikille, jotka osallistuivat eiliseen uusien 7. luokkalaisten info-iltaan. Jos yleisesittely jäi välistä, voit katsoa esityksen diat täältä." -t 1621711933 -n 2084572713```, jossa t on [unix-epoch](https://duckduckgo.com/?q=unix+timestamp&t=newext&atb=v263-1&ia=answer) (ota se talteen), z on joku ajankohtainen merkkijono ja a on käytettävä proof-of-work -algoritmi (Hallacoinin tapauksessa scrypt). Annetuilla asetuksilla tämän tulisi löytää arvo ```c88f84a2b6b20b9fb2d38121d5898b02d6c71714f35a66df22ab7b13f13d46cc```.
