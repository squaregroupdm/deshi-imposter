# Deshi Imposter

A Bangladesh-themed multiplayer imposter party game. One HTML file, no server to run. Everyone plays on their own phone.

**How it works**

1. One person opens the game, types a name and creates a room. They get a 4-letter code and a share link.
2. Friends open the link, type a name and join. 3 to 12 players.
3. Everyone secretly gets the same Bangla word (say, ফুচকা). The imposter only gets the category (Street Food).
4. Players take turns giving one- or two-word hints, discuss in the built-in chat, then vote.
5. Catch the imposter and every crew member scores 1. If the imposter survives the vote, or guesses the word after being caught, the imposter scores 2. Scores carry across rounds.

**Word bank:** 2,100+ words in 21 categories (street food, deshi dishes, places in Dhaka and Bangladesh, Dhaka life, village life, festivals, cricket, childhood games, and more), each shown in Bangla with the English name under it.

**Hosting:** upload `index.html` anywhere static files are served (Cloudflare Pages, GitHub Pages, Hostinger). The host's phone runs the game; players connect to it directly (PeerJS). UI in English.
