# Les classes d'adresses IPV4

Classe | Masque réseau | Adresses réseau | 
-------| --------------| ----------      | 
A      | 255.0.0.0     | 1.0.0.0 - 126.255.255.25 | 
B      | 255.255.0.0   | 128.0.0.0 - 191.255.255.255 |
C      | 255.255.255.0 | 192.0.0.0 - 223.255.255.255 |
D      | 240.0.0.0     | 224.0.0.0 - 239.255.255.255 |

255 = partie réseau
0 = partie hôte

-----------------------------------------------------------

# Les classes d'adresses IPV4

Classe | Masque réseau | Adresses réseau | Nombre de réseaux | 
-------| --------------| ----------      |  ----------
A      | 255.0.0.0     | 1.0.0.0 - 126.255.255.25 |126 | 16777214 |
B      | 255.255.0.0   | 128.0.0.0 - 191.255.255.255 |16384 | 65534 |
C      | 255.255.255.0 | 192.0.0.0 - 223.255.255.255 | 2097152 | 254 |
D      | 240.0.0.0     | 224.0.0.0 - 239.255.255.255 | adresses uniques | 

-----------------------------------------------------------

# Les adresses IP privées et publiques

> Les adresses IP privées

-    Les adresses privées de la classe A : 10.0.0.0 à 10.255.255.255
-    Les adresses privées de la classe B : 172.16.0.0 à 172.31.255.255
-    Les adresses privées de la classe C : 192.168.1.0 à 192.168.255.255
