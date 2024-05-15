# geekjokes
JavaScript library for geek-jokes.sameerkumar.website
# main
```js
const {geekjokes} = require('./geekjokes');

const geekjoke = new geekjokes();
geekjoke.get_joke().then(joke => {
    console.log(joke);
}).catch(error => {
    console.error('Error:', error);
});

```
