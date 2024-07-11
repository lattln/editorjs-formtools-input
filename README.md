# @lattln/editorjs-formtools-input

EditorJS block tool for user input questions. This block tool allows you to add customizable user input questions to your EditorJS instance.


![image](https://github.com/lattln/editorjs-formtools-input/assets/56560260/81fec7f3-3207-48bf-a0c3-b0131d4b6910)



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
  holder: 'editorjs',
  tools {
    inputQuestion {
      class: InputQuestion,
      inlineToolbar: true,
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

 * Utility Functions `@lattln/editorjs-formdep-utils`
 * SVG Icons `@lattln/editorjs-formdep-svgicons`
  
These packages are automatically installed as dependencies. You can also use them independently if needed.


## Updating Dependencies
to update the dependencies to their latest version, use the provided npm script
``` bash
npm run update-dep
```

## Acknowledgements

I would like to express my gratitude to [Medical Informatics Engineering (MIE)](https://mieweb.org/) for their support and for providing the resources necessary to develop this project. Special thanks to the mentors who guided me throughout this journey with their invaluable insights and expertise. Your encouragement and assistance have been instrumental in the successful completion of this project.





