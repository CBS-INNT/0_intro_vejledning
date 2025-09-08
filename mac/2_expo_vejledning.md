# Opsætning af expo - React native Mobil apps

1. Start med at åbne din terminal

2. **Hvis du får adgangsproblemer med at køre kommandoer i denne guide, skriv `sudo` før hvert kommando for at køre det som administrator**

3. Hvis du oplever fejl med kommandoer, læs først hvad terminalen siger og prøv selv at rette det, hvis det ikke lykkes, tilkald hjælp

## Homebrew
Tjek om det er installeret ved at skrive følgende: `brew -v`
Hvis terminalen svarer med et versions nr. gå videre til "Homebrew installeret". Hvis du får `zsh: command not found`, eller andet end et versions nr. gå videre til "Installere Homebrew".

### Installere Homebrew
1. Gå til: [https://brew.sh/](https://brew.sh/)

2. Kopier install curl i din terminal

3. Tjek om det er installeret korrekt ved at skrive følgende: `brew -v`

### Homebrew Installeret
1. I terminalen, skriv
   ```
   brew update && brew upgrade
   ```
PS: brew upgrade kan godt tage rimelig lang tid at køre

## Watchman
Expo kræver en pakke kaldet Watchman for at køre. Derfor skal du installere den ved at kopiere følgende i terminalen:
```
brew install watchman
```
For at tjekke om installationen er fuldført korrekt, kør: 
```
watchman --v
```

## Node

1. Tjek om det er installeret ved at skrive følgende: `node -v`, Hvis den giver et version nummer som `18.17.1` eller højere så er du good to go.

2. Hvis du alligevel ønsker at opdatere til den nyeste version, læs videre i næste afsnit.

### Download Node

Følg den officielle hjemmeside for at sikre den bedste installation: https://nodejs.org/en

### Opdatere Node
1. Clear npm cache: 
```
npm cache clean --force
```

4. Installere n package med kommandoen: 
```
npm install -g n
```

6. For at opdatere Node til den sidste version, kør:
```
n latest
```

8. Tjek nu: `node -v` & `npm -v`


## Expo
Før du går videre, tjek om nedenstående er opfyldt:

 - [ ] Watchman er installeret;
 - [ ] Node med version > 18.17.1.

1. Gå til: https://expo.dev/ og lav en konto ved at trykke på "Sign Up"

2. Download Expo Go på din mobil: https://docs.expo.dev/get-started/set-up-your-environment/?platform=ios&device=physical

### Start dit første expo projekt!
Vi anbefaler, at I laver en mappe "INNT_Exercises", hvor i kan gemme jeres opgaver.

1. Åbn Visual Studio Code (VS Code) og åbn jeres mappe samt en terminal i VS Code.

2. I terminalen kør:
```
npx create-expo-app --template
```

4. Måske vil den promte jer om at skrive "y" eller "n" til version 3.0 - skriv "y" for at godkend.

5. Choose a template: brug arrow-keys og vælg "Blank (Bare)"  template

6. Giv din app et navn, såsom "my_first_app"

7. Expo går i gang med at skabe din app, når den er færdig skal du navigere ind til projektet via terminalen ved at kør: `cd my_first_app`

8. Når du er kommet ind til mappen, kør `npx expo start` for at initiere appen. Hvis du oplever problemer med dette step, kør først `npm install` og derefter `npx expo start --tunnel`

9. Scan QR koden på skærmen og se appen på din telefon! 😲


