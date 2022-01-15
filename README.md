# idGenerator

Can be used to generate random IDs of any user determined length.

## Requirements:

- Node.js (any version)

## Installation:

- with npm: npm install @ponurrrak/id-generator
- with yarn: yarn add @ponurrrak/id-generator

## Usage

1. const idGenerator = require('@ponurrrak/id-generator');
2. console.log(idGenerator()); - then you get 10 characters long id.

OR

1. const idGenerator = require('@ponurrrak/id-generator');
2. const idLength = 20; (or any other number)
3. console.log(idGenerator(idLength));
