## Yleistä
Jos sulle tulee ongelmia jonkun asian kanssa ja saat itse sen järjestelmässäsi korjattua, harkitse korjaustavan lisäämistä näihin ohjeisiin, johonkin sopivaan kohtaan.

# Normiohjeet

## Asennus Windowsille (64-bit)
1. [Asenna Hallacoin-x.xx.x-win64-setup.exe](https://github.com/hallabois/hallacoin/releases/latest)
2. Lataa tiedosto [Hallacoin.conf](https://raw.githubusercontent.com/hallabois/hallacoin/master/Hallacoin.conf) (Ctrl+s tallentaa) kansioon C:\Users\SUNNIMITÄHÄN\AppData\Roaming\Hallacoin . Varmista että tiedoston tiedostopääte on .conf eikä .txt .

## Kaivostoiminta
1. [Lataa cpuminer](https://sourceforge.net/projects/cpuminer/files/latest/download)
2. Käynnistä Hallacoin-qt legacy-address -tilassa, eli suorita seuraava komento Hallacoinin asennuskansiossa: ```Hallacoin-qt.exe -server -addresstype=legacy```
3. ```minerd -o http://localhost:9332/ --user darius --pass rucker --coinbase-addr={sun hallacoin-osoite}```


---


# Uber TT-shittiä
Jatka varoen

## Ohjeet rakentamiseen
1. [Downloading the code and setting up the environment](setup)
2. [Compiling & Installing](build)

## Ohjeet lähdekoodin generoimiseen alusta asti
1. [Pull litecoin & use the automatic script](generate)
2. [Generate the Merkle Root & The Genesis Block](MerkleRoot)
