# what-i-learn-week-8

## Monday
Two Reasons To Use i:
1. You need to access the value at that index.
2. You need to access a range of value or an older value or see what index you are at.

If not use i. For-Of loop is a better option

This for loop
~~~
for (let i=0; i<numbers.length; i++) {
num = numbers[i]
}
~~~
Is equal this for-of loop
~~~
for (const num of numbers) {
}
~~~

## Tuesday
### Mapping and Filter in arrays
1. **Mapping** is when we create a new array that has the same number of elements in the original array, in which, each element is a modified version of the original array.
2. **Filter** is when we create a new array that has only has elements that qualify our condition from a collection of the orriginal array
Syntax used:
~~~
newArray.push(elementThatQualifiedOurCondition)
~~~

## Wednesday
### random number Math.random()
This syntax generate a random decimal number from 0 - 1. Therefore, if we want to get a random interger number from 1 - 6, we multiply with 6 and round it
~~~
let randomFrom1To6= Math.floor(Math.random() * 6)  //-> return a random number among 0, 1, 2, 3, 4, 5, 6
~~~

## Thursday
### Get user input in Node by using **process.argv**
This command will take user input and return an array, in which, each element is a string

~~~
let userInput = process.argv.slice(2)
~~~

