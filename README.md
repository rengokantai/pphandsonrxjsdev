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
