# SQL Password<br />SQL Password is a password recovery tool for Microsoft SQL Server that can recover password for registered user accounts. The following versions of MS SQL Server are supported: 2000, 2005, 2005 Express as well as Microsoft SQL Server Desktop Engine (MSDE) 2000.
Because of the nature of the security system used in MS SQL Server, you have two options when recovering lost or forgotten passwords:
1) you can try to recover the original password. MS SQL Server encrypts passwords and they cannot be easily decrypted, so SQL Password uses the following recovery methods to crack them:
Brute Force Attack
Dictionary Attack
Smart Force Attack
Although there is a guarantee that the password will be recovered, it may take a long time. So, in most cases (i.e. an administrator who has forgotten his or her password) the best option is the second one:
2) you can reset the password to a known one. SQL Password performs this operation instantly by modifying the master.mdf file where SQL Server stores passwords. If you use this feature, you do not have to wait until the password is cracked, though the original password remains unknown.
This change is transparent and you may continue to work with the database as usual, using the new password to log on. You can use SQL Password to recover or reset any password found in the user accounts file of MS SQL Server, including the password for the system administrator (whose username is ‘sa’).
Like every other our password recovery tool, SQL Password is efficient, reliable and easy-to-use. We constantly update it to support the latest versions of MS SQL Server. The latest version supported at the moment is 2005.
Note: if SQL Server is configured to use the standard Windows security accounts (“Windows authentication mode”), SQL Password will not be able to recover passwords.<br />[>> Detailed information](https://secure.shareit.com/shareit/product.html?productid=300084606&affiliateid=200057808)