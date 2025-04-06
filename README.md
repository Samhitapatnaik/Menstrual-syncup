
let name = "Samhita";
const age = 19;
function greet(user)
 {
  return `Hello, ${user}`;
}
console.log(greet(name));

if (age >= 18) 
{
  console.log("You are an adult.");
} else
 {
  console.log("You are a minor.");
}

for (let i = 1; i <= 5; i++)
 {
  console.log("Count:", i);
}

let fruits = ["Apple", "Banana", "Mango"];
fruits.forEach(fruit =>console.log(fruit));


let student = {
  name: "Samhita",
  course: "BTech",
  year: 1
};
console.log(student);


const square = num => num * num;
console.log(square(4));