# 🔢 Jack's Numbers

### Count the footballs. Add them. Take them away. ⚽

# [▶ PLAY](https://jacks-games.github.io/numbers/)

![Jack's Numbers: 8 + 8 shown as two groups of footballs, with number tiles to pick the answer](screenshot.png)

## 🎮 How to play

### 1️⃣ &nbsp; Look at the footballs ⚽⚽⚽
Every sum is made of real footballs you can see.

### 2️⃣ &nbsp; Touch them to count 👆
Tap each ball. It says **one, two, three…** out loud and puts a number on it.

### 3️⃣ &nbsp; Pick your answer 🟨🟩🟦🟪
Four coloured tiles. Tap the right one.

### ⚽ &nbsp; GOAL!
Right answer, one football for you. Wrong one? The tile wobbles and you count again. Nothing bad happens.

## 📈 It grows with you

| | |
|---|---|
| 🐣 **To 10** | counting, plus, take away |
| 🚀 **To 20** | turn it on with the ⚙ button at the top |

Over ten, the balls line up **five in a row**, exactly like the ten frames at school — so twelve looks like *ten and two*. 

```
⚽⚽⚽⚽⚽
⚽⚽⚽⚽⚽

⚽⚽
```

## 🎯 What you get better at

- 🔢 &nbsp; Counting things you can see
- ➕ &nbsp; Adding past ten (8 + 8, 9 + 7)
- ➖ &nbsp; Taking away inside twenty (17 − 5)

## 🎈 More games for Jack

[📖 Words](https://github.com/jacks-games/words) · [🥅 Match](https://github.com/jacks-games/match) · [✏️ Letters](https://github.com/jacks-games/letters) · [🔢 Numbers](https://github.com/jacks-games/numbers) · [♟️ Chess](https://github.com/jacks-games/chess)

👉 &nbsp; All of them together: **[jackbenn.ing](https://jackbenn.ing)**

---

<details>
<summary><b>For grown-ups</b> — how it works</summary>

Every sum is represented concretely before it is abstract: the balls are countable objects, tapped one at a time with the count spoken aloud, and the marks clear after a full count so the same set can be counted again.

The **Numbers to 20** setting appends two more levels rather than replacing the first three, so turning it on never makes an earlier sum harder. Groups larger than six are laid out five to a row with a break after ten — the ten-frame representation used in Year 1, which makes bridging ten visible instead of arithmetic.

One self-contained `index.html`, no build step, no dependencies, no accounts, no tracking. Speech is the Web Speech API and starts only after the ▶ tap. Progress lives in `localStorage`.

Source of truth for all of Jack's games is the [jackbenn.ing repo](https://github.com/google814/Jack); this repo is a copy so the game has its own page and link.

```bash
python3 -m http.server 8000
```
</details>
