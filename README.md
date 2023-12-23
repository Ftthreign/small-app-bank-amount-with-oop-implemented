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

- You Can clone this repo if you want to modify it and learn it more about OOP

```bash
git clone https://github.com/Ftthreign/small-app-bank-amount-with-oop-implemented.git
```

> <span style="color:orange;">BUT I RECOMMEND TO USE ANOTHER LANGUANGE TO LEARN OOP, LIKE JAVA, C++, Typescript and many more with strict-type languange</span>
