# 🃏 Teen Patti (3 Patti) - Web Game

A classic browser-based implementation of **Teen Patti** (Indian Poker), built with vanilla web technologies and hosted on GitHub Pages.

🔗 **Live Demo:** [https://rahulmanne.github.io/TeenPatti/](https://rahulmanne.github.io/TeenPatti/)

---

## 📖 About the Project

Teen Patti is a popular three-card gambling/strategy card game originating in the Indian subcontinent, closely related to the English game of Three-Card Brag. This project brings the traditional tabletop card game experience directly to the web browser without requiring any installations or backend servers.

### ✨ Key Features
* **Classic 3-Card Gameplay:** Authentic Teen Patti hand rankings and turn-based betting mechanics.
* **Interactive UI:** Clean card dealing, betting controls (*Blind*, *Chaal*, *Pack*, *Show*), and real-time pot tracking.
* **Zero Dependencies:** Lightweight frontend built purely with standard web technologies for fast loading via GitHub Pages.
* **AI / Bot Opponents:** Play against computer-controlled players right out of the box.

---

## 🎯 Hand Rankings (Highest to Lowest)

1. **Trail / Trio (Three of a Kind):** Three cards of the same rank (e.g., `A♠ A♥ A♦`).
2. **Pure Sequence (Straight Flush):** Three consecutive cards of the same suit (e.g., `K♥ Q♥ J♥`).
3. **Sequence (Straight):** Three consecutive cards not all in the same suit (e.g., `9♠ 8♦ 7♣`).
4. **Color (Flush):** Three cards of the same suit not in sequence (e.g., `K♠ 10♠ 4♠`).
5. **Pair (Two of a Kind):** Two cards of the same rank (e.g., `Q♦ Q♣ 5♥`).
6. **High Card:** Highest-ranking single card when none of the above hands are formed.

---

## 🛠️ Built With

* **HTML5** – Game structure and layout
* **CSS3** – Card styling, table aesthetics, and animations
* **JavaScript (ES6+)** – Deck shuffling, hand evaluation logic, betting state, and bot AI
* **GitHub Pages** – Static site hosting
 
 ---

## 🗺️ Roadmap & Future Improvements

- [ ] **Responsive Mobile Layout:** Optimize table positioning and touch controls for smaller screens.
- [ ] **Sound Effects & Animations:** Add card flip transitions, chip stacking sounds, and win/loss cues.
- [ ] **Persistent Chip Balance:** Save player bankrolls across sessions using `localStorage`.
- [ ] **Game Variations:** Add popular variants like *Muflis* (Lowball), *AK47*, and *Joker*.
- [ ] **Multiplayer Mode:** Integrate WebSockets (Socket.io / PartyKit) for real-time play with friends.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
