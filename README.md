# mz-cinnamon

This is a simple project comparing two files in CSV format with financial transactions.

Basic assumptions are as follows:

1. The file structure is the same on both files.
2. The main field to compare is the TransactionID.
3. However, there are two other fields TransactionAmount and WalletReference in case a transaction could not be match exactly.
4. The unmatched report highlight those transactions suspected to be the same, but manual revision is needed.


Technologies used:

1. Java 8
2. Spring Boot
3. jQuery and jQuery UI
4. jQuery DataTables
5. Apache Commons CSV
6. JPA
7. Maven

Source Control and Deployment:

1. Git
2. Heroku

The application is deployed at the following URL:
https://trx-compare.herokuapp.com/
