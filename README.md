# Whack Angy Diggy

**Whack Angy Diggy** is a fast-paced, reflex-testing Progressive Web App (PWA) game built entirely in a single `index.html` file using HTML, CSS, and JavaScript.

🎯 Tap on the **AngyDiggy** image to score points.  
🚫 Tap a **red circle** and you'll lose a point.  
⏱ You have 60 seconds. Choose your difficulty and get whacking!

---

## 🚀 Features

- ✅ **Single-file game** – Easy to deploy, fork, or customize
- ⚙️ **Difficulty settings** – Easy (2s), Medium (1s), Hard (0.5s)
- 📱 **PWA support** – Installable on Android and iOS
- 🔌 **Offline-ready** – Works without internet after first load
- 🎮 **Live scoring and leveling** – Levels increase every 10 points
- 🖥️ **Fixed-size game board** – 800x600 px for a consistent experience

---

## 📥 Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/whack-angy-diggy.git
cd whack-angy-diggy
```

### 2. Add Assets

Make sure you have `AngyDiggy.png` (your target image) in the same directory as `index.html`.

### 3. Run the Game

You can either:
- Open `index.html` directly in your browser, **or**
- Serve locally using a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code

### 4. Install as a PWA (Optional)

#### ✅ Android (Chrome or Edge)
- You should see an install prompt automatically
- Or use the browser menu → *Add to Home Screen*

#### 🍎 iOS (Safari)
- Open `index.html` in Safari
- Tap the **Share** icon → *Add to Home Screen*
- PWA meta tags are included for iOS compatibility

---

## 🎮 How to Play

1. Click **Start Game**
2. Choose your difficulty:
   - **Easy** → 2 seconds per target
   - **Medium** → 1 second
   - **Hard** → 0.5 seconds
3. Tap targets as they appear:
   - 🐾 **AngyDiggy** = +1 point
   - 🔴 **Red Circle** = -1 point
4. Game ends after 60 seconds. Your score is displayed.
5. Level increases every 10 points.

---

## 🔧 Customization

| Feature               | How to Change                                      |
|-----------------------|----------------------------------------------------|
| Game Duration         | Change the `timeLeft` variable in the script       |
| Target Sizes          | Adjust the `#target` width/height in CSS           |
| Board Dimensions      | Modify `#gameContainer` width and height in CSS    |
| Difficulty Timers     | Update `autoHideTime` values in the JS logic       |
| Game Icon             | Replace `AngyDiggy.png` with your own image        |
| Target Appearance     | Update the styles or image in the JS `moveTarget()` function |

---

## 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- PWA features (Service Worker + Manifest)

---

## 🤝 Contributing

Pull requests are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to fork the repo and open a PR.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- Inspired by classic Whack-a-Mole gameplay
- Created for kids who love fast games and funny images 🐵
- Special thanks to Lucas & Caleb for inspiration 💙
