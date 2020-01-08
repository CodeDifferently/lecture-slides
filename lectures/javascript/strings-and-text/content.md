# Strings & Text

-
-
## Lecture Overview
* What is a string?
* How do we use Strings


-
-
### What is a String ?
* Technical Term -> A JavaScript string is zero or more characters written inside quotes.
* Strings can be enclosed within either single quotes, double quotes or backticks: 

```javascript
    var single = 'single-quoted';
    var double = "double-quoted";

    var backticks = `backticks`; 
```
    
-
### No Char Type
* Unlike other Languages Javascript does not have a type for single characters (i.e. char = 'd';)

-
#### Length
* Additionally you can get the length of a string as well for furth Operations. For Example:
    * ```javascript
        var name = "MrCody"
        var secondName = "Daniels"

        var nameLength = name.length();
        var secondNameLength = secondName.length();

        console.log(nameLength);
        console.log(secondNameLength);
    ```


-
-
## Creating Text in Processing Js


-
#### Creating Text
* ```javascript
        text(text, x, y);
        Draws some text
        ```

-
#### Changing the size of Text

* ```javascript
    textSize(size)
    Change the size of text
    For Example : textSize(10);
    ```
-
#### Changing the font of Text

* ```javascript
    textFont(font, size*)
    Changes the font of text
    ```

-
-
# Lets Try it 
[https://codepen.io/Rihzan/pen/vYYvwQx](https://codepen.io/Rihzan/pen/vYYvwQx)