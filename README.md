# Roon Material

The Roon Material theme for [Ghost](http://github.com/tryghost/ghost/), based on [Roon](https://github.com/TryGhost/Roon) theme.

This theme is using [Materialize CSS](http://materializecss.com) framework, and it's currently under development.

## Font Options

This theme comes with two font options; a serif and sans-serif. Switching between them must be done in the HTML, by changing a `class` on the `<body>` element in [default.hbs](https://github.com/TryGhost/Roon/blob/master/default.hbs#L23).

**Sans-Serif - Gibson**

The sans-serif is the default, so you don't need to add anything. The `<body>` element should look like this:

```html
<body class="{{body_class}} {{#is 'index, tag, author'}}user{{/is}} {{#is 'post'}}{{#unless post.image}}noimage{{/unless}}{{/is}}">
```

**Serif - Filo Pro**

For the serif font, the `<body>` element should look like this:

```html
<body class="serif {{body_class}} {{#is 'index, tag, author'}}user{{/is}} {{#is 'post'}}{{#unless post.image}}noimage{{/unless}}{{/is}}">
```

## Copyright & License

Copyright (c) 2015 Untung Suryono.
Original Copyright (c) 2013-2015 Sam Soffes & Ghost Foundation - Released under the [MIT license](LICENSE).
