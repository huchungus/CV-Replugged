[release-badge]: https://img.shields.io/github/v/release/ClearVision/ClearVision-v6?include_prereleases&style=flat-square
[release-link]: https://github.com/ClearVision/ClearVision-v6/releases
[license-badge]: https://img.shields.io/github/license/ClearVision/ClearVision-v6?style=flat-square
[license-link]: https://github.com/ClearVision/ClearVision-v6/blob/master/LICENSE
[discord-badge]: https://discord.com/api/guilds/212324635356692500/widget.png?style=shield
[discord-link]: https://clearvision.gitlab.io/join
[issues-badge]: https://img.shields.io/github/issues/ClearVision/ClearVision-v6?style=flat-square
[issues-link]: https://github.com/ClearVision/ClearVision-v6/issues
[prs-badge]: https://img.shields.io/github/issues-pr/ClearVision/ClearVision-v6?style=flat-square
[prs-link]: https://github.com/ClearVision/ClearVision-v6/pulls

<div align="center">

# ClearVision v6

[![Releases][release-badge]][release-link]
[![License][license-badge]][license-link]
[![Discord Server][discord-badge]][discord-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]

![v6 Sapphire](https://github.com/ClearVision/ClearVision-v6/raw/master/screenshots/6-stable.4.7.9.png)

</div>

## Theme Editing

Please join the Clearvision support server for more details as a temporary solution. This will be resolved in the future

## Installing

To install to Replugged, follow this [link](https://replugged.dev/install?identifier=com.clearvision.v6)

## Building from source

In order build the theme from source, you can simply run `npm install` to install all missing dependencies, and `npm run build` to compile the theme into the `/public` folder.

### Dependencies

- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)
- [rimraf](https://www.npmjs.com/package/rimraf) (for cleanup)
- [Prettier](https://www.npmjs.com/package/prettier) (code formatting)
- _[DiscordSelectors](https://github.com/Zerthox/DiscordSelectors) (included in the `/lib` folder)_

## Contributing

You can run `npm run test` to compile the theme.
The `main.css` file will be in the `/test` directory, which can then be copied into BetterDiscord's Custom CSS.
