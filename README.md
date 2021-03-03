# Overview

This install script is designed to fully cofigure a Macintosh system to my
personal liking. Rather than downloading, installing, creating config files,
and other activities related to getting a freshly installed system customized,
I run this install script.

# Installation

To download, extract, and run the installer, run the following command:

```bash
mkdir -p ~/working/github.com/travelar/
pushd ~/working/github.com/travelar/
git clone https://github.com/travelar/system-config
cd system-config
./install
```

# Supported Operating Systems

The install script is tested against macOS.

# Design Philosophy

Rather than just having a "[dotfiles](https://www.google.com/search?q=dotfiles)"
repo, which works great in many cases, I prefer to keep as much in a single
config repo as possible. This means also installing software. I provision
systems for myself constantly and every second where I repeat myself adds up, so
this repo helps me streamline my efforts and be efficient.
