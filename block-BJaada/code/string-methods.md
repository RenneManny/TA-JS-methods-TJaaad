Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`
-Parameter:none
-return:It returns the string passed to it by converting into uppercase.
example:-
```js
let str0="altcampus";
console.log(str0.toUpperCase());
```
3. `toLowerCase`
-Parameter:none
-return:specified string in lower case.
example:-
```js
let str1="ALTCAMPUS";
console.log(str0.toLowerCase());
```
--this method converts the string into lower case.
4. `trim`
-Parameter:none
-return:trimmed string from both sides.
example:-
```js
let str2="  hello world    ";
console.log(str.trim());
```
trim - This method is used to remove whitespace from both sides of the string.
5. `trimEnd`
-Parameter:none
-return:trimmed string from right side.
example:-
```js
let str3="  hello world    ";
console.log(str3.trimEnd());
```
trimEnd - This method is used to remove whitespace from right side of the string.
6. `trimStart`
-Parameter:none
-return:trimmed string from left side.
example:-
```js
let str4="  hello world    ";
console.log(str4.trimStart());
```
trimStart - This method is used to remove whitespace from left side of the string.
7. `concat`
- Parameter: n number of strings that we want to concatenate.
-Seprator:optional
   - Return: concatenation of the provided strings.
   - Example:
     ```js
     let str5="Hello World";
    let sentence="This is altcampus!";
    console.log(str5.concat(" ",sentence));
     ```
   - `concat` accepts one or more strings and concate them with each other.We can also use seprators in this.
8. `endsWith`


- Parameter: a string or a character to check 
   - Return: true or false 
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.endsWith("World"));
     ```
   - `endsWith` accepts one string and check if the original string or sentence ends with it or not . If yes then it will return to true otherwise it will result to false.




9. `includes`

- Parameter: a string or a character to check 
-position :Optional
   - Return: true or false 
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.includes("World"));
     ```
   - `includes` accepts one string and check if that is present in the original string  or not . If yes then it will return to true otherwise it will result to false.



10. `indexOf`

- Parameter: a string or a character to check 
-position :Optional
   - Return: index of string (number) / -1 (in case if specified index doesn't exist)
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.indexOf("l"));
     ```
   - `indexOf` accepts one string and check the first occurance  of that in original string.After that it return the value . If the specified string doesn't include than it will return to -1.
11. `lastIndexOf`

- Parameter: a string or a character to check 
-position :Optional
   - Return: last index of string (number) / -1 (in case if specified index doesn't exist)
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.lastIndexOf("l"));
     ```
   - `lastIndexOf` accepts one string and check the last occurance of that in original string.After that it return the value . If the specified string doesn't include than it will return to -1.

12. `padEnd`

- Parameter: target length in number.
-padString: optional
   - Return: returns a new string with given length and with the specified string.
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.padEnd("20","e"));
     ```
   - `padEnd`:-padEnd is a method which returns  the string to a specified length along with the padded string. 

13. `padStart`

- Parameter: target length in number.
- padString: optional
   - Return: returns a new string with given length and with the specified string.
   - Example:
     ```js
     let str5="Hello World";
    console.log(str5.padStart("20","e"));
     ```
   - `padStart`:-padStart is a method which returns  the string to a specified length along with the padded string but the pad String is applied on starting of the string.

14. `repeat`

- Parameter: a positive integer 
- return : a string value repeated number of provided times.

 - Example:
     ```js
     let str5="Hello World";
    console.log(str5.repeat(30));
     ```
- `repeat`: repeat is used to repeat the string number of times . It accepts positve integers along with 0.
15. `replace`

- Parameter: pattern- 1.This represents the string which needs to be replaced.
             2.replacement-string:This is the string that will load to the 
- return : a string value repeated number of provided times.

 - Example:
     ```js
     let str5="Hello World";
    console.log(str5.replace('World','This is JavaScript'));
     ```
- `replace`: replace is the method which is used to replace on charcter or string with other one.

16. `slice`


- Parameter: startIndex:-This refers to the index number from where we want to extract the part of the string.
            endIndex:-This is optional. This specifies that where we want to end the process.
- return : returns the extracted part of the string.

 - Example:
     ```js
    let institute="This is AltCampus";
    console.log(slice.(7)); //Altcampus
     ```
- slice:-slice method is used to extract a part of the string from a given string. 

17. `split`

- Parameter: separator-seprator is used to define the pattern where the string should break.
              limit:limit is used to limit the search or split.

- return : returns the array of string .

 - Example:
     ```js
    let institute="This is AltCampus";
    console.log(institute.split(" is ")); 
     ```
- split method is used to split the string in a given pattern and return a new string. 

18. `substring`
- parameter :The index of the first character to include in the returned substring.
            :length . It is the optional value.

- return : returns a  string which contains specified part of the index.

- Exmaple:
let institute="This is AltCampus";
    console.log(institute.substring("0","5")); 