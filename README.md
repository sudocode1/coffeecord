# CoffeeCord

## About

Discord Library written in CoffeeScript

## Code Example

```coffee
CoffeeCord = require "coffeecord"

Client = CoffeeCord.Client token, options

Client.on "ready", ->
  console.log "Ready", "Logged in as #{Client.user.username}##{Client.user.discriminator}"

Client.connect()
```

## Motivation

My motivation to continue/recreate this is because I work with CoffeeScript and have always wanted a Discord Libary for CoffeeScript. 
<br />
The developer ditched this project just over a year ago and I felt like doing a revival for mine, and other peoples, convenience.


## Installation

npm install coffeecord
