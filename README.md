# goit-js-hw-04

Homework assignment #4 from the [GoIT](https://goit.global/) JavaScript course. A set of three small exercises practicing objects, `Object.keys()`, array-of-objects iteration, and object methods with `this` in vanilla JavaScript.

## 📋 About

Each task is implemented as a standalone function or object that is exercised with sample inputs, logging the result to the console:

- **Task 1** — `isEnoughCapacity(products, containerSize)`: sums up the quantities in a products object (using `Object.keys()`) and checks whether they fit within a given container size.
- **Task 2** — `calcAverageCalories(days)`: calculates the average calorie count from an array of `{ day, calories }` objects, returning `0` for an empty array.
- **Task 3** — a `profile` object with `changeUsername`, `updatePlayTime`, and `getInfo` methods, demonstrating object state mutation via `this` and a formatted info string.

## 🛠️ Tech Stack

- Vanilla JavaScript (ES modules)
- HTML5

## 📁 Project Structure

```
goit-js-hw-04-main/
├── js/
│   ├── task-1.js    # Container capacity check
│   ├── task-2.js    # Average calories calculator
│   └── task-3.js    # Profile object with methods
├── .prettierrc.json   # Prettier configuration
└── index.html          # Loads all three task scripts as ES modules
```

## 🚀 Getting Started

Open `index.html` in a browser and check the browser console (DevTools) to see the logged results of each task.
