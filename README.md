docker build -t tg-app .

docker run -it -e BOT_TOKEN=  --rm --name tg-app tg-app
