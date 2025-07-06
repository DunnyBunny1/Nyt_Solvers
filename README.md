# 🧩 NYT Game Solvers
Solvers for **Wordle** and **Spelling Bee**, implemented in **Node.js** with **TypeScript**.

This project was created to learn JavaScript basics (scripts, file I/O, npm, modules) in a fun way 

## 📁 Project Structure
```
├── node_modules/
├── package-lock.json
├── package.json
├── README.md
├── src/
│   ├── spelling_bee_solver.ts
│   └── wordle_solver.ts
└── words.txt
```

## 🚀 Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Run the solvers
    ```
    npm run wordle    # Runs the Wordle solver
    npm run bee       # Runs the Spelling Bee solver
    npm start         # Also runs the Wordle solver by default
    ```

## Word List 
- The solver uses a word list stored in words.txt.
- Source: https://raw.githubusercontent.com/dwyl/english-words/master/words_alpha.txt