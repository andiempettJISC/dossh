# DOSSH

A simple interactive CLI utility to lookup existing digitalocean droplets and start an SSH session.

### Install

```shell
brew tap androidwiltron/dossh
brew install dossh
```

### Usage

```shell
dossh [-f <localport:remoteport>]
```

### Arguments

| Argument | Optional | Description                                                       | Format            |
|----------|----------|-------------------------------------------------------------------|-------------------|
| -f       | Yes      | Port Forward. Start port forwarding a remote port to a local port | <0-65536:0-65536> |

