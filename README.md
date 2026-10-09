# FanPulse AI 🏏⚽

**Understand the match, even if you're new to the sport.**

FanPulse AI is a simple web app that helps casual fans follow live sports. It shows a sample scoreboard and explains the match in plain, beginner-friendly language.

🔗 **Live app:** https://aryxncoder.github.io/FanPulse.AI/

> ⚠️ **Demo data only.** All teams, scores and stats in this app are made up. It does not show real or live match information.

## The Problem

During live matches, casual fans often struggle to understand the score, the match situation, and important statistics like run rate, possession or cards.

## Features

- Choose between **Cricket** and **Football**
- Sample live-style **scoreboard** with score, time/overs and match status
- **AI Fan Explainer** with three buttons:
  - Explain the match situation
  - What happens next?
  - Explain the key stats
- Simple, beginner-friendly explanations using predefined demo responses
- Clean, mobile-friendly **dark sports theme**
- No backend, no paid API, no installation

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla)

Everything is in a single file: `index.html`.

## Run Locally

1. Download or clone this repository:
```bash
   git clone https://github.com/aryxncoder/FanPulse.AI.git
```
2. Open `index.html` in any web browser.

## Customize the Demo Data

Open `index.html` and edit the `MATCHES` object inside the `<script>` section to change team names, scores, stats and explanations.

## Deploy with GitHub Pages

1. Push `index.html` to the root of your repository.
2. Go to **Settings → Pages**.
3. Set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, then click **Save**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## AI Tools Used

- **Claude (Anthropic)** was used to help design and write the code and the demo explanations.

## Future Ideas

- Connect to a real sports data source
- Replace demo responses with a live AI model
- Add more sports

---

Made as a demo project. All match data is fictional.
