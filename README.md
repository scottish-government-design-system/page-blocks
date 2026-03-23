# Scottish Government Design System page blocks
Construct page layouts with page blocks that extend the Scottish Government Design System.

## Feedback, help or support

If you need any help or want to give any feedback you can e-mail the Design System team at: [designsystem@gov.scot](mailto:designsystem@gov.scot).

## How to use in your project

We recommend installing the package using node package manager (npm).

### Install

To install your own local copy of the package follow these steps:

1. Ensure you have [node.js](https://nodejs.org/en/) installed. We recommend using the latest Long Term Support (LTS) version, or a minimum of version 8.10.0.
2. Run the command `npm install @scottish-government-design-system/page-blocks` in your chosen directory. This will install the project and its dependencies.

### Include in your project

We recommend importing the Sass for page blocks separately, along with the Sass from the Scottish Government Design System.

#### Import Sass modules

If you already are using the Scottish Government Design System in your project then you only need to include the additional Sass for page blocks. To import the page block Sass into your project's Sass use:

```
@use "/path/to/node_modules/@scottish-government-design-system/page-blocks/src/page-blocks";
```

#### Build production files

Alternatively you may wish to generate a separate CSS file to include in your project. 

Run:

```
npm run build
```

This will compile the various Sass files and update the contents of the `/dist` directory with the newly generated compressed and uncompressed CSS files.