# Anime Guess
This repository contains all the source code for the animeguess project at https://www.animeguess.moe.

## Game Description
Anime Guess is a daily puzzle game inspired by [Wordle](https://www.nytimes.com/games/wordle/index.html), [Framed](https://framed.wtf/) and [GuessTheGame](https://guessthe.game/).

Every 24hrs a new set of images will be shared from an anime. These images will hopefully help you identify the aesthtic, character, context, and eventually the title of the anime.
All titles of anime will be in the Romaji and will match the answers as such. However, you can still type in the English title or other synonym while seaching. This will give you the Romaji title followed by the closest matching synonym.

`Eg. Kimi no Na wa [Your Name]`

We strive to create a game that is fun to play, challenging, and fufilling for individuals and communities. As such we will make selections for anime that are relevant to a large and diverse group of anime watchers (young, old, otaku, or casual). There will be a number of challenging selections as well easier answers and we hope that either way we can satisfy many players with exciting puzzles.

## Repository Description
There are only a few pieces that make up the animeguess game. The main repositories are:

### anime-frontend
The frontend of the animeguess game. This is built using Svelte and hosted in AWS S3.

### anime-api
The backend API for the animeguess game. The API is built using Python and is hosted in AWS.

### tools
Tools and other functions needed for the functionality of animeguess.

