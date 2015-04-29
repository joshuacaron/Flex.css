# Flex.css
A convenient library for CSS flexbox layouts, based off of Polymer's layout.html, but using CSS classes instead of attributes.

The usage is exactly the same as with Polymer, except the attributes are now CSS classes. For example instead of using `<div layout vertical>` use `<div class="layout vertical">`. See [https://www.polymer-project.org/0.5/docs/polymer/layout-attrs.html](https://www.polymer-project.org/0.5/docs/polymer/layout-attrs.html) for the full list of layout options.

To install simply run `bower install css-flex`. Then in your HTML file link to `<link rel='stylesheet' type='text/css' href='bower_components/css-flex/flex.css'>`, and you're good to go.

This project is based off of layout.html from the Polymer project. The only modifications are changing the attributes to css classes, the remaining code is directly from the Polymer project which is released under the following licence:

Copyright (c) 2014 The Polymer Project Authors. All rights reserved.
This code may only be used under the BSD style license found at http://polymer.github.io/LICENSE.txt
The complete set of authors may be found at http://polymer.github.io/AUTHORS.txt
The complete set of contributors may be found at http://polymer.github.io/CONTRIBUTORS.txt
Code distributed by Google as part of the polymer project is also
subject to an additional IP rights grant found at http://polymer.github.io/PATENTS.txt