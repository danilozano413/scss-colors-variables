# Scss Colors Variables

## Installation

### Install by NPM

``` bash
    npm i scss-colors-variables --save
```

## Usage

Add precompiled scss to your global style scss file

``` scss
    @import '~ionic-scss-utils';
```  

or

Add compiled css

``` scss
    @import '~ionic-scss-utils/css';
```  

## Use own colors

Create your variables.scss and include before import this package

```  scss
    @import './variables.scss';
    @import '~ionic-scss-utils/utils.scss';
```

## Libraries compatibility

* [Tailwindcss](https://tailwindcss.com/)
* [Ionic Framewoek](https://ionicframework.com/)
* [Ionic Scss Utils](https://github.com/danilozano413/ionic-scss-utils)
