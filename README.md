pattern-library
======

* **Current stable version:** 2 ([release-2](https://github.com/codeforamerica/pattern-library/releases/tag/release-1) tag / linkable [url](https://style.codeforamerica.org/2/))
* **Current development version:** 3 ([master](https://github.com/codeforamerica/pattern-library/tree/master) branch / linkable [url](https://style.codeforamerica.org/3/))

The pattern library serves as the base CSS and organizing styles for [codeforamerica.org](http://codeforamerica.org). The pattern library is also a living style guide that explains how to use our CSS to build websites.

## Who's working on it

* [David Leonard](https://www.codeforamerica.org/people/david-leonard/): code, bugfixes, planning for the future
* [Michal Migurski](https://www.codeforamerica.org/people/david-leonard/): hosting, code, many things
* [Frances Berriman](https://www.codeforamerica.org/people/frances-berriman/): design + code advice

## Background

Code for America's communications and tech teams worked with Brighton web design firm [Clearleft](http://clearleft.com/) and Colorado branding firm [Dojo4](http://dojo4.com/) to create a new visual design and front-end for the Code for America website. This pattern library is used as the base for the following:

* CfA main site: [github](https://github.com/codeforamerica/codeforamerica.org) / [website](https://www.codeforamerica.org)
* CfA blog: [github](https://github.com/codeforamerica/cfawp2012) / [website](https://www.codeforamerica.org/blog/)
* CfA brigade site: [github](https://github.com/codeforamerica/brigade-alpha) / [website](https://www.codeforamerica.org/brigade)

Read more about pattern libraries here:

* http://clearleft.com/thinks/patternsharing/
* http://alistapart.com/blog/post/getting-started-with-pattern-libraries

## How to use it to build websites

1. **[Read the docs.](http://style.codeforamerica.org)** Complete documentation of the pattern library with copy-and-pastable code snippets is available at [http://style.codeforamerica.org](http://style.codeforamerica.org).
2. **Pick your version.** The current stable version is 2. The current development version is 3. 
3. **Add links to your document head.** For example, like this:

```
<head>
  ...
  <link rel="stylesheet" href="//style.codeforamerica.org/2/style/css/main.css">
  <link rel="stylesheet" href="//style.codeforamerica.org/2/style/css/layout.css" media="all and (min-width: 40em)">
  <link href="//style.codeforamerica.org/2/style/css/prism.css" rel="stylesheet" />
  ...
</head>
```
Note that you should include your chosen version number (i.e. **/2/**) in the url path.

## Versioning

Coming soon.

## How to deploy it

Coming soon.

## Contributing

We welcome bugs, questions and suggestions in the form of issues, or features and code fixes in the form of a pull request.

### Submitting a Pull Request

1. Fork the project.
2. Create a topic branch (name it something verb-y, like `fix-layout-padding`).
3. Make your changes, and commit with descriptive commit messages.
4. Push your changes.
5. Sumit a pull request.

### <a name="issues"></a>Submitting an Issue

We use the [GitHub issue tracker](https://github.com/codeforamerica/codeforamerica.org/issues) to track bugs and features. Before submitting a bug report or feature request, check to make sure it hasn't already been submitted. When submitting a bug report, please include a screenshot and any additioanl details that can help us debug, such as your operating system and browser version.

## License

Copyright (c) 2009-2015 Code for America. See the [LICENSE](https://github.com/codeforamerica/pattern-library/blob/master/LICENSE) for details.