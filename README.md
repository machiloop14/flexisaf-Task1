# Array Methods Demo (ES6 + Arrow Functions)

This is a simple HTML + JavaScript project created as part of my frontend internship (Week 1 deliverable).  
It demonstrates the use of **ES6 array methods** (`map`, `filter`, `reduce`, `forEach`) implemented with **arrow functions**.

Each method is applied on the array `[1, 2, 3, 4, 5]`, and the result is shown dynamically on the webpage when a button is clicked, along with a short explanation of the transformation.

---

## Learning Outcomes Covered

- **ES6 Features**
- **Scope**
- **let & const**
- **Arrow functions**
- **Arrays**
- **Objects (partially introduced through examples in ES6 practice)**

---

## Project Structure

│── index.html # Main HTML file containing buttons, output section, and JS logic
│── README.md # Documentation for the project

---

## How It Works

1. Open `index.html` in any modern browser.
2. You’ll see the array: `[1, 2, 3, 4, 5]`.
3. Click any of the four buttons to run a transformation:
   - **map()** → doubles each number
   - **filter()** → keeps only even numbers
   - **reduce()** → sums all the numbers
   - **forEach()** → lists out each number

Each result includes a short description of what the method does.

---

## Example Output

When clicking **map()**, you’ll see:

map(): 2,4,6,8,10
map() creates a new array by applying a function to each element.
Here, each number was doubled.

---

## Requirements

- A modern browser (Chrome, Firefox, Edge, etc.)
- No external dependencies or styling (pure HTML + JavaScript)
