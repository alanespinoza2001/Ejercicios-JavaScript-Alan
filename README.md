# Ejercicios-JavaScript-Alan
**Ejercicio 1: Calculadora con 4 opereaaciones a traves de datos ingresados por teclado**

//Created By: Alan el Programador y Alan Espinoza

//CALCULADORA EN JAVASCRIPT


var numero_a= prompt("Ingrese el primer numero: ");
numero_a = parseInt(numero_a);//Se tranforma el vaalor digitado a int


var numero_b= prompt("Ingrese el segundo numero: ")
numero_b = parseInt(numero_b);


//Vamos hacer las variables de las operaciones y sus operaciones respectivas

var suma = numero_a + numero_b;//Hacemos la suma

var resta= numero_a - numero_b;//Hacemos la resta

var multiplicacion=numero_a * numero_b;//Hacemos la multiplicacion

var division= numero_a /numero_b; //Hacemos la division


//Mostrar los resultados de las operaciones
console.log("La suma es : "+ suma);
console.log("La resta es : "+ resta);
console.log("La multiplicacion es : "+ multiplicacion);
console.log("La division es : "+ division);
