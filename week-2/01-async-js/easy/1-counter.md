code a counter in Javascript
It should go up as time goes by in intervals of 1 second
## Create a counter in JavaScript

let counter = 1;
let counterEnd = 15;

function newCounter(){
console.log(counter);
counter++

if (counter <= counterEnd){
setTimeout(newCounter, 1000);
}
else{
console.log("counter stopped");  
}

}
newCounter();

