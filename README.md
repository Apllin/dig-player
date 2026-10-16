# dig-player

A Telegram Mini App that plays a list of tracks in order through YouTube's and
SoundCloud's own embedded players.

The page is static. The track list travels in the URL fragment (`#t=…`), which
browsers never send to the server: nothing about what is played reaches this
site, and nothing is stored.
