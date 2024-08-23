Input Format
Number of Users (N):

The first line contains an integer N, which is the number of users.
User Information:

The next N lines each contain two integers:
userID: the user's identifier.
balance: the user's current balance.
Number of Transactions (T):

The following line contains an integer T, which is the number of transactions.
Transaction Details:

The next T lines each contain three integers:
from_userID: the identifier of the user sending the funds.
to_userID: the identifier of the user receiving the funds.
amount: the amount of money being transferred.
Output Format
Transaction Results:

For each transaction, print:
"Success" if the transaction was completed successfully.
"Failure" if the transaction failed.
Final User Balances:

After processing all transactions, print each user’s userID and their remaining balance, sorted by:
Balance in descending order.
For users with the same balance, sort by userID in ascending order.
