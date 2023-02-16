
# Activity 2 - Bank Account

In this activity, you are going to model a bank account. 

- Create a class called **BankAccount**. 
- Add properties for **balance** and **accountNumber**. Make sure that balance and accountNumber is required to create a bank account.
- Allow the user to deposit funds to the account. This can be accomplished by adding a **deposit** function to the BankAccount class. 
- Allow the user to withdraw funds from the account. This can be accomplished by adding a **withdraw** function to the BankAccount class.
- Allow the user to transfer funds between two accounts. This can be accomplished by adding a **transferFunds** function to the BankAccount class. 
- After creating the BankAccount class, along with all the functions make sure to create instance of BankAccount and perform actions. 

**Example:**

```
checkingAccount = BankAccount("FD332", 100)
checkingAccount.deposit(50) 
print(checkingAccount.balance) // $150 
```
