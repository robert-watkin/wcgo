# wcgo
This is my first go cli project. This is intended to get me up to speed with Go fundamentals.
The script will take in a file or read from stdin and count the number of words in it.

## install

go install wcgo

## run

wcgo README.md

## usage

./wcgo --min <number> --top <number> <file>

## example

./wcgo README.md
./wcgo --min 5 --top 10 README.md
./wcgo // read from stdin

## testing

go test // run tests
go test -v // verbose

