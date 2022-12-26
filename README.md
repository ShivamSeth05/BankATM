# BankATM
Convert Bank Transaction process into "Anonymous InnerClass as implementation class".

# Assignment:(BankTransaction Process)
## 
### Real Time Example of Anonymous InnerClass
<hr>
(a)read pinNo
 pinNo must be 4 digits,else &quot;Invalid pinNo&quot;
If pinNo is validated then the PinNo must be in 1111 or 2222 or 3333,else
Incorrect PinNo...;
If pinNo entered Wrongly for three times,display the msg as &quot;Transaction
blocked temporarly;.
<br>
<hr>
(b)If the PinNo is Validated and verified Successfully,select the from the choice<br>
1.WithDraw<br>
2.Deposit
<br>
1.WithDraw:
Enter the amt
The amt must be greater than Zero and multiples of 100,else &quot;Invalid amt&quot;
If amt Validated Successfully then create object for &quot;WithDraw&quot; class and

pass amt as parameter to process() method
part of process() method check the amt is less than bal or not.
If amt is less than bal then perform transaction,else &quot;Insufficient fund&quot;
o/p:<br>
Amt WithDrawn :<br>
Balance Amt :<br>
Transaction Successful...

2.Deposit:<br>
Enter the amt<br>
The amt must be greater than Zero and multiples of 100,else &quot;Invalid amt&quot;
If amt Validated Successfully then create object for &quot;Deposit&quot; class and
pass amt as parameter to process() method
o/p:<br>
Amt Deposited:<br>
Balance Amt :<br>
Transaction Successful...

<br>
Balance.class<br>
Transaction.class<br>
CheckPinNo.class<br><br>
ValidatePinNo.class<br>
BankMainClass.class(MainClass)<br>
BankMainClass$1.class<br>
BankMainClass$2.class
