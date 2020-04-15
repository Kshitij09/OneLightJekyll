# OneLightJekyll
Atom's One Light syntax colors for Jekyll powered blog. Could be compiled to - Pygments

Inspired from [OneDarkJekyll](https://github.com/mgyongyosi/OneDarkJekyll)

Colors borrowed from Atom's [one-light-syntax](https://github.com/atom/atom/tree/master/packages/one-light-syntax) package

Could be used as a template for related themes, to create new syntax stylesheet:

1. `npm install -g less less-plugin-clean-css`
1. Clone this repo
1. Download the `colors.css` file from the syntax theme's repository, for example [Solaried Light Syntax](https://github.com/atom/atom/blob/master/packages/solarized-light-syntax/styles/colors.less)
1. Put the file in same directory (might replace current syntax.css)
1. Run `lessc syntax.less syntax.css --clean-css`
1. Use the `syntax.css`
