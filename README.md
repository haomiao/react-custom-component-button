A custom component used by react, which is a demo project. 

## compile:
- git clone https://github.com/haomiao/react-custom-component-button.git
- cd react-custom-component-button
- npm install / yarn install
- npm run build:commonjs
- npm run build:esm
- npm run copy-css:esm
- npm run copy-css:lib

the dir of esm and lib are the packed objects.

## update the packed objects to npm:
- cd react-custom-component-button
- npm login
- npm publish

## How to use the component in your project:
- npm i -D react-custom-component-button
- import {Button} from 'react-custom-component-button';
- where to use the component, use tag: 'Button'

