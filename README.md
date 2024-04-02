# Scottish Government Design System content blocks
Construct page layouts with content blocks that extend the Scottish Government Design System.

## Feedback, help or support

If you need any help or want to give any feedback you can e-mail the Design System team at: [designsystem@gov.scot](mailto:designsystem@gov.scot).

## How to use in your project

We recommend installing the package using node package manager (npm).

### Install

To install your own local copy of the package follow these steps:

1. Ensure you have [node.js](https://nodejs.org/en/) installed. We recommend using the latest Long Term Support (LTS) version, or a minimum of version 8.10.0.
2. Run the command `npm install @scottish-government-design-system/content-blocks` in your chosen directory. This will install the project and its dependencies.

### Include in your project

We recommend importing the Sass for content blocks separately, along with the Sass from the Scottish Government Design System.

#### Import Sass files

To import the Sass into your project's Sass use:

```
@import "/path/to/node_modules/@scottish-government-design-system/src/content-blocks/all-content-blocks";
```
**This must be imported after the Scottish Government Design System Sass.**

#### Build production files

These are the optimised CSS assets that can be included in your project.
**This also includes the Scottish Government Design System CSS in the generated CSS file, so doesn't need included separately.**

Run:

```
npm run sass-min
```

This will compile the various Sass files and update the contents of the `/dist` directory with the newly generated compressed CSS file.

To create a non-compressed CSS file, run:

```
npm run sass
```