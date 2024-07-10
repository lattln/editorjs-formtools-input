# @lattln/editorjs-formtools-input

EditorJS block tool for user input questions. This block tool allows you to add customizable user input questions to your EditorJS instance.

## Installation

First, ensure you have `@editorjs/editorjs` installed as a peer dependency. Then, install `@lattln/editorjs-formtools-input` along with its dependencies.


#### Install EditorJS
```bash

npm install @editorjs/editorjs
```
#### Install the custom block tool
``` bash

npm install @lattln/editorjs-formtools-input
```

## Usage

```js
import EditorJS from '@editorjs/editorjs';
import InputQuestion from '@lattln/editorjs-formtools-input';

const editor = new EditorJS({
  holder 'editorjs',
  tools {
    inputQuestion {
      class InputQuestion,
      inlineToolbar true,
    }
  }
});
```

## Tool Config
```js
const editor = new EditorJS({
  holder 'editorjs',
  tools {
    inputQuestion {
      class InputQuestion,
      inlineToolbar true,
      config {
         Add any specific configuration for InputQuestion if needed
      }
    }
  }
});

```

## CSS Styling
The package includes default styles for the block tool. If you want to customize the styling, you can override the provided styles by importing the CSS file and adding your own custom styles.
```js
import '@lattln/editorjs-formdep-styles/src/toolStyles.css';
```

## Utility Function and SVG Icons
The block tool utilizes utility functions and SVG icons from the following packages

 Utility Functions `@lattln/editorjs-formdep-utils`
 SVG Icons `@lattln/editorjs-formdep-svgicons`
  
These packages are automatically installed as dependencies. You can also use them independently if needed.


## Updating Dependencies
to update the dependencies to their latest version, use the provided npm script
``` bash
npm run update-dep
```





