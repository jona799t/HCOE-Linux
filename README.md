# HCOE-Linux
En guide til Linux på HCØ

## Maple
Man kan downloade Maple her: https://www.maplesoft.com/download/  
Du kan finde "purchase code" inde på linket på Lectio forsiden.  
Installeren skal klargøres som en hver anden Linux excecutable:
```
chmod +x ./MapleYYYY.VLinuxX64Installer.run
```
Så kan den køres med:
```
./MapleYYYY.VLinuxX64Installer.run
```
Nogen gange åbner Maple installeren ikke. Her kan du i stedet køre konsol versionen af installeren i stedet:

```
./MapleYYYY.VLinuxX64Installer.run --mode text
```

Hvis du har problemer med at aktivere så vær sikker på, som Maple selv siger det, at dit Linux er "LSB 3.0 compatible".
På eksempelvis Arch Linux hjælper det ikke noget at installere `lsb-release`, du skal i stedet installere `ld-lsb`.

## LoggerPro
LoggerPro er ikke længere understøttet native på Linux, og derfor skal der bruges Wine for at få det til at køre.  
Wine kan nemt installeres med din package manager.  
LoggerPro virker kun på 32-bit.  
For at gøre det nemmere at håndtere dependencies, så kan det anbefaldes at bruge programmet Bottles til at holde styr på dit LoggerPro.  
I bottles kan du også nemt installere de nødvendige skrifttyper, ved at installere "allfonts" og "lucon". 
