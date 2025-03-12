# HCØ Linux
En guide til Linux på HCØ.

## Maple
Man kan downloade Maple her: https://www.maplesoft.com/download/  
Installeren skal klargøres som enhver anden Linux-executable:
```
chmod +x ./MapleYYYY.VLinuxX64Installer.run
```
Derefter kan den køres med:
```
./MapleYYYY.VLinuxX64Installer.run
```
Nogle gange åbner Maple-installeren ikke. Her kan du i stedet køre konsolversionen af installeren:

```
./MapleYYYY.VLinuxX64Installer.run --mode text
```

Hvis du har problemer med aktivering, så vær sikker på, som Maple selv siger, at din Linux-distribution er "LSB 3.0 compatible".  
På eksempelvis Arch Linux hjælper det ikke at installere `lsb-release`. Du skal i stedet installere `ld-lsb`.  

Gympakken til Linux kan hentes her: https://www.maplesoft.com/dk/MapleGym/index.aspx

## LoggerPro
LoggerPro understøttes ikke længere officielt på Linux. Derfor skal Wine bruges for at få det til at køre.  
LoggerPro virker kun på 32-bit.  
For at gøre det nemmere at håndtere dependencies anbefales det at bruge programmet Bottles til at holde styr på dit LoggerPro.  
I Bottles kan du også nemt installere de nødvendige skrifttyper ved at installere "allfonts" og "lucon".  
![image](https://github.com/user-attachments/assets/62c73a51-6937-4c3e-96a6-ea241a31dc0a)

## Solstice
Man kan skærmdele ved at indtaste IP-adressen i browseren: https://www.youtube.com/watch?v=YczM-ak0Jfc

## ChemSketch
ChemSketch fungerer godt med 64-bit Wine. Du skal blot sikre, at hele mappen med `setup.exe` læses af Wine, da mappens filer er nødvendige for installationen.  
Under installationen kan fejlen "RPC server unavailable" dukke op, men denne kan blot ignoreres.  
![image](https://github.com/user-attachments/assets/0aefea83-163d-4db4-a3dc-8c10bf7ed3e7)

## MarvinSketch
MarvinSketch er let tilgængelig for Debian- og RedHat-baserede distributioner. For andre systemer kan eksempelvis `debtap` (Arch) anvendes, eller installationen kan foretages manuelt.  
Programmet hentes her: https://download.chemaxon.com/marvin-sketch
![image](https://github.com/user-attachments/assets/e8ce547c-0e89-4a26-a863-af7a4582b107)

