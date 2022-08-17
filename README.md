# TS Node Starter Pack

For å bruke dette prosjektet som et utgangspunkt til utvikling i Typescript, kjør følgende kommandoer i terminalen: 

```bash
# Klon prosjektet
$ git clone https://github.com/jakobsen/ts-node-starter.git

# Gå inn i prosjektmappen
$ cd ts-node-starter

# Installer nødvendige pakker
$ npm i

# Sjekk at alt virker, burde printe `Hello world!`
$ npm start

> ts-node-starter@1.0.0 start
> ts-node index.ts

Hello world!
```
Du kan nå begynne å utvikle med utangspunkt i [`index.ts`](/index.ts)
Om du har lyst til at koden skal kjøre hver gang du gjør en endring kan du bruke følgende kommando:
```bash
$ npm run dev

> ts-node-starter@1.0.0 dev
> nodemon index.ts

[nodemon] 2.0.19
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: ts,json
[nodemon] starting `ts-node index.ts`
Hello world!
[nodemon] clean exit - waiting for changes before restart
```