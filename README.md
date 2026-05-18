<p align="center">
  <img src="https://github.com/user-attachments/assets/1823bd4f-9f57-4d80-9298-7ebe69ddfa22" width="150"/>
</p>

# ChessTime ♟️

**A multiplayer chess app built for long-distance couples.**  
Play chess with your partner over a live video call, with an animated AI coach, in-game chat, and match history — all in real time.

🌐 **[Live App](https://chess-web-app-26069.web.app)**

---

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/24510cd3-d1eb-45b8-aab4-29e1a9ec75d8" width="200" height="433"/>
  &nbsp;
  <img src="https://github.com/user-attachments/assets/ad8d6e95-e349-410c-9bac-5eeb83f77759" width="200" height="433"/>
  &nbsp;
  <img src="https://github.com/user-attachments/assets/b33ae822-674d-47b6-bae9-6d0095c153a3" width="200" height="433"/>
  &nbsp;
  <img src="https://github.com/user-attachments/assets/faadaa41-d018-424c-89f7-be1a9a0ed308" width="200" height="433"/>
</p>

---

## Features

**Multiplayer**
- Create a private game and share a link — your partner joins instantly, no account needed on their end
- Real-time board sync via Firebase Realtime Database
- Live video calling powered by WebRTC, built directly into the game screen
- In-game text chat

**AI Coach (the Robot)**
- Tap the animated robot at any time to get move suggestions powered by Stockfish (depth 14, top 3 moves)
- Suggestions are displayed as color-coded arrows on the board with evaluation scores (+1.4, Mate in 3, etc.)
- The robot has a full idle animation system: it blinks, bounces, tilts, whistles melodies (Star Wars, Harry Potter, Spider-Man...), falls asleep, and reacts to moves
- All robot animations are synced via Firebase so both players see the exact same behavior simultaneously

**Accounts & Profiles**
- Google Authentication
- Custom player name and avatar photo
- Partner email and reunion date settings
- Match history with outcome and timestamp

**vs Computer mode**
- Play solo against the minimax AI

**Design**
- Dark, glowing aesthetic with animated fluid background
- Heart motif replacing the king piece
- Light/dark mode toggle

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla JavaScript, HTML, CSS |
| Real-time sync | Firebase Realtime Database |
| Authentication | Firebase Auth (Google) |
| Hosting | Firebase Hosting |
| Video calling | WebRTC |
| Chess engine | Stockfish (Web Worker) |

---

## About

Built as a personal project to stay connected with my partner during time apart. Designed and developed solo.
