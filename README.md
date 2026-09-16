# 🏀 Basketball Scoreboard

A sleek, interactive basketball scoreboard built with **HTML**, **CSS**, and **JavaScript**. Designed to keep track of scores for two teams — **Home** and **Guest** — with a stunning dark-theme UI and smooth score increment controls.

## ✨ Features

- **Dual-Team Scoreboard** — Track scores for Home and Guest teams side by side
- **Customizable Scoring** — Add **+1**, **+2**, or **+3** points per team with dedicated buttons
- **One-Click Reset** — Instantly reset both scores to zero
- **Modern Dark Theme** — Deep navy-blue background (`#1b234a`) with high-contrast white and black elements
- **Gradient Text Effect** — Score numbers feature a radial gradient (red accents) for a polished, professional look
- **Fully Responsive** — Clean flexbox layout that adapts to different screen sizes

## 📸 Preview

The scoreboard displays two large score boxes (`250×250px`) with **100px** font-size numbers, each flanked by three scoring buttons (`+1`, `+2`, `+3`). A prominent **RESET** button sits below to clear all scores.

| Element | Description |
|---------|-------------|
| `#sq-box1` | Home team score box |
| `#sq-box2` | Guest team score box |
| `#num1` / `#num2` | Score display with gradient text effect |
| `+1`, `+2`, `+3` buttons | Score increment buttons per team |
| `#reset-all` | Reset all scores to 0 |

## 🛠️ Technologies Used

- **HTML5** — Structure and semantic layout
- **CSS3** — Styling, gradients, flexbox, responsive design
- **JavaScript** — Interactive score logic and DOM manipulation

## 🚀 Getting Started

1. **Clone or download** this repository
2. Open `index.html` in any modern browser
3. Start scoring! 🎉

### File Structure

```
scoreboard/
├── index.html      # Main HTML structure
├── index.css       # Styling and layout
├── index.js        # Scoreboard logic
└── README.md       # Project documentation
```

## 📄 How It Works

The JavaScript file (`index.js`) hooks into the DOM elements and provides simple arithmetic functions:

- `add1()` / `addOne()` — Adds **1** point to the respective team
- `add2()` / `addTwo()` — Adds **2** points
- `add3()` / `addThree()` — Adds **3** points
- `resetGame()` — Resets both scores to **0**

Each function reads the current text content of the score box, converts it to a number, adds the increment, and updates the display.

## 🎨 Design Highlights

- **Background**: Deep navy blue (`#1b234a`) for a professional sports-broadcast feel
- **Score Boxes**: Solid black containers with centered, large numerals
- **Gradient Text**: Radial gradient overlay creating a striking red-on-transparent number effect
- **Buttons**: Transparent with white borders and rounded corners for a clean, minimalist aesthetic
- **Typography**: Large `50px` labels, `100px` scores, and appropriately sized buttons

## 🔧 Customization

Feel free to customize:
- **Colors** — Modify `#1b234a` and the gradient in `index.css`
- **Starting Scores** — Change the initial values (`12` and `5`) in `index.html`
- **Button Labels** — Adjust `+1`, `+2`, `+3` to match your sport's scoring rules
- **Dimensions** — Resize boxes and buttons in `index.css`

## 📝 License

This project is open-source and available for anyone to use and modify.

---

**Built with ❤️ for clean, beautiful scoring experiences.**
