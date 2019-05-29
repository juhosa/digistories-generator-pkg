[![npm version](https://badge.fury.io/js/digistories-generator.svg)](https://badge.fury.io/js/digistories-generator)
# Digistories generator package

Mainly used in (my custom built) DigiStories app for Pepper-robot.

Published to NPM as a test and learning process for myself.

## Installation

```
yarn add digistories-generator
```
or
```
npm install digistories-generator
```

## Usage

```javascript
import generateStory from "digistories-generator";

const stories = [
    {kuva: 'pic1.jpg', teksti: "Text 1\nAnother line"},
    {kuva: 'pic2.jpg', teksti: "Text 2\nAnother line"}
]

const outputString = generateStory("Name of the person", stories);
````
