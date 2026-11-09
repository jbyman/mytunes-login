# mytunes login

The HTTPS return page for mytunes's Spotify login. Spotify only redirects to HTTPS or loopback addresses, and mytunes runs on a home network at http://mytunes.local. This page passes Spotify's one-time code straight back to mytunes. The code is useless without the PKCE verifier, which only the mytunes server holds, and nothing is stored here.

The app itself lives in the private repo jbyman/spotify-cleanup.
