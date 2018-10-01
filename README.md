[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/@myfrom/iron-swipeable-pages)
[![Build Status](https://img.shields.io/travis/rust-lang/rust.svg?style=flat-square)](https://travis-ci.org/myfrom/iron-swipeable-pages)
[![npm](https://img.shields.io/npm/v/@myfrom/iron-swipeable-pages.svg?style=flat-square)](https://www.npmjs.com/package/@myfrom/iron-swipeable-pages)

**This is a fork** because the [original element](https://github.com/GeoloeG/iron-swipeable-pages) seems to no longer be maintained for newer Polymer versions.


# `<iron-swipeable-pages>`

`<iron-swipeable-pages>` is a Polymer 3 element that manages a set of pages and provides the ability to switch between them by swiping gesture.

## Install

Install the component using NPM:

```sh
$ npm install iron-swipeable-pages --save
```

## Usage

Import Custom Element:

```js
import 'iron-swipeable-pages/iron-swipeable-pages.js';
```

And then use it:

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="iron-swipeable-pages.html">
	  <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<iron-swipeable-pages selected="0">
  <div>One</div>
  <div>Two</div>
  <div>Three</div>
</iron-swipeable-pages>
```

See the [Documentation](https://geoloeg.github.io/iron-swipeable-pages/) for more options.

## More Demos

 - [Declarative](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/index.html)

 - [Conditional with dom-if's](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/conditional.html)

 - [Disabled](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/disabled.html)

 - [Alongside <paper-drawer-panel>](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/drawerpanel.html) *(Might not work due to deprecation of paper-drawer-panel)*

 - [Mobile](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/mobile.html)

 - [With routing](https://myfrom.github.io/iron-swipeable-pages/components/iron-swipeable-pages/demo/routing.html)


## Discussing

You can also find the original creator on the [Polymer Slack Channel](https://polymer.slack.com/) under nickname of *@MeTaNoV*

## Contributing

Please submit your PRs to `myfrom` branch if you have any new feature ideas.

For best development experience, it's recommended to have **[Polymer CLI](https://www.polymer-project.org/3.0/docs/tools/polymer-cli)** installed. It provides functionality such as serving element docs locally and testing framework.
