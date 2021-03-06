# podcast-to-youtube

The perfect tool to post any podcast episode to YouTube.
Everything you need is:

- A RSS feed
- Docker
- Make

## Download client_secrets.json

You will need a service account for this to work. First go to https://console.cloud.google.com
and create a new project.

Then visit the [API manager for YouTube Data API](https://console.cloud.google.com/apis/api/youtube/overview),
enable it.

Now you need to create a new OAuth2 Client ID and download the `json` file. Save it in the
directory containing this file as `client_secrets.json`.

## Run it

Simply run `make run` and you're done!

See how it looks like in this [short screencast](https://www.youtube.com/watch?v=n8R_00NCCDQ):

[![podcast to youtube screencast](https://img.youtube.com/vi/n8R_00NCCDQ/0.jpg)](https://www.youtube.com/watch?v=n8R_00NCCDQ)

## Disclaimer

This is not an official Google product (experimental or otherwise), it is just
code that happens to be owned by Google.
