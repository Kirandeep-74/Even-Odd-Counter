# Even Odd Checker

A simple web application that checks whether a number is **Even or Odd** using JavaScript.

- If the number is **Even**, the result box turns **Green**.
- If the number is **Odd**, the result box turns **Red**.

## Technologies Used

- HTML
- CSS
- JavaScript
- JavaScript DOM

## Features

- User can enter any number.
- Checks whether the number is even or odd.
- Green box for even numbers.
- Red box for odd numbers.
- Simple and user-friendly interface.

## How It Works

The program uses the modulo operator `%` to check the number.

```javascript
if (n % 2 == 0) {
    box.innerHTML = "Even Number";
    box.style.backgroundColor = "green";
}
else {
    box.innerHTML = "Odd Number";
    box.style.backgroundColor = "red";
}
```

If the remainder after division by 2 is `0`, the number is even. Otherwise, it is odd.

## How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Enter a number.
5. Click the **Check** button.
6. The result will be displayed with the appropriate color.

## Example

**Input:** `8`  
**Output:** `Even Number` – Green Box

**Input:** `7`  
**Output:** `Odd Number` – Red Box

## Project Structure

```text
Even-Odd-Checker/
│
├── index.html
└── README.md
```

## Author

**Kirandeep Kaur**
