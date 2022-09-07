# Anita Zhinzhikova
### contacts
location: Moscow, Russia 
telegram: @Anita_Zhinzhikova
anitazhin@gmail.com
github: anitazhin

### skills
* HTML
* CSS
* GIT 
* JS
### about me
Very new to front-end
### code example
```JavaScript
function add(num1, num2) {
  //turn num1 into array
  let myInt1 = num1;
  let myFunc1 = num => Number(num);
  var intArr1 = Array.from(String(myInt1), myFunc1);
  
  //turn num2 into array
  let myInt2 = num2;
  let myFunc2 = num => Number(num);
  var intArr2 = Array.from(String(myInt2), myFunc2);
  
  //get the item of arrays and add together
var negOneAdd = Number(intArr1.slice(-1)) + Number(intArr2.slice(-1));
var negTwoAdd = Number(intArr1.slice(-2,-1)) + Number(intArr2.slice(-2,-1)); 
var negThreeAdd = Number(intArr1.slice(-3,-2)) + Number(intArr2.slice(-3,-2));
var negFourAdd = Number(intArr1.slice(-4,-3)) + Number(intArr2.slice(-4,-3)); 
var negFiveAdd = Number(intArr1.slice(-5,-4)) + Number(intArr2.slice(-5,-4));  
  //combine and store into a string
var result = Number(negFiveAdd.toString()+negFourAdd.toString()+negThreeAdd.toString()+negTwoAdd.toString()+negOneAdd.toString());
   return result;  
}
```
