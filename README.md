# TS Node Starter

To use this project as a starter, do the following:

```bash
# Clone the project
$ git clone https://github.com/jakobsen/ts-node-starter.git

# Enter the directory
$ cd ts-node-starter

# Install the dependencies
$ npm i

# Verify that everything works
$ npm start

> ts-node-starter@1.0.0 start
> ts-node index.ts

Hello world!
```
You may now start developing, using [`index.ts`](/index.ts) as an entry point.
If you want the code to run again every time there's a change in a file, you can use the following command:
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
[nodemon] restarting due to changes...
[nodemon] starting `ts-node index.ts`
Hello there!
[nodemon] clean exit - waiting for changes before restart
```