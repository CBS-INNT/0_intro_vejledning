# Opsætning af expo Windows - React native Mobil apps

#### En forudsætning for at kunne installere expo er at man hentet node
- Hent den anbefalede version(LTS) af Node ved at trykke på følgende link: https://nodejs.org/en/
- Du kan tjekke om du allerede har node ved at skrive `node -v` i terminalen. Hvis terminalen returnerer med en versionsbeskrivelse, som ikke er alt for gammel, er alt i orden og du kan hoppe til næste punkt i denne vejledning. 

#### Installer expo CLI  
- Installer expo CLI `npm install -g expo-cli`
- Hent expo appen fra din AppStore på følgende link: https://docs.expo.dev/get-started/set-up-your-environment/
 
#### Kør dit først expo projekt!
1. Navigér ind til den mappe, som projektet skal placeres i via terminalen (`cd` & `cd..`)

2. Skriv nu `npx create-expo-app --template blank`
3. Find nu dit projekt i VS code, og aktivér projektet ved at skrive
   `npx expo start` i terminalen

4. Dernæst åbnes terminalen med expo interfacet. Check først at din computer og telefon kører på det samme net. Scanning af QR-koden foregår ved brug af expo appen.
# OBS!!! Hvis cbs-nettet / eduroam ikke virker, kan det være nødvendigt at gå på mobil-hotspot. 
   
5. Resultatet skulle være at du skal se denne tekst `Open up App.js to start working on your app!`
6. Prøv at ændre i filen app.js og se teksten ændre sig
