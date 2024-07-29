# Innoverse-Bot
Discord bot of Innoverse Discord Server

## Compiling

### Setup
Install [Go](https://go.dev/doc/install) and [git](https://git-scm.com/downloads), then clone this project.
```bash
$ git clone https://github.com/InnoverseTeam/DiscordInnoverse-Bot
$ cd DiscordInnoverse-Bot
```

### Compiling using Go
```bash
$ go mod init DiscordInnoverse-Bot
$ go get github.com/bwmarrin/discordgo
$ go mod tidy
$ go run main.go
```
