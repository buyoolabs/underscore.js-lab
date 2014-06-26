underscore.js-lab
=================

Playing with underscore.js javascript library

- It's a suite of functions, provides 80 functions
- Can be used in functional flavour or object oriented flavour:
    - Functional style
        ```
        var integers = [1, 27, 91, 32, 86, 12, 8, 68, 97, 72];
        var integerLimit = 50;
        var topIntegers = _.filter(integers, function (aInteger){
            return aInteger > integerLimit;
        });
        ```
    - Object-oriented style
        ```
        var integers = [1, 27, 91, 32, 86, 12, 8, 68, 97, 72];
        var integerLimit = 50;
        var topIntegers = _(integers).filter(function (aInteger){
            return aInteger > integerLimit;
        });
        ```
- For a .net developer, great advantage having LINQ similar functions over collections, like `find`, `where`, `sortBy`, `contains`, ...
- Has a basic templating system
