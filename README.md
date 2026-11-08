# প্রতারক-চক্র (Deshi Imposter)

A Bangladesh-themed multiplayer imposter party game. One HTML file, no server to run. Everyone plays on their own phone.

**How it works**

1. One person hosts a game. They get a 6-digit game PIN and a share link.
2. Friends open the link or type the PIN and a nickname. 3 to 12 players. Everyone sits around a table on screen.
3. Everyone secretly gets the same Bangla word (say, ফুচকা). The imposter only gets the category, the first letter and the letter count.
4. Players take turns putting a one-word hint on the table (30 seconds each), discuss in the built-in chat, then vote (45 seconds).
5. Catch the imposter and every crew member scores 100. If the imposter survives the vote, or guesses the word after being caught, the imposter scores 200. A leaderboard shows after every round.

**Word bank:** 2,100+ words in 21 categories (street food, deshi dishes, places in Dhaka and Bangladesh, Dhaka life, village life, festivals, cricket, childhood games, and more), each shown in Bangla with the English name under it.

**Hosting:** upload `index.html` anywhere static files are served (Cloudflare Pages, GitHub Pages, Hostinger). The host's phone runs the game; players connect to it directly (PeerJS). UI in English.
