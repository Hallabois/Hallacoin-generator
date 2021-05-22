# Merkle-juuren rakentaminen
1. ```sudo pip install scrypt construct==2.5.2```
2. ```git clone git@github.com:Hallabois/GenesisH0.git```
3. ```cd GenesisH0```
4. ```python3 genesis.py -a scrypt -z "Kiitos kaikille, jotka osallistuivat eiliseen uusien 7. luokkalaisten info-iltaan. Jos yleisesittely jäi välistä, voit katsoa esityksen diat täältä." -t 1621711933 -n 2084848677```, jossa t on [unix-epoch](https://duckduckgo.com/?q=unix+timestamp&t=newext&atb=v263-1&ia=answer) (ota se talteen), z on joku ajankohtainen merkkijono ja a on käytettävä proof-of-work -algoritmi (Hallacoinin tapauksessa scrypt). Annetuilla asetuksilla tämän tulisi löytää arvo ```27ebdba18b68539a33f4f1a6643ac6cbca83f506884de5d1947e5a855cb4c4a5```.
