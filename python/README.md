# Getting Started

View Halite documentation at https://halite-tournament.fly.dev/documentation/getting_started/

## How to use this?

Make a [new repository on Github](https://github.com/new). Follow the instructions to initialize a
new repo in this directory and push the files to Github.

This will create a Github Action to package your bot into a docker image and publish it to the
github container registry! You'll be able to use these docker images to register your bot.

## Developing Locally

To download the `halite` executable, visit https://github.com/nmalaguti/halite-matches/releases
and download the appropriate file for your operating system and architecture. Extract it into
this directory and run `./halite -d "30 30" "python MyBot.py" "python MyBot.py"` to run your bot
against itself.
