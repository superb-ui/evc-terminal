<h1 align="center"><code>bui-terminal</code></h1>
<p align="center">BUI for terminal</p>
<p align="center"><a href="https://github.com/NNBnh/bui-terminal/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"></a> <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/badge/development-completed-%234EAA25.svg?labelColor=073551&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></a></p>
<p align="center"><a href="https://github.com/NNBnh/bui-terminal/watchers"><img src="https://img.shields.io/github/watchers/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/bui-terminal/stargazers"><img src="https://img.shields.io/github/stars/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/bui-terminal/network/members"><img src="https://img.shields.io/github/forks/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"></a> <a href="https://github.com/NNBnh/bui-terminal/issues"><img src="https://img.shields.io/github/issues/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"></a></p>

## About
`bui-terminal` is an UI tool written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) that change terminal colors on-the-fly independent of terminal emulator and uses [BUI environment variables](https://github.com/superb-ui/bui).

## Contents
- [About](#about)
- [Contents](#contents)
- [Setup](#setup)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Usage](#usage)
- [Credit](#credit)

## Setup
### Dependencies
- `sh` to process

### Installation
#### Manually
- Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/NNBnh/bui-terminal/main/bin/bui-terminal > ~/.local/bin/bui-terminal
chmod +x ~/.local/bin/bui-terminal
```

- Option 2: using `git`

```sh
git clone https://github.com/NNBnh/bui-terminal.git ~/.local/share/bui-terminal
ln -s ~/.local/share/bui-terminal/bin/bui-terminal ~/.local/bin/bui-terminal
```

#### Package manager
For [`bpkg`](https://github.com/bpkg/bpkg) user:

```sh
bpkg install NNBnh/bui-terminal
```

For [Basher](https://github.com/bpkg/bpkg) user:

```sh
basher install NNBnh/bui-terminal
```

###### If you can and want to port BUI terminal to other package managers, feel free to do so.

## Usage
Run `bui-terminal` in the terminal:

```sh
bui-terminal
```

## Credit
Special thanks to:
- [**Paleta**](https://github.com/dylanaraps/paleta) by [Dylan](https://github.com/dylanaraps), This project inspired me to make this tool.

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></p>
