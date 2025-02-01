# 🏺 Jarring (Count the Jar!)

## 🎮 About the Game  

**Jarring** is a fun and interactive guessing game where players estimate the number of objects inside a virtual jar.  
It features:  

- 🎨 A stylish, pixel-art-inspired design  
- 🎭 Randomized objects with floating animations  
- 🎚️ Adjustable difficulty levels (Easy, Medium, Hard)  
- 🏆 Best-score tracking with local storage  
- 🔥 A fun shake effect for incorrect guesses  

## 🚀 How to Play  

1. **Choose a difficulty level:**  
   - **Easy** (1-20 objects)  
   - **Medium** (1-40 objects)  
   - **Hard** (1-60 objects)  

2. **Look at the jar and estimate the number of objects.**  
3. **Enter your guess in the input box.**  
4. **Press the "GUESS!" button or hit "Enter" on your keyboard.**  
5. **Receive feedback:**  
   - ❌ Incorrect? You'll get a hint.  
   - 🎉 Correct? Celebrate and try to beat your best score!  
6. **Play again** by clicking "PLAY AGAIN" after a correct guess.  

## 🎨 Visual Features  

- **Dynamic jar-filling animation**: Objects are positioned randomly for a natural look.  
- **Soft glass-like jar effect** using the CSS `backdrop-filter`.  
- **Shake effect on incorrect guesses** for feedback.  
- **Retro-inspired font** for a fun arcade feel.  

## 🛠️ How It Works  

- The game randomly selects an object type (e.g., marbles, candies, cookies).  
- A random number of these objects (within the difficulty range) is placed in the jar.  
- The player must guess the correct number.  
- Incorrect guesses provide hints.  
- Best scores are saved using `localStorage` (I know, I know). 

## 🔧 Tech Stack  

- **HTML** for structure  
- **CSS** for styling and animations  
- **JavaScript** for interactivity and game logic  

## ❗ Notes for HS Reviewers  

- The CSS is written **before** the HTML body (a personal quirk).  
- Uses `localStorage` to persist the best score.  
- Difficulty settings adjust the max object range.  


🚀 **Enjoy guessing!**  
