BACKROOMS ONLINE
================
Needs Node.js 16 or newer (https://nodejs.org). No npm install needed.

PLAY WITH FRIENDS ON YOUR WIFI / LAN
  1. Open a terminal in this folder and run:   node server.js
  2. You open  http://localhost:3000
     Friends on the same network open  http://YOUR-PC-IP:3000
  3. Multiplayer > Create room, give friends the 4 digit code.

PLAY OVER THE INTERNET
  Upload this folder to any Node host (Render, Railway, Fly.io, a VPS...).
  Start command: node server.js   (it uses the PORT the host gives it).
  Everyone opens your site's address. HTTPS works automatically (the game uses wss://).
  If you only open index.html straight from your disk instead, type your server address in
  the "Server" box in the Multiplayer screen.

MODES (host picks in the lobby): Co-op, Online Co-op (shared entities), Teams 2v2 / 4v4, Race.
Rooms hold up to 10 players. Admin spawn tools are checked on the server too.
