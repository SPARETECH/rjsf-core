# THIS IS A FORK OF [react-jsonschema-form](https://github.com/rjsf-team/react-jsonschema-form) CONTAINING [#1666](https://github.com/rjsf-team/react-jsonschema-form/pull/1666). AS SOON AS THIS LANDS WE CAN GO BACK TO USE THE OFFICIAL PACKAGE.

## Additional Change

- [#1666](https://github.com/rjsf-team/react-jsonschema-form/pull/1666) uses the `useDefaults` options in `validate.js`. This is a breaking change for the general behavior of the form, but was used to fix the if/then/else behavior. Each if block is validated on its own and a property with an `undefined` value without being required, will always validate. Using `useDefaults` in combination with adding `"default": ""` to the if block properties will have the correct validation. 

[![Build Status][build-shield]][build-url]
[![npm][npm-shield]][npm-url]
[![npm downloads][npm-dl-shield]][npm-dl-url]
[![Contributors][contributors-shield]][contributors-url]
[![Apache 2.0 License][license-shield]][license-url]

<br />
<p align="center">
  <a href="https://github.com/rjsf-team/react-jsonschema-form">
    <img src="https://raw.githubusercontent.com/rjsf-team/react-jsonschema-form/59a8206e148474bea854bbb004f624143fbcbac8/packages/core/logo.png" alt="Logo" width="180" height="120">
  </a>

  <h3 align="center">@rjsf/core</h3>

  <p align="center">
  Core logic and classic Bootstrap 3 theme for <a href="https://github.com/rjsf-team/react-jsonschema-form/"><code>react-jsonschema-form</code></a>.
    <br />
    <a href="https://react-jsonschema-form.readthedocs.io/en/latest/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://rjsf-team.github.io/react-jsonschema-form/">View Playground</a>
    ·
    <a href="https://github.com/rjsf-team/react-jsonschema-form/issues">Report Bug</a>
    ·
    <a href="https://github.com/rjsf-team/react-jsonschema-form/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [THIS IS A FORK OF react-jsonschema-form CONTAINING [#1666](https://github.com/rjsf-team/react-jsonschema-form/pull/1666) AS SOON AS THIS LANDS WE CAN GO BACK TO USE THE OFFICIAL PACKAGE](#this-is-a-fork-of-react-jsonschema-form-containing-1666-as-soon-as-this-lands-we-can-go-back-to-use-the-official-package)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
    - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

Core logic and classic Bootstrap 3 theme for `react-jsonschema-form`.

### Built With

- [react-jsonschema-form](https://github.com/rjsf-team/react-jsonschema-form/)
- [Bootstrap 3](https://getbootstrap.com/docs/3.3/)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- `Bootstrap 3`

To use the default Bootstrap 3 theme, add a Bootstrap 3 CSS tag to your HTML page:

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
```

### Installation

```sh
npm install @rjsf/core
```

## Usage

```javascript
import Form from '@rjsf/core';
```

<!-- ROADMAP -->

## Roadmap

See the general [open issues](https://github.com/rjsf-team/react-jsonschema-form/issues).

<!-- CONTRIBUTING -->

## Contributing

Read our [contributors' guide](https://react-jsonschema-form.readthedocs.io/en/latest/contributing/) to get started.

<!-- CONTACT -->

## Contact

rjsf team: [https://github.com/orgs/rjsf-team/people](https://github.com/orgs/rjsf-team/people)

GitHub repository: [https://github.com/rjsf-team/react-jsonschema-form](https://github.com/rjsf-team/react-jsonschema-form)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[build-shield]: https://github.com/rjsf-team/react-jsonschema-form/workflows/CI/badge.svg
[build-url]: https://github.com/rjsf-team/react-jsonschema-form/actions
[contributors-shield]: https://img.shields.io/github/contributors/rjsf-team/react-jsonschema-form.svg
[contributors-url]: https://github.com/rjsf-team/react-jsonschema-form/graphs/contributors
[license-shield]: https://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/apache-2.0/
[npm-shield]: https://img.shields.io/npm/v/@rjsf/core/latest.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/@rjsf/core
[npm-dl-shield]: https://img.shields.io/npm/dm/@rjsf/core.svg?style=flat-square
[npm-dl-url]: https://www.npmjs.com/package/@rjsf/core
[product-screenshot]: https://raw.githubusercontent.com/rjsf-team/react-jsonschema-form/59a8206e148474bea854bbb004f624143fbcbac8/packages/core/screenshot.png
