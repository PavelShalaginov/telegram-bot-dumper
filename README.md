# telegram-bot-dumper

Easy dumping of all Telegram bot stuff.

**Input**: only bot token.

**Output**: bot name & info, all chats text history & media, bot's users info & photos.

## Requirements

- Python 3.6
- Telethon >= 1.8.0
- [Register Telegram application](https://core.telegram.org/api/obtaining_api_id) to get API_ID and API_HASH

## Using

```sh
pip install -r requirements.txt

vi dumper.py # change API_ID and API_HASH and save

./dumper.py --token 12345678:ABCe2rPVteUWZ7wLeCqCb3CH3ilUY_fLabc
```

Also you can use `--tor` flag for Telegram blocking bypass.

## Token leaks

Dorks examples: [telepot.bot](https://github.com/search?q=telepot.bot&type=Code)
