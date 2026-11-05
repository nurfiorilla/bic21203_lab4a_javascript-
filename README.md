# BIC21203 Web Development — Lab 4a a

**Student Name: NUR FIORILLA ORNILLA LAWISON
**Student ID:AI240005
**GitHub Repository:** https://github.com/nurfiorilla/bic21203_lab4a_javascript-

## Lab 4a — Client-Side Scripting (JavaScript)

### Question 1: Interactive Text Changer
- **Q1:** Click **Change Message**. The paragraph changes from `Welcome to my website!` to `Hello there!`.
The webpage selects the paragraph and button using `getElementById()`. The `changeMessage()` function 
changes the paragraph using `textContent`. An event listener calls the function when the button is clicked.

**Expected output:** `Hello there!`

### Question 2: Smart Number Validator
- **Q2:** Enter a value and click **Check**. Test `5`, `10`, `15`, `abc`, and an empty value. Decimal values such as `10.5` are accepted.
The `checkInput()` function trims the input and checks whether it is empty. It converts the value using `Number()` and
uses an `if...else if...else` structure to compare it with 10. The result is displayed using `textContent`.

| Input | Expected message            |
|-------|-----------------------------|
| 5     | The number is lower than 10 |
| 10    | The number is equal to 10   |
| 15    | The number is higher than 10|
| abc   | Please enter a valid number!|
| Empty | Please enter a valid number!|

### Question 3: Dynamic Number Generator
- **Q3:** Click **Generate**. An ordered list from 1 to 5 appears. Clicking again replaces the existing list instead of duplicating it.
The `generateNumbers()` function clears the existing ordered list, uses a `for` loop from 1 to 5, creates each list item 
with `document.createElement()`, sets its text using `textContent`, and appends it to the list.

**Expected output:** 
1. The number is 1
2. The number is 2
3. The number is 3
4. The number is 4
5. The number is 5


