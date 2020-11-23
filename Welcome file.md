# Mise en service UNITY Siège/NetCenter
## Montage UNITY dans la baie du 8éme
#### Ports Management
***Switch :* 172.16.108.189**
 - UNITY Bas -> ports (7,19)
 - UNITY Haut -> ports (6,18)
 #### Configuration VLAN 108
![Configuration Port To Vlan](https://ibb.co/cFVFgWc)
## Configuration POOL
 - Création du POOL1
 - Configuration du POOL1 EN RAID5
## MAJ Drive Firmware
 - CHECK Firmware des disques
 - Upload Frirmware File
## Configuration ISCSI
#### Configuration des interfaces sur les storage processeur (SP)
| Port Ethernet | SP |IP|
|--|--|--|
| Ethernet Port 2|SP A| 10.0.10.1 |
| Ethernet Port 2 |SP B| 10.0.20.1 |
## Ajout du vCenter
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcwMDQ5OTg3MywxOTQ0MDQzNzQwLDE1OD
I0MzM4NzIsLTI1MzE0MTkzNSwtNTE4OTY5MDE0LDE1MjcyMDU5
MTddfQ==
-->