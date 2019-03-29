# Word Map
_This project comes from the split of the original [exploreAT-collectionexplorer](https://github.com/acdh-oeaw/exploreAT-collectionexplorer) of [Alex Benito](https://github.com/ale0xb)_

Geographical exploration of Lemmas, with filtering options (text, part of speech and year) enabled to highlight only certain words in the map. It allows for word/text searches. 
Individual results of lemmas are displayed on a map to show their geographical location and distribution. Narrowing results to word categories or according to time are possible. 
Hovering over individual entries on the map gives information on lemma, location and source.

![Prototye screenshot](img/prototype.png "Prototype screenshot")

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

Dependencies are been migrated from [Bower]() with [bower-away](). Therefore yarn or npm may be used for installing
the dependencies.

As indicated in **Bower** official site, it is recommended not to use it to manage the dependencies.

```
yarn
```
or
```
npm install
```

You can use any static server of your choice to serve the files for the webpage.
Additionally, [webpack](http://www.dropwizard.io/1.0.2/docs/) may be used for compiling the source code
and package it into a few files (friendlier with download speed for the webpage).

**This prototype needs for a json file containing the geographical data to be shown; it uses an API for retrieving data regarding words with geo location ((API)[https://github.com/acdh-oeaw/exploreAT-collectionexplorer-api]).**

## Authors

* [Alex Benito](https://github.com/ale0xb) - *Implementation of the prototype* 
* [Alejandro Rodríguez](https://github.com/Janchorizo) - *Project split and migration to newer package managers* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

