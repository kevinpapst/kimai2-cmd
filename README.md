# Kimai2-cmd

Command line client for [Kimai2](https://www.kimai.org/), the open source, self-hosted time tracker.

To use this program you have to install Kimai2 first!

This client is still under developement. See planned features in the next section

## Current and planned features

This client is not intended to replace the Kimai webUI, so only basic functions, starting and stopping measurements

Commands: 
- [x] Start, restart and stop measurements
- [x] List active and recent measurements
- [x] List projects and activities

UI:
- [x] Interactive terminal UI with autocomplete
- [ ] Classic terminal UI for integration 

Integration:
- [x] Portable executable for all three platforms
- [ ] Generate output for Rainmeter (Windows) (Just like [kimai-cmd](https://github.com/infeeeee/kimai-cmd))
- [ ] Generate output for Argos/Kargos/Bitbar (Gnome, Kde, Mac)

## Installation

Download executable from [releases](https://github.com/infeeeee/kimai2-cmd/releases/latest)

## Usage

Follow options in the terminal, currently only interactive UI

On the first run it will ask for your settings

## Developement version

### Installation

requirements:
- node js
- git

```
git clone https://github.com/infeeeee/kimai2-cmd
cd kimai2-cmd
npm install
```

### Build

Requirements: globally installed [pkg](https://github.com/zeit/pkg): 

```
npm install pkg -g
```

Build x64 executables to linux, mac, win:

```
npm run build
```

For building for other platforms see pkg's documentation, or open an issue and I can build it for you.


### Usage

```
npm start
```

Follow options in the terminal, currently only interactive UI

On the first run it will ask for your settings, but you can just copy settings.ini.example to settings.ini and modify it with your favourite text editor

## Troubleshooting

If you find a bug open an issue! The client is not finished yet, however all implemented features should work!

## License

MIT