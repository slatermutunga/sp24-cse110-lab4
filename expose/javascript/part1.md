1. values added: 20
2. final result: undefined
3. values added: 20
4. ReferenceError: result is not defined
This returns an error because result is declared with the let keyword. This means that it isn't accesible outside of the if block
that it was defined in. By trying to access it on line 13 which is outside of the if statement, we cause an error.
5. TypeError: Assignment to constant variable
This returns an error as we declare result with the const keyword and set it to 0. We then try to assign it to num1 + num2, which we are unable to do as you cannot reassign const variables.
6. ReferenceError: result is not defined
This returns an error because result is declared with the const keyword. This means that it isn't accesible outside of the if block
that it was defined in. By trying to access it on line 13 which is outside of the if statement, we cause an error.