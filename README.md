
# quaint-autoprefixer

Autoprefixer for Quaint.

[Autoprefixer](https://github.com/postcss/autoprefixer) lets you use
upcoming CSS features (flexbox, for instance) easily by adding vendor
prefixes when applicable, using the data from [Can I
Use](http://caniuse.com/).

## Install

In your Quaint project directory, run the command:

    quaint --setup autoprefixer


## Usage

Any CSS resources you include will be filtered through autoprefixer,
for instance `quaint-autoprefixer` will transform `my-style.css` when
you use this directive:

```quaint
resources :: my-style.css
```

Transformations are also applied to CSS files listed in
`resources.files` in `quaint.json`.
