[![npm version](https://badge.fury.io/js/sky-toolkit.svg)](https://badge.fury.io/js/sky-toolkit)  [![Circle CI](https://circleci.com/gh/sky-uk/toolkit/tree/master.svg?style=svg&circle-token=6b7a4f1adf2fb7fad8c0942b8d4d8386afb681f4)](https://circleci.com/gh/sky-uk/toolkit/tree/master)

# Toolkit

**Sky's CSS Toolkit**

For full documentation, visit [sky.com/toolkit](http://sky.com/toolkit)

## Contents

* [Goals](#goals)
* [Structure](#structure)
* [Installation](#installation)
* [Requirements](#requirements)
* [Versioning](#versioning)
* [Champions](#champions)
* [Contributing](#contributing)

## Goals

- Enable teams across tribes to share common styles.
- Provide a modular approach to handling CSS/Sass components.
- Provide a single source of truth for Polaris brand guidelines.

## Structure

The project consists of 3 repositories:

- **this repo**: provides the UI and Core layers.
- [toolkit-core](https://github.com/sky-uk/toolkit-core): Global styles and defaults for all projects.
- [toolkit-ui](https://github.com/sky-uk/toolkit-ui): Aesthetic components.

### Libraries
- [toolkit-react](https://github.com/sky-uk/toolkit-react): React.js UI components built on Toolkit styles.

## Installation

```
$ npm install sky-toolkit --save
```

:warning: **Note:** your Sass configuration **must** be set to access certain dependencies or installation will fail. Either:
 * Include [Eyeglass](https://github.com/sass-eyeglass/eyeglass) in your [build tools](https://github.com/sass-eyeglass/eyeglass#building-sass-files-with-eyeglass-support) **or**
 * Set `node_modules` in your `includedPaths`

See [sky.com/toolkit](http://sky.com/toolkit) for full documentation and information on how to [implement the Toolkit](http://sky.com/toolkit/getting-started) in your project.

### Compiled

For rapid prototyping and static sites you can include our latest compiled CSS in the `<head>` of your page.

```
<link rel="stylesheet" href="https://www.sky.com/assets/toolkit/v1.7.0/toolkit.css">
```

**We strongly advise not to use this method in live projects**.
Use `npm` installation to benefit from the Toolkit's modularity and extensibility.


## Requirements

Because of how the Toolkit loads third party dependencies (such as [sass-mq](https://github.com/sass-mq/sass-mq)), your development environment needs:

* [npm](https://www.npmjs.com/) (3.0 or greater)
* [NodeJS](https://nodejs.org/en/) (5.0 or greater)

If you're using [**webpack**](https://webpack.github.io/) you'll also need:

* [sass-loader](https://github.com/jtangelder/sass-loader) (3.1 or greater)

## Versioning

The Toolkit follows [Semantic Versioning](http://semver.org) to help manage the impact of releasing new library versions.

## Maintainers

| [![Joe Bell](https://avatars.githubusercontent.com/joebell93?s=100)<br /><sub>Joe Bell</sub>](https://github.com/joebell93) | [![Joe Dinsdale](https://avatars.githubusercontent.com/mrdinsdale?s=100)<br /><sub>Joe Dinsdale</sub>](https://github.com/mrdinsdale) | [![Aaron Thomas](https://avatars.githubusercontent.com/aaronthomas?s=100)<br /><sub>Aaron Thomas</sub>](https://github.com/aaronthomas) | [![Luke Barratt](https://avatars.githubusercontent.com/lbarratt?s=100)<br /><sub>Luke Barratt</sub>](https://github.com/lbarratt) | [![Steve Duffin](https://avatars.githubusercontent.com/steveduffin?s=100)<br /><sub>Steve Duffin</sub>](https://github.com/steveduffin) | [![Sam Kitson](https://avatars.githubusercontent.com/skitson?s=100)<br /><sub>Sam Kitson</sub>](https://github.com/skitson) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |

## Contributing

We appreciate **any** contribution to the Toolkit, please check out [CONTRIBUTING.md](CONTRIBUTING.md).

We keep a list of features and bugs [in the issue tracker](https://github.com/sky-uk/toolkit/issues).

### Champions

If you need any support getting to grips with the Toolkit, pop over to your tribe Toolkit Champion:

| DA                                                | DC                                             | DE                                            | DS                                             | DT                                                   |
|---------------------------------------------------|------------------------------------------------|-----------------------------------------------|------------------------------------------------|------------------------------------------------------|
| [Mahesh Jagadeesan](https://github.com/maheshjag) | [Chris Vernon](https://github.com/welikeideas) | [Callum Barratt](https://github.com/cbarratt) | [Clare Devine](https://github.com/claredevine) | [Alex Fenton](https://github.com/afenton90)          |
|                                                   | [Djenan Kozic](https://github.com/djenan)      | [John Bower](https://github.com/beclamide)    | [Greg Pratt](https://github.com/gregorypratt)  | [Stefan McCready](https://github.com/stefanmccready) |
|                                                   |                                                |                                               | [Rory King](https://github.com/geit)           | [Rich Gorman](https://github.com/coderas)            |

**Special thanks to the following contributors:**

- [Harry Roberts](https://github.com/csswizardry)
- [Callum Barratt](https://github.com/cbarratt)
- [Richard McIntyre](https://github.com/mackstar)
- [Ross Warren](https://github.com/rosswarren)
- [Steven Bapaga](https://github.com/romidane)
