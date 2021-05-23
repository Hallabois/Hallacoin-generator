# Hallacoin (Ohjeet)

## Yleistä
Jos sulle tulee ongelmia jonkun asian kanssa ja saat itse sen järjestelmässäsi korjattua, harkitse korjaustavan lisäämistä näihin ohjeisiin johonkin sopivaan kohtaan.

## Ohjeet rakentamiseen ja asentamiseen
1. [Downloading the code and setting up the environment](/docs/setup.md)
2. [Compiling & Installing](/docs/build.md)

---

## Ohjeet lähdekoodin generoimiseen alusta asti
1. [Pull litecoin & use the automatic script](/docs/generate.md)
2. [Generate the Merkle Root & The Genesis Block](/docs/MerkleRoot.md)

## Kaivostoiminta
1. Asenna cpuminer
2. Käynnistä Hallacoin-qt legacy-tilassa: ```Hallacoin-qt -server -addresstype=legacy```
3. ```minerd -o http://localhost:9332/ --user darius --pass rucker --coinbase-addr={sun hallacoin-osoite}```
