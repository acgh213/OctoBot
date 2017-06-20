# Octeon
[![Documentation Status](https://readthedocs.org/projects/octeon/badge/?version=latest)](http://octeon.readthedocs.io/en/latest/?badge=latest)
## A modular telegram bot
### Installation

1. `cp settings.example.py settings.py`

2. Write your settings in file `settings.py`:
    - `CHANNEL` - Put here an channel where Octeon is admin. This is required for using images in inline
    - `TOKEN` - Bot token. You can get one from t.me/botfather

3. `pip3 install python-telegram-bot` - This is Bot API wrapper which Octeon use

3. `pip3 install emoji praw requests` - Requirments for some modules

### Creating your own plugins

See plugin/Example.py

It is base plugin, and has a lot of comments to get you started