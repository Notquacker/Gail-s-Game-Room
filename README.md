<img src="build/icon.png" width="140" align="right" alt="Gail's Game Room icon — pixel art of Gail with Archie, Ice and Chip">

# Gail's Game Room ♥

*Eight cozy games made with love for **Gail**, starring our three babies —
**Archie**, **Ice** & **Chip** the huskies.*

| Game | What it is |
|---|---|
|  **A Little Tidier** | drag, straighten and sort things until they feel *just right* — 13 levels, 5 invented by Gail. Inspired by [*A Little to the Left*](https://alittletotheleft.com/), built 100% from scratch |
|  **Sudoku** | freshly generated puzzles (always exactly one solution), three difficulties, hints, and your progress auto-saves |
|  **Wordle** | guess the five-letter word in six tries — real English *and* Dutch words, checked against a live dictionary |
|  **Word Salad** | find the hidden words — themed around the pack, love, and home |
|  **Cipher Duel** | crack a hidden 6-digit code live online with a partner on another device — lock in your secret, then take alternating turns, with a coin flip deciding who guesses first — or go solo against **Ice** |
|  **Lucky Number** | type logic rules (`even`, `>40`, `cijfersom<=7`, `tussen20-30`, `dubbelecijfers`, …) to narrow a grid of numbers down to one — play 1–100 or 1–1000 |
|  **Code Vault** | classic Mastermind: crack a hidden 4-peg code (each color used at most once) in 10 tries using black/white peg feedback — solo against **Chip**, or online where one partner locks the code and the other cracks it |
|  **Hangman** | guess the word one letter at a time before a cowboy gets fully strung up — a Wordle-style keyboard tracks every letter you've tried. Solo against **Archie**, or online where one partner picks a real word (checked live against a dictionary) and the other guesses it |

Open the game, land on a **home screen**, pick a game from the **game room** menu, and every
game shares the same pastel look, pause menu, and husky supervision from the corner.

---

## 1 · How to get the game

| Way | How | Best for |
|---|---|---|
|  **Play in the browser** | Open **https://notquacker.github.io/Gail-s-Game-Room/** | Phones, tablets, any computer — always the newest version |
|  **Windows app** | **[⬇ Download the exe](https://github.com/Notquacker/Gail-s-Game-Room/releases/latest)** (under *Assets*) | Playing like a real desktop game |
|  **From source** | See [Building it yourself](#building-it-yourself) below | Developers / the curious |

## 2 · How to install

**There is nothing to install.** The Windows app is a *portable* exe:

1. Copy the downloaded `.exe` anywhere (Desktop is fine).
2. Double-click it. The first start takes a few extra seconds — it's unpacking itself.
3. If Windows shows a blue **"Windows protected your PC"** screen, that's only because
   the app isn't code-signed (that costs money). Click **More info → Run anyway**. Once.

The app is self-updating in spirit: when you're online it loads the newest version
of the game from the internet, and when you're offline it plays the copy built into
the exe. New levels appear automatically — you never need a new exe.

## 3 · How to play

Every game has a **pause button** (⏸): resume, restart (the same puzzle/level, not a new
one), jump to **choose a game**, or go all the way **home**. Click **Archie, Ice or Chip** in
the corner any time for an awooo 🐺 — they wag and blink on their own too.

###  A Little Tidier

**Goal:** every level shows something slightly untidy. Make it *just right*.
When something is placed correctly it clicks into place with a chime and a sparkle .
Finish all of them and there might be a message waiting at the end… 

| Input | What it does |
|---|---|
| **Drag** an object | Move it (sorting, aligning, placing) |
| **Drag sideways** on a crooked object | Rotate it upright |
| **?** button (top right) | Shows a ghost hint of the solution for a few seconds |

There's a **level menu** — finished levels get a pink heart, and progress is saved on your device.

**The levels**

1. **Straighten Up** — three crooked picture frames; make them hang straight
2. **Hang Together** — hang the frames on one invisible line
3. **Pencil Parade** — sort the pencils from shortest to tallest
4. **Handle With Care** — set the wonky mugs down straight (one has a paw on it )
5. **Rainbow Shelf** — sort the books into rainbow order
6. **Treat Time** — sort the dog biscuits from smallest to biggest, one per hungry baby
7. **Drawer Order** — put every piece of cutlery on its matching outline
8. **Build a Bouquet** — drop the flowers into the vase 
9. **Closet Cleanup** — hang, fold and tuck everything away 
10. **Puppy Puzzle** — rebuild the picture of the pup 
11. **Potion Time** — pour the colours into the cauldron in recipe order 
12. **Nail Salon** — paint every nail pink 
13. **Love Letters** — spell a very important name 

*(Levels 8–12 were invented by Gail herself.)*

###  Sudoku

Tap a cell, then a number on the pad (or your keyboard) to fill it in. Wrong numbers turn red
if they clash with their row, column or box. Pick **easy / medium / hard** any time — re-picking
the mode you're already on won't touch your progress, only switching modes starts a new puzzle.
The **?** button fills in one correct number for you (your selected cell if it needs help,
otherwise a random one) — hinted numbers get a soft gold tint. Your board **auto-saves**, so
closing the app or switching games and coming back resumes exactly where you left off.

###  Wordle

Type (or tap the on-screen keyboard) a 5-letter word and press **Enter**. Green = right letter,
right spot; yellow = right letter, wrong spot. Real English words are checked live against a
free dictionary; a curated set of Dutch words works too (see [`words.json`](words.json)) — anything
else gets rejected with a little shake, without costing you a guess.

###  Word Salad

Drag across letters — in any of 8 directions — to select a word from the themed word list
below the grid. Found words get crossed off and highlighted in the grid.

###  Cipher Duel

Type a room code and tap **join room** — whoever's on the other end, on any device, joins the
same live duel over the network. Build your 6-digit secret and tap **lock in** (it can't be
changed after that); once you're both locked in, we flip a coin to see who guesses first, then
you take strict alternating turns — a digit turns green the instant your partner confirms it's in
the right spot. The paw button switches to solo mode against **Ice** instead: she hides her own
code for you to guess, and her **Ice's turn** button makes her guess back at yours, one row per
tap — she remembers every wrong digit and deduces the last one for free once nine are ruled out.
Your board **auto-saves** in solo mode.

###  Code Vault

Classic Mastermind. Online, one player locks in a secret 4-peg code — 6 colors to choose from,
each usable only once — (tap a color swatch to fill the next empty slot) and the other gets 10
tries to crack it — each guess comes back with black
pegs (right color, right spot) and white pegs (right color, wrong spot), but never *which* peg is
which, so it's real deduction. Roles are assigned automatically when you both join a room. The paw
button switches to solo mode against **Chip**, who's already locked in a random code for you to
crack — no setup needed, just start guessing. Solo sessions **auto-save**.

###  Hangman

Guess the word one letter at a time — a Wordle-style on-screen (and real) keyboard shows every
letter you've tried, green for a hit and grey for a miss. Guess wrong too many times and the
cowboy ends up fully strung up from the gallows. Online, one player picks a secret word (5+
letters) — checked live against a dictionary before it locks in, though an unrecognized word
(a name, Dutch, just obscure) can still be locked in on purpose — and the other player guesses it,
with the word-picker able to watch the guesses land in real time. The paw button switches to solo
mode against **Archie**, who's already picked a word for you to crack — no setup needed. Solo
sessions **auto-save**.

###  Lucky Number

Pick **1–100** or **1–1000** with the two buttons up top (switching modes starts a fresh grid).
Type logic rules — `even`, `oneven`/`odd`, `>40`, `<=87`, `==12`, `dubbelecijfers`/`doubledigits`
(a two-digit number), `deelbaardoor5`/`divided5` (divisible by), `tussen20-30`/`between20-30`, or
the shorthand symbols `:5` (gedeeld door / divided by) and `x5` (tafel van / multiples of) —
comma-separated or one at a time, and press Enter. Both Dutch and English keywords work side by
side. The digit-sum rule (`cijfersom`/`sum`/`digitsum`) takes any comparison too — `cijfersom=7`,
`cijfersom<=7`, `sum>=5` — or `cijfersom=even`/`cijfersom=oneven` to test the digit sum's own
parity. Every
rule narrows the grid down further; matching numbers light up. Click a rule chip to remove
it, or click any number in the grid to cross it off as "already guessed." Narrow it down to exactly
one and the pack celebrates. Your rules and crossed-off numbers **auto-save**.

## 4 · How it's made (the nerdy part)

Hand-written HTML, CSS and vanilla JavaScript — no frameworks, no build step, no npm
dependencies at runtime. [`index.html`](index.html) is the home screen / game picker;
[`tidier.html`](tidier.html), [`sudoku.html`](sudoku.html), [`wordle.html`](wordle.html),
[`salad.html`](salad.html), [`cipherduel.html`](cipherduel.html), [`luckynumber.html`](luckynumber.html),
[`codevault.html`](codevault.html) and [`hangman.html`](hangman.html) are the eight games, each its
own page. [`shared.css`](shared.css) and [`shared.js`](shared.js) hold the common look, sounds,
sparkles and the husky pack so every page shares them instead of repeating the code.

-  **All the art is code.** Every frame, pencil, mug, biscuit, spoon and husky is an
  inline **SVG drawn by JavaScript functions** — shapes, gradients and paths, zero image
  files. (The only bitmaps in the whole project are the app icon and its favicon.)
-  **All the sound is code too.** The chimes, fanfares and the husky howl are
  generated live with the **WebAudio API** — oscillators, no audio files.
-  **The font** is [Geist Pixel](https://fonts.google.com/specimen/Geist+Pixel) from Google
  Fonts, with system handwriting fonts as offline fallbacks.
-  **Wordle's word list** lives in [`words.json`](words.json) — a plain JSON array, loaded
  with `fetch()` — and guesses outside that list are validated live against the free
  [Dictionary API](https://dictionaryapi.dev/) (English only; it quietly lets a guess through
  if there's no internet to check it).
-  **Progress is saved with `localStorage`:** which Tidier levels are finished, Sudoku's
  current puzzle/entries/difficulty, Cipher Duel's solo-vs-Ice state, Code Vault's solo-vs-Chip
  state, Hangman's solo-vs-Archie state, and Lucky Number's range/rules/crossed-off numbers — all
  survive closing the app. Online rooms in Cipher Duel, Code Vault and Hangman are session-only
  and don't persist.
-  **Online duels run on [Supabase Realtime](https://supabase.com/realtime):** Cipher Duel, Code
  Vault and Hangman use it purely as a live relay (Broadcast + Presence channels, no database) —
  secrets never leave the device that owns them, only guesses and verdicts get sent over the wire.
-  **The desktop app is [Electron](https://www.electronjs.org/):** [`main.js`](main.js)
  opens a window and loads the game room into it. [`electron-builder`](https://www.electron.build/)
  packs it into a single portable exe. (See [`ELECTRON.md`](ELECTRON.md) for a crash course.)
-  **Updates are free via GitHub Pages:** this repo *is* the website. Every
  `git push` puts new content online, and the app loads it on next launch.
  (See [`UPDATES.md`](UPDATES.md).)
-  The game design doc lives in [`PROMPT.md`](PROMPT.md).

Made in 2026 by **Xayvion**, together with Claude (Anthropic) — for Gail,
supervised at all times by Archie, Ice and Chip.

## Building it yourself

```powershell
git clone https://github.com/Notquacker/Gail-s-Game-Room.git
cd Gail-s-Game-Room
npm install        # fetches Electron & tooling (one time)
npm start          # play as a desktop app
npm run dist       # build the portable exe into dist/
```

Or skip all of that — `index.html` runs by just opening it in a browser. That's the point. 🙂
