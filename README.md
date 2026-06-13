# Story Picker

A random story generator built with vanilla JavaScript. Pick a genre — scary, funny, adventure, mystery, or sci-fi — and get a randomly selected story with a matching color theme.

## Live Demo

[https://abedoulaye.github.io/story-picker/]

## Features

- 5 genres with 5 unique stories each (25 total)
- Random story selection per click — no repeats in a row
- Dynamic border and background colors that change with each genre
- Fully responsive design
- Built without any frameworks or libraries

## How It Works

Each genre is stored as an object containing an array of stories and color values. When a genre button is clicked, the JavaScript picks a random index from that genre's array and updates the DOM with the story text and matching colors.

## What I Practiced

- DOM manipulation (`querySelector`, `getElementById`, `textContent`)
- Event listeners (`addEventListener`)
- JavaScript objects and arrays
- Bracket notation for dynamic property access
- `Math.random()` and `Math.floor()` for random selection
- CSS transitions for smooth color changes
- Git version control and GitHub

## Built With

- HTML
- CSS
- JavaScript
