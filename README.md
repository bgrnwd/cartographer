# cartographer

[![license](https://img.shields.io/github/license/bgrnwd/cartographer.svg)](LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

cartographer is a minimal Hugo theme designed for readability

Inspired by:

- [FiveThirtyEight](https://fivethirtyeight.com/)
- [Gregory Gundersen](https://gregorygundersen.com/)
- [Chris Albon](https://chrisalbon.com/)

## Table of Contents

- [cartographer](#cartographer)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
    - [Fonts](#fonts)
  - [Install](#install)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Background

### Fonts

cartographer uses 3 open source fonts that are included under `static/fonts`

- [Source Serif Pro](https://github.com/adobe-fonts/source-serif-pro)
- [Public Sans Web](https://public-sans.digital.gov/)
- [Space Mono](https://github.com/googlefonts/spacemono)

## Install

```sh
git submodule add https://github.com/bgrnwd/cartographer.git themes/cartographer
```

or

```sh
git clone https://github.com/bgrnwd/cartographer.git themes/cartographer
```

## Usage

Add the following to your `config.toml` to tell Hugo to use the theme

```toml
theme = "cartographer"
```

Alternatively, the theme can also be passed in as an argument when starting the Hugo server

```sh
hugo server -t cartographer
```

## Contributing

Feel free to [open an issue](https://github.com/bgrnwd/cartographer/issues/new) or submit a pull request.

## License

[MIT](./LICENSE) © Brian Greenwood
