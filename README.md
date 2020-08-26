# mz-cinnamon

This is a simple project comparing two files in CSV format with financial transactions.

Basic assumptions are as follows:

1- The file structure is the same on both files.
2- The main field to compare is the TransactionID.
3- However, there are two other fields TransactionAmount and WalletReference in case a transaction could not be match exactly.
4- The unmatched report highlight those transactions suspected to be the same, but manual revision is needed.
