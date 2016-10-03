# Optimist Digital | Core SCSS

This is a SCSS partial that provides some utility mixins and default styles that fit our workflow.

Some of the partials utilize variables that you may define in your project before including these partials. If not defined, we define defaults in `partials/_default-config.scss`.

## Usage

Add `@import "node_modules/@optimistdigital/core-scss/core";` before your component mixins, after your variable definitions.

## Features

#### Config

We set some default variables that are used in core and that you can use in your code. You can override them by defining them yourself *before* including core.

- `$global-site-maxwidth` - Used mainly for maxwidth-wrapper
- `$global-site-side-padding` - Used mainly for maxwidth-wrapper
- `$bp-tablet` - Min width (px) for tablets
- `$bp-mobile` - Min width (px) for mobile devices
- `$color-bg` - Main background color
- `$color-fg` - Main foreground (text) color
- `$body-font-size` - Main body size
- `$font-body` - Main font for body text
- `$font-heading` - Main font for headings

#### Mixins

The exact purpose of each mixin is explained in `_core.scss`. Other than the default styles, Here are the mixins that we provide:

- `@mixin clearfix()`
- `@mixin ellipsis()`
- `@mixin body-font()`
- `@mixin heading-font()`
- `@mixin maxwidth-wrapper()`
- `@mixin reset-list()`
- `@mixin bp($width)`
- `@mixin minbp($width)`
