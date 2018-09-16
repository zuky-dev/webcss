# WebCSS

![CSS Framework](https://img.shields.io/badge/type-CSS_Framework-blue.svg)
![version](https://img.shields.io/badge/version-0.1.1-lightgray.svg)
![status](https://img.shields.io/badge/status-development-red.svg)
![licence](https://img.shields.io/badge/licence-MIIT-blue.svg)

Goal of this barebones CSS Framework is to jumpstart responsive development without too much hassle. It's mainly aimed for devs who like to write CSS/SCSS but don't like to rewrite tons of it just to get the responsivness of other frameworks.

## Download options

* ### Link to cloud repo

    Link the minified framework via the html link tag.

    ```HTML
    <link rel="stylesheet" src="[COMMING SOON]">
    ```

* ### Download minified framework

    If you want to use the framework offline as is and dont want to use the sass mixins download the minified version of the framework.

    1. Download [webcss.min.css](COMMING_SOON)
    2. Link downloaded file to your HTML
        ```HTML
        <link rel="stylesheet" src="[path]/webcss.min.css">
        ```

* ### Download SCSS files

    For the most advanced users SCSS files are provided for you to extend them.

    1. Download [webcss.zip](COMMING_SOON).
    2. Unzip the archive
    3. Link the _**webcss.scss**_ to your _**main.scss**_
        ```SCSS
        @import '[path]/webcss.scss'
        ```

## Usage

[COMMING SOON]

### Grid positioning

WebCSS layouting is based on 12 rows (12 as being the most divisible number).

**Example**

```HTML
<div class="grid">
    <div class="gc-8">Big</div>
    <div class="gc-4">Small</div>
</div>
```

#### Responsiveness

**Example**

```HTML
<div class="grid">
    <div class="gc-sx-4 gc-md-8">Big</div>
    <div class="gc-sx-8 gc-md-4">Small</div>
</div>
```

### Dropdowns

## Development Informantion

### Prerequisites

![NodeJS](https://img.shields.io/badge/NodeJS-v8.11.4-blue.svg)
![NPM](https://img.shields.io/badge/NPM-v5.6.0-blue.svg)

Because we use npx as Parcel bundling process startup we recommend to use NPM v5 where NPX is installed by default. However you can run parcel also if you have it locally installed.

### [FORGOT WHAT I WANTED]

grid
flexbox

## In production

[COMMING SOON]

## Changelog

* _**v0.1.1**_ - updated documentation
* _**v0.1.0**_ - basic responsive grid mixin
* _**v0.0.1**_ - initial project setup

## Authors

* __Lukáš Odler__ - _initial development_ - [ZukyDesigns](https://github.com/zukydesigns)

## Licence

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/zukydesigns/webcss/blob/master/LICENSE) file for details.