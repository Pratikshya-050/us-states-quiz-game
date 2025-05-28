# 🗺️ U.S. States Quiz Game

An interactive Python game that helps users learn and memorize all 50 U.S. states. The game uses the Turtle graphics library to display a blank map of the U.S., and the player is prompted to enter state names. Correct answers appear in their geographic location on the map.

![Screenshot 2025-05-28 234447](https://github.com/user-attachments/assets/01b8572b-2883-422d-8d03-759916642fc0)


## 📂 Project Structure

```
us-states-quiz-game/
├── main.py                # Main Python script with game logic
├── 50_states.csv          # Contains names and coordinates of U.S. states
├── states_to_learn.csv    # Automatically generated list of missed states
└── blank_states_img.gif   # Image of the U.S. map used for the game
```

## 🎮 How to Play

1. Run the `main.py` script.
2. A U.S. map will appear.
3. Enter state names in the pop-up textbox.
4. Correct guesses will be displayed on the map.
5. Type `Exit` to stop the game and save unguessed states to `states_to_learn.csv`.

## 🛠️ Requirements

- Python 3.x
- `pandas`
- `turtle` (built-in with Python)

Install `pandas` if needed:
```bash
pip install pandas
```

## 📈 Learning Feature

If you exit the game before guessing all states, a file called `states_to_learn.csv` will be generated. This helps you focus on the states you missed!


## 🌟 Star This Repo

If you found this useful or fun, consider starring ⭐ the repository!
