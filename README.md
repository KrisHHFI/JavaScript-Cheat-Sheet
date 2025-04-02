# JavaScript Cheat Sheet 2025

## Syntax

<details>
<summary>Comments</summary>

<br/>

Comments allow you to add notes to your code, without effecting the code itself.

```sh
// This is a single line comment
 ```
```sh
/*
This is a multi line comment
*/
 ```

<br/>

</details>


<details>
<summary>Loops</summary>

<br/>

Loops have a number of use cases. For example, a loop can be used to "loop"/repeat lines of code until a condition is met, or to minimise file size by reducing repetitive code. The loops below show different ways to print the numbers 1 to 10.

<br/>

"for" loop, execute this code "for" as long as a condition is true.

```sh
for (let i = 1; i <= 10; i++) {
    console.log(i);
}
 ```

<br/>

"while" loop, execute this code "while" a condition is true.

```sh
let i = 1;

while (i <= 10) {
    console.log(i);
    i++;
}

 ```

<br/>

</details>


<details>
<summary>Print</summary>

<br/>

Printing allows you to print messages to a console. Developers can use it for debugging.

```sh
console.log("cat");
 ```
```sh
console.log(45);
 ```
```sh
console.log(5 + 5); // Prints "10" to the console
 ```
```sh
console.log("5 + 5"); // Prints "5 + 5" to the console
 ```

<br/>

</details>


<details>
<summary>Variables</summary>

<br/>

Variables can be declared as either a "var", "let" or "const". Using "let" and "const" is good modern practice. A "let" should be used for a variable whose value will change. A "const" (constant) should be used for variables that will not change in value.

<br/>

const variable examples
```sh
const cat = "Steve";
const age = 22;
const cost = 22.75;
 ```

<br/>

let variable examples
```sh
let cat = "Steve";
let age = 22;
let cost = 22.75;
 ```

</details>
