Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

## Getting To Know Array Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (2-3 times to understand)
2. Data types of parameters                                               
3. Return value type
4. Write three examples
5. In your words what this method does.
6. Does it mutate the original value or not (check https://doesitmutate.xyz)

Example:

1. `concat`

   - Parameter: n (any) number of values (number, string, boolean, array, null, undefined, object and function etc)
   - Return: a single Array consisting of by all the values passed as parameters in the same order.
   - Example:
     ```js
     let numbers = [1, 2, 3];
     numbers.concat(4); //[1,2,3,4]
     let sentanceArray = 'A quick brown fox jumped over a lazy'.split(' ');
     sentanceArray.concat('dog').join(' '); //"A quick brown fox jumped over a lazy dog"
     let colors = ['red', 'green', 'blue'];
     colors.concat('black', 'red', 21, true); // ['red','green','blue','black', 'red', 21, true]
     ```
   - `concat` accepts n number of values and returns one array with all the values in same order. It does not change the original array.
   - No it does not mutate the original array

2. `join`
  - Parameter: seprator is used to specify how you want to seprate the elements of the array.
   - Return: an array with joined string together but seprated by the seprator.
```js
let colors=["Green","blue","orange","black"];
colors.join("'");
let numbers =[1,2,3,4,5,6];
numbers.join("/");
let fruits=["Apple","Mango","Banana","Kiwi"];
fruits.join("-");
```
 - `join` method is used to join the elements of the array seprated by the specific seprator.
   - No it does not mutate the original array.
3. `flat`
  - Parameter: depth (integer).
   - Return: a flattened array with the given depth.
```js
let arr1=[1,2,3,4,[5,6,7,8,[9,10,11]]];
arr1.flat();
let arr2=["apple","mango","banana",["kiwi","orange",["peach","gauva",["rasberry"]]]];
arr2.flat(2);
let arr3=["red","blue","maroon",["black","orange",["purple","diamondblack",["wheat"]]]];
arr3.flat(3);

`flat` method is used to flattened the nested arrray based on the depth which is specified.
   - No it does not mutate the original array.
```
4. `push`
- Parameter: the element or array to be pushed.
   - Return: a new array with the updated value.
   ```js
   let arr11=[1,2,3,4,5,6];
   arr11.push(7);
   let arr22=["apple","mango","banana","pineapple"];
   arr22.push("orange");
   arr22.push(arr11);
```
- `push` method is used to add elements at the end of the array.
   - Yes it mutates the original array.

5. `indexOf`
6. `lastIndexOf`
7. `includes`
8. `reverse`
9. `every`
10. `shift`
11. `splice`
12. `find`
13. `unshift`
14. `findIndex`
15. `filter`
16. `flat`
17. `forEach`
18. `map`
19. `pop`
20. `reduce`
21. `slice`
22. `some`
