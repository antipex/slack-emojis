slack-emojis
============

This repository stores images used for custom emojis on [Slack](https://slack.com/).

### How to download your emojis

A Slack access token is required to download emojis using the `get_emojis.py` script. You can get a token [here](https://api.slack.com/web?sudo=1).

Once you have a token you can run the following command to download your custom emojis:

```python get_emojis.py -o images <team name> <token>```
