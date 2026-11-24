# Forgotten Favorites

Finds songs you used to play on repeat and then stopped. Load your Spotify data export, browse by era, and turn any era into a private Spotify playlist.

- Your listening history is processed and saved only in your browser. It is never uploaded.
- Spotify sign-in (PKCE, no server) is used only to look up songs and create private playlists.
- Best with Spotify's **Extended streaming history** export (Account → Privacy settings → Download your data).

## Spotify setup (one time)
1. Create an app at https://developer.spotify.com/dashboard (needs Spotify Premium).
2. Add the page's address as a Redirect URI, e.g. `https://<you>.github.io/forgotten-favorites/`.
3. Tick **Web API**, save, then paste the Client ID into the page and click **Connect Spotify**.
