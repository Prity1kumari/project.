console.log("Welcome to the world of gaming\n");

let x=Math.floor(Math.random()*5);
const prompt=require("prompt-sync")();
let chance=0;
console.log("Guess the number from 0 to 5\n");

let a;
let b=0;


while(b<5 && a!=x){
  a=prompt("Enter the number:");

  if(a==x){

  }
  else{
  if(a>x){
    console.log("your guessing is greater than the number\n");
    chance++;
  }
  else if(a<x){
    console.log("your guessing is smaller than the number\n");
    chance++;
  }
  }
  b++;

}



console.log(x);
console.log("your score is",5-chance);
