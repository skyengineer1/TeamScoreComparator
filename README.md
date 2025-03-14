# 🏆 Team Score Comparison

## 📌 About
This JavaScript script calculates the average scores of two teams, Dolphins and Koalas, and determines the winner based on their average scores.

## 📂 Project Structure
- `script.js` - Contains the logic for calculating and comparing the scores.

## 📝 Code
```javascript
const scoreDolphins = (96 + 108 + 89) / 3;
const scoreKoalas = (88 + 91 + 110) / 3;

if (scoreDolphins > scoreKoalas) {
    console.log('Dolphins win the trophy');
} else if (scoreDolphins < scoreKoalas) {
    console.log('Koalas win the trophy');
} else {
    console.log('Both win the trophy');
}
```

## 🚀 Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo-name
   ```
3. Run the script using Node.js:
   ```sh
   node script.js
   ```

## 🔥 Output Example
```
Koalas win the trophy
```

## 💡 Features
- Calculates the average scores of both teams
- Compares scores to determine the winner
- Handles tie cases where both teams have the same score

## 👨‍💻 Author
**Goga Gabelia** - Software Developer

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
