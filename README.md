# What is it?

This image is a frozen version of Sharelatex with all its packages installed and the full version of `TexLive`.

It is really a copy of the Overleaf Community Edition image with most of the packages needed installed.

## What do I need to run this?

- You will need Docker and Docker Compose installed

## What operational System does this run into?

- I have tested it both on Linux and Windows and it runs fine with Docker

## How to run

1. Go to [the repo](http://github.com/silvavn/sharelatex).
2. Clone it
3. Run `docker-compose up -d` in your terminal

## How to stop

- Run `docker-compose down` in your terminal

## There is a package that I need that is not installed

1. Follow the `How to Run` guide
2. In the terminal run `docker exec sharelatex tlmgr install name_of_the_missing_package`, replacing the tag `name_of_the_missing_package` by the missing `LaTex` package
