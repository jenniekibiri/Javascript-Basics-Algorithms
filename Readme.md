let fruits=['kiwi','apple','mango','lemon']


foreach
```
fruits.forEach(fruit => {
    console.log(fruit)
});
```
for
``` 
for (let i = 0; i <fruits.length; i++) {
    console.log(fruits[i]);
} 
```
 for of
can be used with objects
```
for(let fruit of fruits){
    console.log(fruits)
}
```
 map
you can use map to change the value of the arrays
you must assign it to a variable
```
fruits.map(fruit=>{
    console.log(fruit)
})
```


for in
```
for(let i in fruits){
    console.log(fruit[i])
}
```

array methods
The filter() method creates a new array with the elements that pass the result of a given test.
```
let seaCreatures = [ "shark", "whale", "squid", "starfish", "narwhal" ];
```

 Filter all creatures that start with "s" into a new list
 ```
let filteredList = seaCreatures.filter(creature => {
  return creature[0] === "s";
});
filteredList;
```
reduce()
The reduce() method will reduce an array to a single value.
 maybe sum of all numbers
```
let numbers = [ 42, 23, 16, 15, 4, 8 ];
```

 Get the sum of all numerical values
```
let sum = numbers.reduce((a, b) => {
    return a + b;
});

sum;
```
<!-- find() -->
 <!-- The find() method returns the first value in an array that passes a given test. -->
 <!-- Check if a given value is a cephalopod -->
```
const isCephalopod = cephalopod => {
    return [ "cuttlefish", "octopus" ].includes(cephalopod);
}

seaCreatures.find(isCephalopod);

```




find index 
```
 const isThereAnEel = eel => {
    return [ "eel" ].includes(eel);
} 


seaCreatures.findIndex
```
<!-- if no result returns -1 -->

<!--  while
//while loop checks if a condition is true. If it is, the loop continues; if it is not, it stops. -->
