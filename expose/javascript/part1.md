1. 20
2. 20
3. 20
4. The code returns an error because result is not defined. Result has a block scope, and because it wasn't defined in that specific block, then it is undefined.
5. The code returns an error because it tries to reassign the value of a const variable, when const keyword doesn't let you do that.
6. Nothing, because it returns an error from the same error as in #5. It never reaches line 13.