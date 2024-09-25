
## JavaScript Assignment Operators

Operator        Example                      Same As
=               x = y                        x = y
+=              x += y                       x = x + y
-=              x -= y                       x = x - y
*=              x *= y                       x = x * y
/=              x /= y                       x = x / y
%=              x %= y                       x = x % y
**=             x **= y                      x = x ** y

***

## Shift Assignment Operators
Operator        Example                      Same As
<<=             x <<= y                      x = x << y
>>= x           >>= y                        x = x >> y
>>>=            x >>>= y                     x = x >>> y

***

## Logical Assignment Operators
Operator        Example                      Same As
&&=             x &&= y                      x = x && (x = y)
||= x           ||= y                        x = x || (x = y)
??= x ?         ?= y                         x = x ?? (x = y)




## инкремент ++
Эта унарная операция увеличивает удиницу числоб записанное в переменную

## постфиксная форма:
Если используется постфикс с оператором после операнда (например, x ++), оператор приращения увеличивает и возвращает значение до увеличения.

```
let x = 3;
const y = x++;
// x = 4
// y = 3
```
## префиксная форма:
Если используется префикс с оператором перед операндом (напримерб ++x),
оператор приращения увнеличивает и возвращает значение после увеличения.
```

let x = 3;
const y = ++x;
// x = 4
// y = 4
```

***

## декремент "__"
Эта унарная операция уменьшает на единицу число, записанное в переменную.

function increaseBalance(x, y) {
    return x + y;
  }
  
  function decreaseBalance(x,y) {
    return x - y;
  }
  
  function divideBalanceByAccounts(balance, accNumber) {
    return balance/ accNumber;
  }
  
  function getRestAfterDivision(x, y) {
    return x %= y;
  }

  function getIncrementPost(x) {
    return x++;
  }

  function getIncrementPre(x) {
    return ++x;
  }

  function getDecrementPost(x) {
    return x--;
  }

  function getDecrementPre(x) {
    return --x;
  }
  
  console.log(increaseBalance(3000, 700));
  console.log(decreaseBalance(3000, 700));
  console.log(divideBalanceByAccounts(3000, 2));
  console.log(getRestAfterDivision(7000, 3));
  console.log(getIncrementPost(3));
  console.log(getIncrementPre(3));
  console.log(getDecrementPost(3));
  console.log(getDecrementPre(3));



  let x = 3;
  const y = ++x;
  console.log(x,y)