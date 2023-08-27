[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT HEADER -->
<br />
<p align="center">
  <h3 align="center">_final-REMASTERED</h3>

  <p align="center">
    Script for finding the final name
    <br />
    <br />
    ·
    <a href="https://github.com/Beuterei/_final-REMASTERED/issues">Report Bug</a>
    ·
    <a href="https://github.com/Beuterei/_final-REMASTERED/issues">Request Feature</a>
    ·
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

Helps you find the perfect final name for your file

## Usage

```sh
_final HelloWorld.js
```

## Installation

```sh
brew install Beuterei/homebrew-tap/_final
```

or without brew

```bash
# installs to /usr/local/bin/_final
curl -L https://raw.githubusercontent.com/Beuterei/_final-REMASTERED/master/_final >/usr/local/bin/_final
chmod 0755 /usr/local/bin/_final
```

## Parameters

| Parameter          | Description                         | type      |
| ------------------ | ----------------------------------- | --------- |
| `-h --help`        | Show this usage summary and exit    | -         |
| `-e`               | Only echos back the generated names | -         |
| `--use_separators` | Use separators (e.g. . , - \_)      | `boolean` |
| `--modifiers_max`  | Maximum modifiers to be generated   | `number`  |

### Add more modifiers and separators

Add them at the top of the script. Each line is a modifiers/separators.

Modifiers and separators may only contain characters that are allowed in filenames.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/Beuterei/_final-REMASTERED.svg?style=flat-square
[contributors-url]: https://github.com/Beuterei/_final-REMASTERED/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Beuterei/_final-REMASTERED.svg?style=flat-square
[forks-url]: https://github.com/Beuterei/_final-REMASTERED/network/members
[stars-shield]: https://img.shields.io/github/stars/Beuterei/_final-REMASTERED.svg?style=flat-square
[stars-url]: https://github.com/Beuterei/_final-REMASTERED/stargazers
[issues-shield]: https://img.shields.io/github/issues/Beuterei/_final-REMASTERED.svg?style=flat-square
[issues-url]: https://github.com/Beuterei/_final-REMASTERED/issues
[license-shield]: https://img.shields.io/github/license/Beuterei/_final-REMASTERED.svg?style=flat-square
