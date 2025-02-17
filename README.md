# FAQ Bot

[![CI](https://github.com/deltachat-bot/faqbot/actions/workflows/python-ci.yml/badge.svg)](https://github.com/deltachat-bot/faqbot/actions/workflows/python-ci.yml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

A simple FAQ Bot for Delta Chat groups

## Install

```sh
pip install git+https://github.com/nelson9608/faqbot.git
```

### Installing deltachat-rpc-server

This program depends on a standalone Delta Chat RPC server `deltachat-rpc-server` program that must be
available in your `PATH`. To install it check:
https://github.com/deltachat/deltachat-core-rust/tree/master/deltachat-rpc-server

## Usage

Configure the bot:

```sh
faqbot init bot@example.com PASSWORD
```

Start the bot:

```sh
faqbot serve
```

Run `faqbot --help` to see all available options.
