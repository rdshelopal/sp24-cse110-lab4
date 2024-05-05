1. 20. Because var is function scope, so 0 gets overwritten by the add statement.
2. 20. Because var is function scope and it's value didnt get changed outside of the if block.
3. 20. This is because let is block scope, so inside the if block the value was set to 20 by the addition. 
4. Undefined. Since let is block scoped, the let result wasnt defined outside of the first if block, therefore it is undefined.
5. Undefined. This line is undefined because a const variable is not changeable, therefore after being defined as 0, it cant be changed.
6. Undefined. This line is undefined because const is also block scoped like let, so it is technically undefined outside the if block, therefore undefined.