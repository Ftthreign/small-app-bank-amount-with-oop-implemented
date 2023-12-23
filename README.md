> THIS IS IMPLEMENTATION OBJECT ORIENTED PROGRAMMING WITH JAVASCRIPT

this is small app that u can use

The OOP implemented code :

```javascript
class Bank {
  constructor(balance) {
    this.balance = balance;
  }

  withdraw(withdraw) {
    if (withdraw > this.balance) {
      throw new Error("Nilai tarik tunai lebih dari Saldo");
    }

    this.balance -= withdraw;
  }

  deposit(depo) {
    if (depo >= 1_000_000) {
      throw new Error("Deposit untuk akun anak harus kurang dari 1 Juta");
    }
    this.balance += depo;
  }
}

const BRI = new Bank(0);
```
