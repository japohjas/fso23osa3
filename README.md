 
Ohjelman suoritus
### node index.js
```
"scripts": {
    "start": "node index.js",
```
tai
### npm start

## Express
```
npm install express
```
Projektin riippuvuuksien päivitys
```
npm update
```
Jos aloitamme projektin koodaamisen toisella koneella, saamme haettua ajantasaiset, package.json:in määrittelyn kanssa yhteensopivat riippuvuudet komennolla
```
npm install
```

Jos muutamme sovelluksen koodia, joudumme ensin sulkemaan sovelluksen konsolista (ctrl + c) ja sitten käynnistämään sovelluksen uudelleen, jotta muutokset tulevat voimaan. Ratkaisu nodemon
```
npm install --save-dev nodemon
npm run dev
```