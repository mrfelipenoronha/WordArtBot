
# ![WordArtBot logo](images/logo.png)

The Telegram bot that generate beautiful wordArts for you! Try it on [**@bestWordArtBot**](https://t.me/bestWordArtBot).

## Usage

![Using it](images/using-it.gif)

To generate an WordArt you have the following options:

- Answer to a massage with the `/wordart` command
- Write the desired text right next to `/wordart`

You can also use the `/rainbow` command instead of `/wordart`. Use also `/two` and `/three` to generate compositions of multiple WordArt styles.

## Running locally

The most simple way is to build and run the Docker container, just issue `$ docker build --tag bot . && docker run -e MODE=dev -e BOT_TOKEN=<token> bot`.

Alternatively you can install all the dependencies (check the Dockerfile for more information) and run `$ export MODE=dev && export BOT_TOKEN=<token> && python3 bot.py`.

## Acknowledgments

Thanks [@arizzitano](https://github.com/arizzitano/css3wordart) for creating the reproduction of WordArt in CSS3 and [@zorbaproject](https://github.com/zorbaproject/pythonWordArt) for presenting a simple template to generate the WordArt text.
