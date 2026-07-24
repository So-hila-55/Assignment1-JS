
// Q1
let num = Number("123");
console.log(num + 7);

// Q2
let x = 0;

if (!x) {
    console.log("Invalid");
}


// Q3
for (let i = 1; i <= 10; i++) {
    if (i % 2 === 0) {
        continue;
    }
    console.log(i);
}


// Q4

let numbers = [1, 2, 3, 4, 5];

let evenNumbers = numbers.filter(num => num % 2 === 0);

console.log(evenNumbers); // [2, 4]


// Q5
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];

let merged = [arr1, arr2];

console.log(merged); // [1,2,3,4,5,6]

// Q6
let day = 2;

switch (day) {
    case 1:
        console.log("Sunday");
        break;
    case 2:
        console.log("Monday");
        break;
    case 3:
        console.log("Tuesday");
        break;
    case 4:
        console.log("Wednesday");
        break;
    case 5:
        console.log("Thursday");
        break;
    case 6:
        console.log("Friday");
        break;
    case 7:
        console.log("Saturday");
        break;
    default:
        console.log("Invalid Day");
}


// Q7 
let words = ["a", "ab", "abc"];

let lengths = words.map(word => word.length);

console.log(lengths);

// Q8
function checkNumber(num) {
    if (num % 3 === 0 && num % 5 === 0) {
        return "Divisible by both";
    } else {
        return "Not divisible by both";
    }
}

console.log(checkNumber(15));


// Q9 
const square = num => num * num;

console.log(square(5));


// Q10
function personInfo(person) {
    const { name, age } = person;

    return `${name} is ${age} years old`;
}

console.log(personInfo({ name: "John", age: 25 }));


// Q11
function sum(...numbers) {
    let total = 0;

    for (let num of numbers) {
        total += num;
    }

    return total;
}

console.log(sum(1, 2, 3, 4, 5));


// Q12
function successPromise() {
    return new Promise((resolve) => {
        setTimeout(() => {
            resolve("Success");
        }, 3000);
    });
}

successPromise().then(result => console.log(result));


// Q13 
function largestNumber(arr) {
    return Math.max(...arr);
}

console.log(largestNumber([1, 3, 7, 2, 4]));


// Q14
function getKeys(obj) {
    return Object.keys(obj);
}

console.log(getKeys({ name: "John", age: 30 }));


// Q15
function splitWords(sentence) {
    return sentence.split(" ");
}

console.log(splitWords("The quick brown fox"));