# vinxictl [![Build Status](https://travis-ci.org/vinxi/vinxictl.png)](https://travis-ci.org/vinxi/vinxictl) [![GoDoc](https://godoc.org/github.com/vinxi/vinxictl?status.svg)](https://godoc.org/github.com/vinxi/vinxictl) [![Coverage Status](https://coveralls.io/repos/github/vinxi/vinxictl/badge.svg?branch=feat%2Finheritance)](https://coveralls.io/github/vinxi/vinxictl?branch=feat%2Finheritance) [![Go Report Card](https://goreportcard.com/badge/github.com/vinxi/vinxictl)](https://goreportcard.com/report/github.com/vinxi/vinxictl) [![API](https://img.shields.io/badge/vinxi-core-green.svg?style=flat)](https://godoc.org/github.com/vinxi/vinxictl) 

Command-line interface for vinxi with declarative configuration file to easily set up a full-featured proxy server.

Note: work in progress.

## Installation

```bash
go get -u gopkg.in/vinxi/vinxictl.v0
```

## Usage

```bash
vinxictl 0.1.0

Usage:
  vinxictl -p 80
  vinxictl -p 80 -c config.toml

Options:
  -a <addr>                 bind address [default: *]
  -p <port>                 bind port [default: 8080]
  -h, -help                 output help
  -v, -version              output version
  -c, -config               Config file path
  -f                        Target server URL to forward traffic by default
  -mrelease <num>           OS memory release inverval in seconds [default: 30]
  -cpus <num>               Number of used cpu cores.
                            (default for current machine is 8 cores)
```

## License

MIT - Vinxi Authors
