# 🏆 Leaderboard

A Python program that processes user-entered name and score pairs, builds a leaderboard, sorts it in descending order by score, and displays the top 3 performers.

## ✨ Features

- Accepts space-separated input in the form: `Name Score Name Score ...`
- Separates names and scores using slicing
- Converts scores to integers with `map()`
- Combines names and scores using `zip()`
- Sorts leaderboard with a custom `key` function
- Displays:
  - Full sorted leaderboard with ranks
  - Top 3 performers

## 💡 Example

### ▶️ Input 
Ram 92 sita 85 geeta 99

### 🖨 Output 
🏆 Full Leaderboard:

1. Geeta — 99
2. Ram — 92
3. Sita — 85

Top 3 Performers:

1. Geeta — 99
2. Ram — 92
3. Sita — 85

   ## 🧠 Concepts Used

- List slicing
- `map()` for type conversion
- `zip()` to combine two lists
- Custom sort using `key=`
- `enumerate()` for index-based printing

## 📌 Author

**Parul**  
[GitHub Profile](https://github.com/Parul-01)
