## Practicing Arrays

### What will each of the following lines of code return?

All the questions in this section will be based on this array:
```js
var colors = ["Red", "Magenta", "Cerulean", "Coral"]
```

???

# Array Practice

?: colors[3];

( ) "Cerulean"
(X) "Coral"
( ) "Red"

?: colors.length;

( ) 5
( ) 3
(X) 4

?: colors[1] = "Dusty Rose"; 

(X) ["Red", "Dusty Rose", "Cerulean", "Coral"]
( ) ["Dusty Rose", "Magenta", "Cerulean", "Coral"]
( ) ["Red", Dusty Rose", "Magenta", "Cerulean", "Coral"]


?: Using the original array, what would the array look like after `colors.push("Cornflower Blue");`

(X) ["Dusty Rose", "Magenta", "Cerulean", "Coral", "Cornflower Blue"]
( ) ["Red", "Magenta", "Cerulean", "Coral", "Cornflower Blue"]
( ) ["Cornflower Blue", "Dusty Rose", "Magenta", "Cerulean", "Coral"]


?: Using the original array, what would the array look like after `colors.pop();`

( ) ["Dusty Rose", "Magenta", "Cerulean", "Coral", "Cornflower Blue"]
( ) ["Magenta", "Cerulean", "Coral", "Cornflower Blue"]
(X) ["Dusty Rose", "Magenta", "Cerulean", "Coral"]

???

???

# Now it's your turn to use array methods

?: Give the original array `var colors = ["Red", "Magenta", "Cerulean", "Coral"]` How do you replace "Magenta" with "Chartreuse"?

( ) colors[2] = "Chartreuse";
(X) colors[1] = "Chartreuse";
( ) colors.push("Chartreuse");

?: How do you figure out how long the original array `var colors = ["Red", "Magenta", "Cerulean", "Coral"]` is?
 
(X) colors.length();
( ) colors.count();
( ) colors.size();

?: Given the original array, how do you add "Fuchsia" to the end of the array?
( ) colors.pop("Fuchsia")
( ) colors.add("Fuchsia")
(X) colors.push("Fuchsia")

?: Given the original array, how do you remove the last item from the array?

( ) colors.popLastItem();
( ) colors.removeLastItem();
(X) colors.pop();

?: Given the original array, how do you sort the colors in alphabetical order?
( ) colors.alphabetical();
(X) colors.sort();
( ) colors.organize();

???
<a href='https://learn.co/lessons/hs-intro-web-design-array-interactive-practice' data-visibility='hidden'>View this lesson on Learn.co</a>
