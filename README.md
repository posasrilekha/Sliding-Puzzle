

## **README.md**

# Sliding Puzzle Game (3×3)

A simple, interactive 3×3 sliding puzzle built using **HTML, CSS, and JavaScript**. The goal is to arrange the tiles in order by sliding them into the empty space. The game includes real-time **timer tracking**, **step counting**, and **win detection**.

---

## 🚀 Features

* 3×3 classic sliding puzzle
* Randomized puzzle layout on each refresh
* Click-based tile movement
* Real-time timer
* Step counter
* Win detection with a success message
* Clean UI built with CSS Grid

---

## 🎮 How to Play

1. Click a tile adjacent to the empty space.
2. It will slide into the empty spot.
3. Keep rearranging the tiles until they are in order:
   `1 2 3 4 5 6 7 8 _`
4. When solved, the game stops the timer and displays a win message.

---

## 📂 Project Structure

```
/sliding-puzzle
│── index.html     # Main game file
│── (No external JS or CSS files, fully self-contained)
```

---

## 🛠 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla)**

---

## ▶️ Run the Game

Just open `index.html` in any modern browser — no setup required.

---

## 🔧 Code Highlights

* Puzzle is rendered dynamically using DOM manipulation
* Fisher–Yates shuffle used to randomize tiles
* Movement rules based on grid adjacency
* Win check based on sequential tile match

---

