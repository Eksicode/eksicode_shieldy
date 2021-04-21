# [@eksiCodeAntiSpamBot](https://t.me/eksiCodeAntiSpamBot) Telegram bot code

Telegram'da antispam için kullanılan popüler bir bot olan Shieldy'nin Ekşicode grupları için düzenlenmiş halidir.

# Installation

## Local launch

1. Clone this repo: `git clone https://github.com/Eksicode/eksicode_shieldy`
2. Launch the [mongo database](https://www.mongodb.com/) locally
3. Create `.env` with the environment variables listed below
4. Run `yarn install` in the root folder
5. Run `yarn distribute`

And you should be good to go! Feel free to fork and submit pull requests. Thanks!

## Docker

1. Clone this repo: `git clone https://github.com/Eksicode/eksicode_shieldy`
2. Replace the dummy environment variables in `docker-compose.yml` with the ones listed below
3. Run `docker-compose up -d`

## Environment variables

- `TOKEN` — Telegram bot token
- `MONGO`— URL of the mongo database

Also, please, consider looking at `.env.sample`.

# License

MIT — use for any purpose. Would be great if you could leave a note about the original developers. Thanks!
