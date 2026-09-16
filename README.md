# 🇺🇸 U.S. States Game

An interactive **U.S. States Guessing Game** built with **Python, Turtle, and Pandas**.

The goal of the game is to guess all **50 U.S. states**. When you correctly guess a state, its name is displayed on the map at the correct location.

## 🎮 How It Works

1. A blank map of the United States is displayed.
2. Enter the name of a U.S. state in the input box.
3. If the answer is correct, the state name appears on the map.
4. The counter keeps track of how many states you have guessed.
5. Type **"Exit"** to stop the game.
6. When you exit, the program creates a CSV file containing the states you still need to learn.

## 🛠️ Technologies Used

* **Python**
* **Turtle** — for creating the interactive map
* **Pandas** — for reading and processing the CSV data
* **CSV** — for storing state names and coordinates

## 📂 Project Structure

```text
US-States-Game/
│
├── main.py
├── 50_states.csv
├── blank_states_img.gif
├── states_to_learn.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd US-States-Game
```

### 3. Install Pandas

```bash
pip install pandas
```

### 4. Run the game

```bash
python main.py
```

## 🎯 Example

If you enter:

```text
Texas
```

The game will place **Texas** on the correct position on the map.

The progress will also update:

```text
5/50 Correct State
```

## 📚 Learning Purpose

This project helped me practice:

* Python loops
* Lists
* Conditional statements
* Functions and modules
* File handling
* CSV data
* Pandas DataFrames
* Data filtering
* Turtle graphics
* User input
* Working with coordinates

## 🚀 Future Improvements

Possible improvements include:

* Add a timer
* Add a scoring system
* Add hints
* Show the final score
* Improve the exit functionality
* Add difficulty levels
* Add sound effects
* Create a graphical start/restart screen

## 👨‍💻 Author

**Ismaeel**

Built as a Python learning project to practice **Turtle graphics and Pandas**.
