// shuttle colors 
<!DOCTYPE html>
<html>
  <body>
    <h2>Shuffle colors with Lodash</h2>
    <p id="result">Click the button to shuffle!</p>
    <button id="btn">Shuffle</button>

    <!-- Lodash is loaded from a CDN -->
    <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js"></script>

    <script>
      const colors = ["red", "orange", "yellow", "green", "blue", "purple"];

      document.getElementById("btn").addEventListener("click", function () {
        // Use _.shuffle() to randomize the colors array
        // Then display the result in the paragraph
      const shuffled = _.shuffle(colors);
      document.getElementById("result").textContent = shuffled.join(", ");
      
      });
    </script>
  </body>
</html>
----------------------------------------

// Create a variable called 'name' with your name
const name = "teresa";

// Create a variable called 'age' with your age
let age = 60;

// Log both variables
console.log(name);
console.log(age);

---------------------------------------
const a = 20;
const b = 4;

// Log a + b
console.log(a + b);
// Log a - b
console.log(a - b);
// Log a * b
console.log(a * b);
// Log a / b
console.log(a / b);

-------------------------------------

const sideA = 3;
const sideB = 4;

// Hint: hypotenuse = √(a² + b²)
// Use ** to square: 3 ** 2 = 9
// Use Math.sqrt() for square root

const hypotenuse = Math.sqrt(
                    (sideA ** 2) + 
                    (sideB ** 2) )

console.log(hypotenuse);

// Use backticks and ${} to insert the variable
console.log(`The hypotenuse is ${hypotenuse}`);

-------------------------------
const countries = ["France", "Germany", "Spain", "Italy", "Portugal"];

// Log: "There are X countries in the list"
console.log(`There are ${countries.length} countries in the list`);

----------------------------------
const countries = ["France", "Germany", "Spain", "Italy", "Portugal"];

// Log the first country
console.log(`The first country is ${countries[0]}.`);

// Log the last country (hint: use .length)
let n = countries.length - 1;
let name = countries[n]
console.log(`The last country is ${name}.`);

-------------------------------------------


