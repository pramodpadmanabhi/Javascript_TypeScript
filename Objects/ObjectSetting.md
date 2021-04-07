```
const userChosenKeyName='level' ------------------------> Dynamic Property Access & Setting Properties Dynamically

let person={
'first name':Pramod,  -----------------------------------------> Special Key Notation
 age:20,
 hobbies:['Sports','drawing'],
 [userChosenKeyName]:'...', ---------------------------> Dynamic Property Access & Setting Properties Dynamically
 greet:function(){
 alert("Hi There")
 },
 1.5:"Hello"
 }


 console.log(person['first name']);-------------------------------> Way to access it
 
 console.log(person[1.5]);
 console.log(person['1.5']);  -------------------> Js coerces to string therfore '1.5' or 1.5 both can be used
 
 ```
