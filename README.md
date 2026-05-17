# ChessTime ♟️

**A multiplayer chess app built for long-distance couples.**  
Play chess with your partner over a live video call, with an animated AI coach, in-game chat, and match history — all in real time.

---

## Screenshots

> <img width="590" height="1278" alt="IMG_1409" src="https://github.com/user-attachments/assets/24510cd3-d1eb-45b8-aab4-29e1a9ec75d8" />
<img width="590" height="1278" alt="IMG_1410" src="https://github.com/user-attachments/assets/09bb74de-8576-4f90-a755-d168fe9420a5" />


---

## Features

**Multiplayer**
- Create a private game and share a link — your partner joins instantly, no account needed on their end
- Real-time board sync via Firebase Realtime Database
- Live video calling powered by WebRTC, built directly into the game screen
- In-game text chat

**AI Coach**
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

## Project Structure

```
auth.js          — Google sign-in / sign-out
board.js         — Board rendering and move logic
pieces.js        — Piece definitions and movement rules
game.js          — Game state, Firebase sync, turn management
robot.js         — Stockfish integration, AI coach animations and sound
chat.js          — Real-time in-game chat
webrtc.js        — Peer-to-peer video call logic
profile-menu.js  — Player profile UI
fluid-bg.js      — Animated background
main.js          — App entry point
```

---

## About

Built as a personal project to stay connected with my partner during time apart. Designed and developed solo.
