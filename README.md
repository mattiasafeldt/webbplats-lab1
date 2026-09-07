# Webbplats Laboration 1
En webbplats skapad som en del av laboration.
Innehåller lite kort information om mig och mina intressen.
## 📌Tekniker
- HTML - Webbplatsens innehåll och struktur.
## 📌Publicerade versioner
- [GitHub Pages](https://mattiasafeldt.github.io/webbplats-lab1/)
- [Netflify](https://webbplats-lab1.netlify.app/)
## 📌Frågor om Git
### Vad är skillnaden mellan git add och git commit?
- git add - Lägger till ändrade filer i Staging Area.
- git commit - Skapar en ny version i ditt lokala reo.
### Varför använder man branches istället för att jobba direkt i main?
Detta bidrar till att utveckla och testa ändringar separat, utan att påverka main.
När de ändringar man gjort fungerar och är testade kan man mergea dessa med main.
### Vad händer rent praktiskt när man gör en merge?
Git tar med de ändringar man gjort från en branch till en annan.
Till exempel kan ändringarna i dev föras in i main.
### Vad är skillnaden med att pusha till GitHub och att publicera direkt på exempelvis Netflify?
- Pushar man till GitHub, skickar man sina lokala commits till repot på GitHub.
- Om jag publicerar webbplatsen görs den tillgänglig på en webbadress där andra besökare kan se och använda den.
### Hur exkluderar man en fil från versionshanteringen?
Lägg till filens namn i .gitignore för att Git ska förstå att den ej ska versionshanteras.
Om filen redan har laddats upp sedan tidigare behöver detta kommando användas: git rm --cached filnamn
Efter detta kan man spara ändringen i en commit.
