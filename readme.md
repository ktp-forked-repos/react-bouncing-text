# Bouncing Text

[![npm version](https://badge.fury.io/js/react-bouncing-text.svg)](https://badge.fury.io/js/react-bouncing-text)

> A styled react component. Liven your text up.

Bounce the text by clicking/hovering on it.  
The animation will not be triggered until last animation has finished!

## Usage
### Install:
```
npm install --save react-bouncing-text

// or

yarn add react-bouncing-text
```

### Example:
```js
import BouncingText from 'react-bouncing-text';

const MyBouncingText = () => {
  <BouncingText
    className={myClassName}
    text={myTextToShow} 
    clickable
    hoverable 
    delay={ms} 
    duration={ms}
  >
};

export default MyBouncingText;

```

## API

### BouncingText

| Porperty | Description | Type | Default |
| -------- | -------- | -------- | -- |
| className | specify class name of whole text | String     | -- |
| text | text to display | String    | -- |
| clickable | whether triggerable by clicking | Boolean    | false |
| hoverable | whether triggerable by hovering     | Boolean     | false |
| delay | delay for each text. every character's delay will time the index of itself. (ms) | Number   | -- |
| duration | duration for each text. duration start after delay for each character. (ms)  | Number    | -- |

You should not keep `text`, `delay`, `duration` empty.

## Demo

[Codepen](https://codepen.io/sh1zuku/pen/bvWQRZ)
