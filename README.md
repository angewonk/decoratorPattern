## Problem

Cimb is a digital bank that offers GSave and UpSave savings accounts.   As with a typical Savings Account, it contains accountNumber, accountName, and a balance for that account.

The typical savings account offers an interest rate of 1%.
The benefits of the typical savings account is the same with the "Standard Savings Account" as compared to other banks.

The GSave account offers an interest rate of 2.5%.
Benefits include the "Standard Savings Account" plus access to "GCash transfer".

The UpSave account offers the highest interest rate of 4.0%.
Benefits include the "Standard Savings Account" plus "with Insurance".

The content of your Cimb.java should ONLY contain the following codes with the exception of inserting your own package name:
<br>
![1df](https://github.com/angewonk/decoratorPattern/assets/142864286/253aeed2-778d-4b68-a469-7e25f5d2a13f)

You should display the following output:
<br>
![213](https://github.com/angewonk/decoratorPattern/assets/142864286/534c176d-54b5-4e4d-9707-8e9ef946f864)
<br>
<br>
Description of the following methods

1. <b>showAccountType()</b> - Either returns "Savings Account", "GSave" or "UpSave"
2. <b>getInterestRate()</b> - Either returns 1% for Savings Account; 2.5% for GSave; 4.0% UpSave
3. <b>getBalance()</b> - Returns the balance of the account set.
4. <b>showBenefits()</b> - Either returns "Standard Savings Account" for Savings Account; 
<br>benefits offered by savings account + "GSave Transfer";
<br>benefits offered by savings account + "With Insurance";
5. <b>computeBalanceWithInterest()</b> - returns new balance by computing the balance plus the interest depending on the interest rate.
6. <b>showInfo()</b> - Returns details of account number, account name, and balance.

<b>BankAcountDecorator</b> must be an interface.

Follow instructions.  You are not allowed to insert other methods except what is stated in the diagram (setters and getters are allowed).

## Decorator Pattern Class Diagram
![Blank diagram (7)](https://github.com/angewonk/decoratorPattern/assets/142864286/457f3059-7744-4b54-b723-b1301faf11a4)

