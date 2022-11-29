# tnyaa

A shell script for searching torrents on nyaa.

![example](example.gif)

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - xclip

## Installation

    install -m 755 tnyaa /usr/bin

## Usage

Just type 'tnyaa "your search"', choose what you want and the magnet link will be copied to your clipboard.

Search for the biggest lossless audio

    tnyaa -c audio-lossless -s size 'audio'

Search for the least seeded lossy audio on second page

    tnyaa -r -s se -p 2 'audio'

Search different domain for word "list" and change delimiter to space

    tnyaa -D ' ' -d 'https://otherdomain.to' 'list'

Get some help

    tnyaa -h
