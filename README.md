# cloudprojectsAWS
This will house all my beginner cloud computing and cloud security projects on AWS

Best Practices of the 2nd Project on IAM

1. Do not use your AWS root account, instead, create an IAM user and attach policies to it to facilitate your daily activities on the AWS Console.

2. Always download the .csv file of an IAM user before closing the user creation interface. This file contains his/her username, password (not shown), access key and unique
link for that specific user to log in.

3. Create groups and attach policies to it if you have numerous IAM users who have same access levels. This always all users under the group inherit set permissions instead
of attaching permissions to users individually.

4. Take a screenshot of the QR code for the MFA and store it in a safe place; this is incase you forget your password or delete the authenticator application as you will not
be able to access the IAM account without it.
