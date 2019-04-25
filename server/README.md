# README

## HOW TO

For running commands
`docker-compose run --rm api rails`

For getting to rails console
`docker-compose exec api rails console` (this takes forever)

g scaffold todo title completed:boolean order:integer

## Rubocop

`docker-compose exec api bash`
`rubocop`

## Errors

A server is already running.
Check server/tmp/pids/server.pid.
