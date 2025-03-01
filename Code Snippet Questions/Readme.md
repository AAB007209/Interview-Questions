# Code Snippet Based Questions

1. Guess the Output: [Hint - Hoisting]
    ```Javascript
        var x = 10;
        function helper(){
            x++;
            console.log(x);
            var x = 20;
        }

        helper();