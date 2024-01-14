Did someone provided you their public PGP key to send them secure email? or

Do you have their PGP public key from a website and you need to send them an email securely?

- Then below info should guide to send email using their PGP key - See Importing public key

-------------

Mail Encryption - Use PGP for sensitive data sharing via email

Example Application - Thunderbird, supports on mulitple OS (Win, Mac, Linux)

# Creating new key

- Go to Setting > Privacy and security > Account settings in Email end to end encryption
- In account settings > End to end encryption > Add key > Create new openpgp key if you don't have one
- Set expiry and key size, then click generate key and confirm

# Exporting public Key

- In the same end to end encryption, account setting location > OpenPGP Key Manager
- selelct the mail for which you wanted to export key > file > Export the public key as file or via email
- Now you can provide your key for someone who wants to send you encrypted emails

# Importing Public Key

- click on OpenPGP Key Manager as guided above in settings.
- Assuming you have recepient's PGP key and copied to clipboard
- Go to Edit > Import keys from clipboard.
- Once imported you should see the receiver's email associated with their provided key
- now you have their email address, create a new message and enter receivers address in To field
- click enter after entering recievers address and thunerbird should prompt you to "Encrypt" saying OpenPGP end to end encryption is possible for that receiver.
