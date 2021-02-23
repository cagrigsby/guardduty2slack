# guardduty2slack

#In order to use this template, you must place the .zip file, which contains the lambda function
#into an s3 bucket, and you must code this, as well as the zip file, into lines 84 and 85. 
#Furthermore, you must create a customer managed KMS key in order to encrypt the slack webhook URL.
#This is because the lambda function assumes the environment variable for the slack webhook URL is 
#encrypted. It is noted in the function is that you need to scroll to environment variable and 
#encrypt the webhook URL function, but you will need to create the key first.
