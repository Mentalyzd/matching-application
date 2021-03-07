# Fitbud app
Deze app is gemaakt als project voor Blok Tech. Hierbij was het de bedoeling om een dynamische webapp te maken met gebruik van Node.js, Express en MongoDB. Deze app is gemaakt voor mensen die opzoek zijn naar gym buddies. Dit kan zijn om mee te sporten of om meer ervaring op te doen.

Deze webapp is alleen voor mobiel gebruik. Met de app kan je een eigen account aanmaken, inloggen, gebruikers liken en je profiel aanpassen.

## App screenshots
![](https://user-images.githubusercontent.com/32453774/110255719-75508d00-7f95-11eb-84d1-4bf19eec5f4a.jpg)

## Content
1. [Install App](#install-app)
2. [Install Database](#install-database)
4. [Code](#code)
5. [Data](#render-data)
6. [Update](#update-data)
7. [Packages](#packages)
8. [Sources](#sources)
9. [License](#license)


## Install App

### Stap 1
Installeer git
```
sudo apt update
sudo apt install git
```
Controleer of installatie gelukt is
```
git --version
Voorbeeld output: git version 2.17.1
```

### Stap 2
Clone de repo van github en ga naar de folder
```
git clone https://github.com/Mentalyzd/Fitbud.git
cd Fitbud
```

### Stap 3
Installeer npm
```
npm install
```
Controleer npm install
```
npm -v
Voorbeeld output: 7.5.3
```

### Stap 4
Run de applicatie
```
npm start
```
Succesvolle output:
```
App listening at http://localhost:2999 and on local network at http://YOU_LOCALE_IP_ADRES:8080
```

## Install Database
### Stap 1
Maak account aan voor mongoDB
```
Ga naar: https://account.mongodb.com/account/register
```
1. Zodra je ingelogd bent maak je een nieuw project aan in MongoDB Atlas.
2. Daarna maak je ook een nieuw cluster en een database aan met de naam naar keuze. Onthoud de database naam goed! 
3. MongoDB vraagt je om een username en een wachtwoord maken voor de database connectie. Onthoud deze ook goed!

### Stap 2
Maak in de root van de repo een bestand aan, genaamd .env
```
touch .env
```

Open het nieuwe betand in nano
```
nano .env
```
Hierin ga je variable toevoegen als gebruikersnaam, wachtwoord en database naam:
```<div color="green"> JOUW_DATABASE_GEBRUIKERSNAAM </div>
DB_USER=
DB_PASS=JOUW_DATABASE_WACHTWOORD
DB_NAME=JOUW_DATABASE_NAAM
```

Sla je bestand op
```
Type: CTRL + X
```

