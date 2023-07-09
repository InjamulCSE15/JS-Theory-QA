<div align="center">
<h2>JavaScript Theoretical Q/A</h2>
</div>

<h4>1. Explain Hoisting in javascript</h4>
<details><summary><b>Answer:</b></summary>
<p>
When we write JavaScript code, there are two main phases: the compilation phase and the execution phase. Hoisting is a mechanism where `variable` and `function` declarations are moved to the top of their containing scope during the compilation phase, before the code is executed. This means that regardless of where <b>variables</b> and <b>functions</b> are declared in the code, they are treated as if they were declared at the beginning of their scope.
</p>
<p><b>Example 1:</b>
<code>
myVariable = 5; // Variable initialized
console.log(myVariable); // Output 5 even when the variable is declared after it is initialized	
var myVariable; // Variable declared

</code>
</p>
</details>
```
myVariable = 5; 
console.log(myVariable); 
var myVariable; 

```