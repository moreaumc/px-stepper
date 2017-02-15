# px-path-guide
[![Build Status](https://travis-ci.org/PredixDev/px-path-guide.svg?branch=master)](https://travis-ci.org/PredixDev/px-path-guide)

[![px-path-guide demo](px-path-guide.png?raw=true)](https://github.com/PredixDev/px-path-guide?target=_blank)


px-path-guide is a visual representation of a sequence of steps and any associated progress details.  It can show which steps have been completed, the current step, and later steps.

## Overview

Use the px-path-guide to represent any sequence of steps that can be completed.  An example of a process is user account creation, which can consist of this sequence of steps: 1. Sign Up, 2. Email Confirmation, 3. Account Activation and 4. Account Configuration.  px-path-guide will can represent this process with a sequence of circles, each corresponding to the steps.  Each step is labeled accordingly.  px-path-guide can place connector lines between adjacent steps.  Each step's completion state can be symbolized by a font-awesome icon, like a checkmark for a completed step.

## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. Install the [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs) to add support for web components and custom elements to your application.

### Getting Started

First, install the component via bower on the command line.

```
bower install px-path-guide --save
```
Second, import the component to your application with the following tag in your head.

```
<link rel="import" href="/bower_components/px-path-guide/px-path-guide.html"/>
```

Finally, use the component in your application:

```
<px-path-guide></px-path-guide>
```

<br />
<hr />

## Documentation

Read the full API and view the demo [here](https://predixdev.github.io/px-path-guide).

## Using Events

Events follow the [Polymer data-binding standards](https://www.polymer-project.org/1.0/docs/devguide/data-binding.html).

You can can attach the following listener(s) to these parts of the component:

1. Mouseclick event on a step.
<br />
<hr />

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### LiveReload

By default gulp serve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.

### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-path-guide/issues) to submit any bugs you might find.