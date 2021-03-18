# Dinstagram - Instagram redesign

[![DeepSource](https://deepsource.io/gh/huynhducduy/dinstagram.svg/?label=resolved+issues)](https://deepsource.io/gh/huynhducduy/dinstagram/?ref=repository-badge)
![LGTM Grade](https://img.shields.io/lgtm/grade/javascript/github/huynhducduy/dinstagram?logo=lgtm)
![Codecov](https://img.shields.io/codecov/c/github/huynhducduy/dinstagram?logo=codecov&token=VLMIXK11LQ)
![Package.json version](https://img.shields.io/github/package-json/v/huynhducduy/dinstagram)
![GitHub](https://img.shields.io/github/license/huynhducduy/dinstagram)
![Dependencies](https://david-dm.org/huynhducduy/dinstagram.svg)

This project was bootstrapped with [Duy's React Starter Kit](https://github.com/huynhducduy/react-starter-kit)

## Configure

`cp .env.example .env && vi .env`

## Development

With docker: `docker-compose up --build -d`

Without docker: `yarn start`

Configure in `docker-compose.yml` file, default running on port `3000`

Running test: `yarn test`

Debugging tests: `yarn test:debug`

Lint code & style: `yarn lint`

Fix code & style: `yarn fix`

Reinstall entire project: `yarn refresh`

## Production

Build image: `sudo docker build -t dinstagram .`

Run container: `sudo docker run --init -dit -p 3000:80 --name dinstagram dinstagram:latest`

Kill and remove: `(sudo docker kill dinstagram || true) && (sudo docker rm dinstagram || true)`

Without docker: `yarn build`, output is located at `/build`

Analyze output: `yarn analyze`

## Todo
