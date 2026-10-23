# Retro Bowl web game

This folder contains the Retro Bowl HTML5 game and the files it needs to run locally. The source archive's `retro-bowl-unblocked.html` page only embedded the game from Kongregate, so the referenced game assets were collected into this self-contained folder.

## Run it

Opening `index.html` directly may be blocked by browser security rules because the game loads data files with web requests. Serve the folder over local HTTP instead:

1. Open Terminal.
2. Change into this folder.
3. Run:

   ```sh
   python3 -m http.server 8765
   ```

4. Open <http://localhost:8765> in a browser.

Stop the server with `Control-C` in Terminal.

Saved games are stored by the browser for the local site, not as files in this folder.
