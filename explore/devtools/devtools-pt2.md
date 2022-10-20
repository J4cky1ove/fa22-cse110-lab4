1. The bug was the wrong type of the numbers to be added. They are two `strings` so that when adding them, they will concatenate together rather than calculating.
2. We need to type cast them from `string` to `integer` by using `parseInt(num1)` and `parseInt(num2)`.
