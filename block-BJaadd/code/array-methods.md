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

`flat` method is used to flatened the nested arrray based on the depth which is specified.
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

 `push` method is used to add elements at the end of the array.
   - Yes it mutates the original array.

5. `indexOf`

- Parameter: the element of which we want to find the  index number.
- Return: returns the index number (number).

```js
 let array1=[10,20,30,40,50,60];
 array1.indexOf(30);
 let strArr=["apple","mango","guava","peach"];
 strArr.indexOf("mango");
 let str2Arr=["red","brown","yellow","orange"];
 str2Arr.indexOf("cyan");
```
`indexOf` method is used to find the first occurance of an  element in a existing array .
   - No it does not mutates the array.




6. `lastIndexOf`
- Parameter: the element of which we want to find the  index number.
- Return: returns the index number (number).

```js
 let array1=[10,20,30,40,50,60];
 array1.LastIndexOf(30);
 let strArr=["apple","mango","guava","peach"];
 strArr.LastIndexOf("mango");
 let str2Arr=["red","brown","yellow","orange"];
 str2Arr.LastIndexOf("cyan");
```
`LastIndexOf` - method is used to find the last occurance of an  element in a existing array .
   - No it does not mutates the array.


7. `includes`

- Parameter: the element of which we want to check .
         searchIndex--optional
- Return: returns boolean value i.e true/false.

```js
 let array1=[10,20,30,40,50,60];
 array1.includes(30);
 let strArr=["apple","mango","guava","peach"];
 strArr.includes("mango");
 let str2Arr=["red","brown","yellow","orange"];
 str2Arr.includes("cyan");
```
`includes` - method is used to check whether the given value is present in the array or not.
   - No it does not mutates the array.



8. `reverse`

- Parameter: no parameter
- Return: returns the same array with element in the reverse order.

```js
 let array1=[10,20,30,40,50,60];
 array1.reverse();
 let strArr=["apple","mango","guava","peach"];
 strArr.reverse();
 let str2Arr=["red","brown","yellow","orange"];
 str2Arr.reverse();
```
`reverse` - method is used to reverse the elements in the same array.
   - yes it mutates the array.

9. `every`

- Parameter: a callback function
- Return: returns true/false.


```js
let fun=function(num){
   return num*2>=50;
}
array1.every(fun);
```


`every` - method is used to check wheter all the elements have passed the test provided by the function or not.
   - NO it doesn't mutates the array.

10. `shift`

- Parameter: no parameter
- Return: array with removed array value.


```js
array1.shift();
```


`shift` - method is used to remove the array items from starting of the array.
   - yes it  mutates the array.


11. `splice`

- Parameter: start index
            value to be inserted
            stopIndex-index number where it should stop.

- Return: array containg deleted items.


```js
array.splice(1,0,"Hello");
```


`splice` - method is used to change the array by adding or replacing or deleting existing values.
   - yes it  mutates the array.


12. `find`


- Parameter: callback function
            

- Return: the item which meets the condition


```js
fun=(num)=>num%2!==0;
array1.find(fun);
```


`find` - method search an array one by one until the functions value is satisfied .When it satified it will stop and will return that value.
   - no it doesn't mutates the array.

13. `unshift`

- Parameter: no parameter
            
            
- Return: the length of the array after addition of the element.

```js
array.unshift("120");

```
`unshift` - unshift method is used to add elements at the start of the array .
   - yes it mutates the array.




14. `findIndex`

- Parameter: callback function
            

- Return: the index of the item which meets the condition


```js
fun=(num)=>num%2!==0;
array1.findIndex(fun);
```


`findIndex()` - method search an array one by one until the functions value is satisfied .When it satified it will stop and will return that index number of the first occurance which satisfies the condition.
   - no it doesn't mutates the array.

15. `filter`


- Parameter: callback function
            

- Return: all the values which satisfies condition.


```js
fun=(num)=>num%2!==0;
array1.filter(fun);
```


`filter()` - method search an array one by one until it complete the last element. After that it will return the elements that satisfies the conditions.If none satisfies then it will return empty array.
   - no it doesn't mutates the array.

17. `forEach`

- Parameter: callback function
            

- Return: no return value 


```js
array1.forEach((element)=>{
   console.log(element=num%2);
});
```


`forEach()` - method iterate over an array one by one and it will execute the function atleast once on them.
   - no it doesn't mutates the array.




18. `map`


- Parameter: callback function
- Return: a new array with same element .


```js
fun=function(num){
return num*2;
}
array1.map(fun);
```


`map()` - The map() function in JavaScript is an array method that creates a new array by applying a provided function to each element of the original array. It doesn't change the original array but instead returns a new array with the results of applying the provided function.
   - no it doesn't mutates the array.
   - it doesn't mutates the array.



19. `pop`

- Parameter: no parameter.
- Return: deleted item.


```js
array1.pop();
```


`pop()` - The pop() function in JavaScript is an array method that is used to delete the element from the end of the array
   - no it doesn't mutates the array.
   - yes it mutates the array.

20. `reduce`
21. `slice`

- Parameter:startIndex
           :LastIndex -optional
- Return: new array with extracted.


```js
array1.slice(1,5);
```
`slice`-This method is used to extract a specific part of an array.
      -It doesn't mutates the array.

22. `some`

- Parameter:callback function
          
- Return: true/false.


```js
fun=function(num){
   return num*2;
}
array1.some(fun);
```
`some`-This method is used to check whether atleast one element is satisfying the condition.
      -It doesn't mee