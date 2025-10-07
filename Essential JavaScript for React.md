# Destructuring Assignment

## Question
#Paano gamitin ang Destructuring sa Arrays?
## Answer
#Ginagamit ang square brackets [] kapag array ang idede-structure.
ex;
const colors = ['red', 'green', 'blue'];
const [first, second, third] = colors;

console.log(first); // red
console.log(second); // green


# Arrow Functions

## Question
#Ano ang .map() at para saan ito?
## Answer
Ang .map() ay ginagamit para mag-loop sa isang array at bumalik ng bagong array na may transformed values.
ex;
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2);
console.log(doubled); // [2, 4, 6]



# Spread & Rest Operators

## Question
Para saan ang Spread Operator?
## Answer
Ginagamit ang Spread Operator (...) para;
-Kopyahin ang arrays o objects
-Pagsamahin ang arrays o objects
-Ilagay ang elements sa function parameters



# Array Methods

## Question
Ano ang pagkakaiba ng mutating at non-mutating array methods?
## Answer
Mutating methods → binabago ang original array
Non-mutating methods → gumagawa ng bagong array (safe gamitin sa React)



# Template Literals

## Question
magbigay ng halimbawa ng syntax of Template Literal?
## Answer
const name = "Chris";
console.log(`Hello, ${name}!`);


# Conditional (Ternary) Operator

## Question
Paano ito naiiba sa if-else statement?
## Answer
Ang if-else ay mahaba at multi-line, samantalang ang ternary operator ay maikli at one-liner.