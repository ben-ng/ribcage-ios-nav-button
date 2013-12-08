Ribcage iOS Nav Button
=======================

A little view to use with `ribcage-view` that gives you a pure CSS ios7-style menu button.

## Install

```
npm install ribcage-ios-nav-button
```

## Usage

```javascript

  var NavButton = require('ribcage-ios-nav-button')

  var button = new NavButton({
    label: 'Something'
  , action: function () {
      myView.trigger('dosomething')
    }
  })

```
