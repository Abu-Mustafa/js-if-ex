What the following statements will return?

1. `2 == "2";`  true
2. `2 === 2;` true
3. `10 % 3;` true
4. `10 % 3 === 1;` true
5. `true && false;` false
6. `false || true;` true
7. `true || false;` true

Answer the following questions about this code block:

```js
let isLearning = true;
if (isLearning) {
  console.log('Keep it up!');
} else {
  console.log('Pretty sure you are learning....');
}
```

1. What should the above code console.log? keep it up!
2. Why we do not need to specify `if(isLearning === true)`? Why does `if(isLearning)` work on its own?
because true is truthy value

---

```js
let firstVariable;
let secondVariable = '';
let thirdVariable = 1;

if (firstVariable) {
  console.log('first');
} else if (firstVariable || secondVariable) {
  console.log('second');
} else if (firstVariable || thirdVariable) {
  console.log('third');
} else {
  console.log('fourth');
}
```

1. What should the above code console.log? third
2. What is the value of `firstVariable` when it is initialized? undefined
3. Is the value of firstVariable a "truthy" value? no
4. Is the value of secondVariable a "truthy" value? no
5. Is the value of thirdVariable a "truthy" value? yes

---

- Use `Math.random` and write an if statement that console.log's "Over 5" if your operation returns a number greater than 5. Otherwise console.log "Under 5".

```js
randNum = Math.random() * 10;

if(randNum > 5){
  console.log("Over 5");
}else if(randNum < 5){
  console.log("Under 5");
}
```