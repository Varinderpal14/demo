# demo
this repository is a representation of demo of cloning.
<html>
<head>
  <title> Inherit the properties from the parent Person class. </title>
  <body>
   <script>
  class Person {
    constructor(name, age) {
        this.name = name;
        this.age = age;
    }
    sing() {
        return `${this.name} can sing`;
    }
    dance() {
        return `${this.name} can dance`;
    }
} 
class Child extends Person {
    constructor(name, age, Color) {
        super(name, age);
        this.Color = Color;
    }
    car() {
        return "I have"+" "+this.Color+" "+" Color Car";
    }
}
var a = window. prompt("Enter The Person Name: ");
var b = window. prompt("Enter The Person Age: ");
var c = window. prompt("Enter The Person Car Color: ");
let obj = new Child(a, b, c);
console.log(obj.sing());
console.log(obj.car());
   </script>
</body>
</head>
</html>
