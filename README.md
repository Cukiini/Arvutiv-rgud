# Arvutiv-rgud
Tarmo Roopärg

Lesson 1

Ping - Saad vaadata kas ühendus sinu ja mõne muu hosti vahel on võimalik.
printf - Saad sisestada teksti ja eristada mõnda käsku.
nc - Andmete edastamine internetiühenduste vahel.
| (pipe) - Outputi ülekandmine teise kohta.
-l - Paneb nc kindlale pordile kuuldele.
Control-D - Ühendab netcati pordist lahti
> - Saad saata nc commandi vastu faili sisse.

Lesson 2 

CTRL + C - Lõpetab protsessi
host - Veebilehe sisse kirjutamisel tõlgib selle IP-ks.
dig - nagu host, annab informatsiooni DNSi kohta.

Lesson 3

Käskudest eriti ei räägitud.
Rääkis sellest, et maailmas pole piisavalt IP-sid kõigile aga sellele on juba lahendus.
Lahenduseks hetkel on NAT süsteem ehk ruuteritel on private IP.

Lesson 4

tcpdump - Saab vaadata DNS trafficut.
Rääkis miks on packetid vajalikud ja kuidas nad töötavad.
Kui üks pool ei saa teiselt vastust teatud ajajooksul siis ühendus katkeb.

Lesson 5

traceroute - Näitab kõiki IP-sid mida läbisid enne kui jõudsid soovitud aadressile.
Rääkis sellest, et ruuter ei suuda lasta suurt arvu packeteid korraga läbi ning mida ruuter teeb selle jaoks.
Rääkis veel ka sellest, et seadmetel on firewallm, mis jälgib ja filtreerib tegevust seadme ja võrgu vahel.
