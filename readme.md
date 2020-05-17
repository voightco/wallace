<div align="center" style="text-align: center;">

![wallacelogo](./docs/github-logo.jpg)

<em>Quickly set-up your local linting environment.</em>

<a href="#includes">Includes</a> |
<a href="#install">Install</a> |
<a href="#plugins">Plugins</a>

</div>

## Intro

A **basic linting set-up** you can add to any (node) project. These are opionated default configuration files. Please tweak them to your liking, don't take them 'as is'.

## Includes

- [EditorConfig][config]: helps to maintain a consistent coding styles across various editors and IDEs.
- [ESLint][eslint]: analyzes JavaScript to quickly find syntax problems (errors).
- [Stylelint][stylelint]: avoids errors and enforces conventions in your styles.
- [Prettier][prettier]: opinionated code formatter (style).
- [VScode editor settings][prettier]: common defaults for the VSCode text editor.

## Install

Most of these configurations work by installing a plugin for your text editor and then adding _configuration files_ to your project. You can add these `dotfiles` to your _existing project_, put them in the root of your directory. Or install them _globally_ on your machine by adding them to the root of your machine.

### Linting

If you installed the _plugins for your editor_, it will show any linting warnings and errors trough the interface. You can also lint trough your _cli_ using `npm run scripts`.

_Lint every JavaScript file in your project using the cli_

```
npm run lint:css
```

_Lint every CSS file in your project using the cli_

```
npm run lint:js
```

### VSCode settings

The easiest way to install the VScode configuration is to open up the `settings.json` file from **this repository** and copy and paste the contents into your current `settings.json` **from VScode**.

## Plugins

- Install the [EditorConfig plugin][ediplugin] for your text editor
- Install the [ESLint plugin][esplugin] for your text editor
- Install the [Stylelint plugin][styleplug] for your text editor

_You'll probably don't need the prettier plugin, we extend prettier through ESLint._

## Support

I believe in making resources and products public and free (as in freedom, not free as in free frappuccinos) so people can build upon them. If you like my resources and products you can consider [supporting me][support].

Made with 🤍 by [Danny de Vries][author] and [contributors][contributors].

## License

[MIT][license] © [Danny de Vries][author]

[author]: https://github.com/dandevri
[license]: license
[contributors]: https://github.com/voightco/wallace/graphs/contributors
[support]: https://www.dandevri.es/support/
[ediplugin]: https://editorconfig.org/#download
[config]: https://editorconfig.org/
[eslint]: https://eslint.org/
[esplugin]: https://eslint.org/docs/user-guide/integrations
[prettier]: https://prettier.io/
[stylelint]: https://stylelint.io/
[styleplug]: https://stylelint.io/user-guide/integrations/editor
