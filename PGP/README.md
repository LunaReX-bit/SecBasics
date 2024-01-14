Mail Encryption - Use PGP for sensitive data sharing via email

Example Application - Thunderbird, supports on mulitple OS (Win, Mac, Linux)

Creating new key -

- Go to Setting > Privacy and security > Account settings in Email end to end encryption
- In account settings > End to end encryption > Add key > Create new openpgp key if you don't have one
- Set expiry and key size, then click generate key and confirm

Exporting public Key -

- In the same end to end encryption, account setting location > OpenPGP Key Manager
- selelct the mail for which you wanted to export key > file > Export the public key as file or via email
- Now you can provide your key for someone who wants to send you encrypted emails

Importing Public Key - 

- click on OpenPGP Key Manager as guided above in settings.
- Assuming you have recepient's PGP key and copied to clipboard
- Go to Edit > Import keys from clipboard.
- Once imported you should see the receiver's email associated with their provided key
