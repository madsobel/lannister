# lannister [WORK IN PROGRESS]
A Lannister always pays his technical debt

![Keep calm and alwyas pay your debts](https://boomerandecho.com/wp-content/uploads/2014/04/Keep-Calm.jpg)

This is a work in progress. Basically, I like the idea of auto generating a list of potential technical debt in a code base.

## Install
`npm install -g lannister`

## Usage

`lannister src/` runs the the technical debt check on dir src/ and returns a report.md at current path.
 
## Current rules
* too-many-args: more than 4 args in a function
* too-long/file-too-long: file length more than 250 lines