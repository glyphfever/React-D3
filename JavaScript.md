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

const countries = ["France", "Germany", "Spain", "Italy", "Portugal"];

// Check if "Spain" is in the array
console.log(countries.includes("Spain") )
 
// Check if "Japan" is in the array
console.log(countries.includes("Japan") )

----------------------------------------------

const countries = ["France", "Germany", "Spain"];

// Join the array into a string with ", " as separator
console.log(countries.join(", "));

-------------------------------------------
const company = {
  name: "TechCorp",
  headquarters: {
    country: "Japan",
    city: "Tokyo",
    employees: 5000
  },
  founded: 2010
};

// Log the city
console.log(company.headquarters.city);

-------------------------------------
// Create an array of objects matching the table
const data = [
  {fruit: "apple", price: 1.2},
  {fruit: "banana", price: 0.8}
];

console.log(data);

---------------------------------
const data = [
  { country: "France", population: 67 },
  { country: "Germany", population: 83 },
  { country: "Spain", population: 47 }
];

// Log Germany's population
console.log(data[1].population);

----------------------------------
const data = [
  { country: "France", population: 67 },
  { country: "Germany", population: 83 },
  { country: "Spain", population: 47 }
];

// Log: "The dataset has X countries"
console.log(`The dataset has ${data.length} countries`);

----------------------------------
// Create an arrow function called 'triple'
function triple (x) {
  return x * 3
}

console.log(triple(4));   // should log 12
console.log(triple(10));  // should log 30

-------------------------------------

// Create a 'multiply' function with two parameters
function multiply (x, y) {
  return x * y
}

console.log(multiply(3, 4));   // should log 12
console.log(multiply(7, 8));   // should log 56

--------------------

// Return an object with name and score properties
const makePlayer = (name, score) => (
  {name: name, score: score}
)

console.log(makePlayer("Alice", 100));
// should log { name: "Alice", score: 100 }

-------------------------
//Multi-line functions need explicit return.
const greet = (name) => {
  const greeting = "Hello, " + name + "!";
  return greeting;
};

console.log(greet("Bob"));  // should log "Hello, Bob!"

---------------------------------
const score = 75;

// Is score greater than 50?
console.log(score > 50);

// Is score equal to 75? (use ===)
console.log(score === 75);

// Is score less than or equal to 100?
console.log(score <= 100);

--------------------------------
const score = 45;

// If score >= 60, log "pass", otherwise log "fail"
if (score >= 60) {
  console.log("pass");
} else {
  console.log("fail");
}

------------------------------

const age = 22;
const hasTicket = true;

// Can they enter? (age >= 18 AND hasTicket)
const canEnter = age >= 18 && hasTicket
console.log(canEnter);

------------------------------

const temperature = 35;

// Use a ternary: condition ? ifTrue : ifFalse
const status = temperature > 30 ? "hot" : "cold"
console.log(status);  // should log "hot"

------------------------------
const value = -5;

// Hint: you can chain ternaries
// condition1 ? result1 : condition2 ? result2 : result3
const color = value > 0 ? "green" : value === 0 ? "gray" : "red"
console.log(color);  // should log "red"

---------------------------------------------


