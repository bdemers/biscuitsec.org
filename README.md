# biscuitsec.org
This is a playground for biscuit tokens. We developed this site to ease the understanding and usage of biscuit tokens (in the spirit of jwt.io).

The site is made using react, wasm and the biscuit rust library.


## Install

Use npm to install the required packages and start the server. Please follow these instructions to launch the server

`npm install`

`npm start`


## Deploy
The playground is deployed on netlify, and available at https://biscuitsec.org
-> TOFIX


## Use cases
Our base scenario is a [car rental agency](./examples/car_rental_agency.md)

We implemented other self-contained examples, such as [xstate](https://github.com/acertio/ex_biscuit_xstate).


## Credit

Credit goes to clever cloud and its developers (notably Geoffroy Couprie) and for the [core library](https://github.com/CleverCloud/biscuit).

Developed by Mohamed Rahji and Fabien Imbault.


## Todo
- [ ] support sealed biscuit, depends on [issue](https://github.com/CleverCloud/biscuit-rust/issues/12)
- [ ] clean files and provide detailed documentation (look for temporary links on https://www.w3schools.com)


