# PROJECT JAVASCRIPT G1 HIGHER-ORDER FUNCTIONS

To code this project you need to know:
Functions as Data,
Functions as Parameters

If you are not familier with them please download Learn JavaScript eBook from https://codingwithbasir.com/learn-javascript

## Project Title: Functions Benchmark

1. Open VS Code and create a html file with your name like john.html
2. Add current code to that file:

```html
<!DOCTYPE html>
<html>
  <body>
    <script>
      // your code here
    </script>
  </body>
</html>
```

3. Declare function `repeat(func, param, times)` that takes a function `func`, a paramter for the function `param` and number of calls `times`. It should call the function with that parameter for requested times and log run number into console.

4. Declare function `repeatDuration(repeat, times, func, param)` that takes a repeat function `repeat`, times of calling `times`, function to be called `func` and paratemters to this function `param`. It should call the function and log its running time in milliseconds.

5) define function `factorial` that gets a number and return its fcatorial and log it into console.

6. Call repeatDuration to log running time of `factorial` for parameter 20 for 1000 times.