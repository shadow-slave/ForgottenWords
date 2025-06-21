
# 📖 Forgotten Words Dictionary 
[Live Demo](https://shadow-slave.github.io/ForgottenWords/index.html)

*Rediscover lost language, one card at a time.*

**Forgotten Words Dictionary** is an interactive and beautifully styled web app that introduces users to rare or forgotten words each day. Designed for vocabulary enthusiasts and curious minds, the app lets users flip up to three word cards daily and revisit collected words with filters based on origin.

---

## 📚 Table of Contents

* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Configuration](#configuration)
* [Dependencies](#dependencies)
* [File Structure](#file-structure)
* [Screenshots](#screenshots)
* [Troubleshooting](#troubleshooting)
* [Contributors](#contributors)
* [License](#license)

---

## ✨ Features

* 🎴 Flip up to **3 unique words per day**
* 🧠 Learn definitions, origins, and usage examples
* 🕯️ Filters by word origin (Latin, Greek, etc.)
* 🌙 Dark mode toggle with persistence
* 📦 LocalStorage persistence of word history
* 📱 Responsive and mobile-friendly
* 🎨 Elegant UI styled with custom CSS and Bootstrap

---

## 🛠️ Installation

1. Clone or download this repository:

   ```bash
   git clone https://github.com/your-username/forgotten-words.git
   cd forgotten-words
   ```

2. Open `index.html` in your browser directly, or run a local server (e.g., with VSCode Live Server).

---

## 🚀 Usage

* Visit the main page (`index.html`) to see today's new words.
* Click on a card to flip it and reveal the word's meaning.
* Flip up to **3 words per day**.
* Click **"View collected words"** to see your previously flipped words.
* Use the origin filter on the viewed page to refine your list.
* Toggle 🌙/☀️ mode using the top-right button.

---

## ⚙️ Configuration

No server setup or external API is required. All word data is stored in `s.js`.

You may modify or expand the word list in the array inside `s.js`:

```javascript
const words = [
  { word: "Apricity", meaning: "...", origin: "Latin", example: "..." },
  ...
];
```

---

## 📦 Dependencies

* **[Bootstrap 5](https://getbootstrap.com/)** – for alert styling and responsive utilities
* **LocalStorage** – for tracking daily and viewed words
* **Custom CSS** – `styles.css` and `viewed.css` for styling and themes

---

## 📁 File Structure

```
├── index.html             # Main app interface
├── viewed.html            # Viewed/collected words interface
├── s.js                   # JavaScript logic for word handling
├── styles.css             # Core styles and card animations
├── viewed.css             # Additional styling for viewed.html
```

---

## 🖼️ Screenshots
![Screenshot 2025-06-22 004330](https://github.com/user-attachments/assets/49481fb5-0439-4e4e-b461-21908d842279)
![Screenshot 2025-06-22 004347](https://github.com/user-attachments/assets/aa117b2f-6464-40ac-a395-67d968eadb20)
![Screenshot 2025-06-22 004404](https://github.com/user-attachments/assets/7070a6ad-b553-4558-b4ec-414353f4d31a)
![Screenshot 2025-06-22 004417](https://github.com/user-attachments/assets/fcd26eb0-3713-41bf-b80a-56b086246b9f)



---

## ❗ Troubleshooting

* **Not seeing new words today?** Try again tomorrow; the limit is 3 flips per day.
* **All words viewed?** The app resets the pool once all words have been seen.
* **Dark mode not saving?** Make sure your browser allows LocalStorage access.

---

## 👥 Contributors

*ASWIN TS – [GitHub](https://github.com/shadow-slave)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

