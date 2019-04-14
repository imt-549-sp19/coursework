# CSS Frameworks

In the [Adding Some Style](adding-css.html) and [Responding to the Device](responsive.html) tutorials, you learned how to write style rules that change the appearance of your web pages. Although you could implement a entire site with only custom style rules, most professionals build upon a well-tested CSS framework instead. The framework normalizes browser default styling, applies consistent and attractive formatting to all HTML elements, and defines several style classes you can use for common UI components (badges, alerts, cards, responsive navigation bars, tabs, drop-down buttons, tool tips and popovers, sliders, switches, carousels, etc.). You can then add your own custom rules on top of the framework to tweak the default framework formatting.

A CSS framework is just a stylesheet with a bunch of rules that someone else wrote for you, and some accompanying JavaScript for the interactive features. There's nothing magic about it. You can look at the stylesheet and see all the rules that are defined in there, and it's all stuff you could have written yourself. But those rules have been crafted by professionals and tested on a wide array of browsers to ensure consistent results, so it's a good idea to build on top of them.

## Popular CSS Frameworks

There are several popular CSS frameworks to choose from. All of them provide beautiful formatting of HTML elements, pre-defined responsive multi-column layout grids that work on all browsers, and all the common UI elements you see on most web sites.

### Bootstrap

The most commonly-used CSS framework on the web is Bootstrap. It was originally created at Twitter to enforce some consistency amongst their internal tools, but after they released it as an open-source project in 2011, it became very widely used. That wide use has benefits and drawbacks: it's very well tested, documented, and supported, but it's also so prevalent that it's default look has become cliché. Thankfully, it's rather easy to customize Bootstrap with your own fonts, colors, sizing, etc.

### Foundation

Bootstrap's chief rival is Foundation. It has the reputation of being more ahead-of-the-curve than Bootstrap, introducing new features sooner. They were the first framework to use a responsive mobile-first design, and their new version 6 already offers a flexbox-based responsive grid. Foundation has mostly the same UI elements as Bootstrap, but with a different default look at feel, which can also be customized to match your own branding.

### Material Design Lite

Bootstrap and Foundation defined their own visual design language, but if you are a fan of Google's Material Design instead, there are a few CSS frameworks based upon that. The official Google implementation is known as Material Design Lite, or MDL for short. Material Design is very opinionated so MDL is difficult to customize beyond changing the primary and accent colors. Their style class names are also very verbose, as they follow the Block, Element, Modifier (BEM) naming method. But it's a well-implemented framework that has all the smarts and money of Google behind it.

### Materialize

The other popular Material Design implementation is Materialize. This is an open-source project, so it's not supported by Google, nor does Google feel that it's a "correct" implementation of Material Design. Regardless, a lot of people use it, primarily because it's easy to learn if you are coming from Bootstrap.

## Adding a Framework to your Page

Each framework has a "getting started" page that describes your various options for adding the framework to your HTML page. Nearly all of them will let you link to their production files on a Content Delivery Network (CDN), download them as a zip file, or add them to your project via a package manager like npm or bower. Each method has its benefits and drawbacks.

### Linking to a CDN

Linking to a CDN is a very easy option that has several benefits. The first is simplicity. For example, linking to Bootstrap's version 4.1.0 files on a CDN is as simple as adding these elements to the `<head>` section of your web page: