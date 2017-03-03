# Bank-account-Multi-class
 Each BankHolder instance has the name of a person or business in the bankerName attribute.  A BankHolder can have
  any number of Account instances, but no account holder can have multiple accounts of any type
  (that is, no one will have two checking accounts)

acctType is a char indicated with the following key:
C=checking
S=savings
D=certificate of deposit
B=business account

  Note that a BankHolder may have 0 - 3 accounts.  Business account holders only have
  1 account.  Some BankHolders haven't completed their applications and will have 0
  accounts at this time.


Data will be retrieved using the following function called bankers().  Note its return type.You must only call this function only 1 time toward the beginning of your main() function.
You must #include <vector>.

Requirements:
format of output.

Person 1:
                Checking account balance $xxx.xx

                … (other accounts and balances they may have)
TOTAL BALANCE FOR Person 1:$xxxxx
------------------------------------------------------------
*Person 2:
                *** Checking account balance $-xxx.xx  ***
                … (other accounts and balances they may have)
*TOTAL BALANCE FOR Person 2:$xxxxx
------------------------------------------------------------
-Person 3:
                -Accounts are pending
------------------------------------------------------------
+Company 1

                Business account balance:$xxx.xx
+TOTAL BALANCE FOR Company 1:-$xxx.xx
