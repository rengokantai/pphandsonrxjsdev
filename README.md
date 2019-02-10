# pphandsonrxjsdev
## 2.
### 1 What are Observables and How to Crate Them?
Observables are lazy push collections of multiple values
- pull: The consumer determines when it receives data from the data proucer
- push: The producer determines when to send data to the consumer

  
  type|Single|Multiple
  ---|---|---
  pull|Function|Iterator
  Push|Promise|Observable

Observables are collections of Future values
Array
```
[1,2,3].map(console.log) //instant values
[1,2,3].pipe(map(console.log))//overtime
```
