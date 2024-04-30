1. The bug was that we were adding the inputs as strings. 

2. We can fix this with the Number() function that just returns an integer version of the input. result = Number(num1) + Number(num2)