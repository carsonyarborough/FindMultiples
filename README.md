<h1 align="center">
FindMultiples
</h1>
<h3 align="left">
Description
</h3>
<text>
In this simple exercise, you will build a program that takes a value, integer , and returns a list of its multiples up to another value, limit . If limit is a multiple of integer, it should be included as well. There will only ever be positive integers passed into the function, not consisting of 0. The limit will always be higher than the base. For example, if the parameters passed are (2, 6), the function should return [2, 4, 6] as 2, 4, and 6 are the multiples of 2 up to 6.
</text>

<h3 align="left">
Solution 
</h3>
```

export function findMultiples(integer: number, limit: number): number[] {
 
     const arr = [];
  
  for (let i = 1; i <= limit; i += 1) {
    
      if (integer * i <= limit) {
        arr.push(integer * i);
      }
  }
  return arr;

}

<h3 align="center">
[Kata](https://www.codewars.com/kata/58ca658cc0d6401f2700045f)
</h3>