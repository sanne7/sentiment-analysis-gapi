 
This program is used to measure sentiment of each comment; And also overall sentiment of all conversations.

Environment: Python, Google NLP, Linux

Requirements
* Setup GCP account.
* Copy all credentials into separate file;  Let's say cred-xyz.json 

* content of cred-xyz.json 
{
"type": "",
  "project_id": "",
  "private_key_id": "",
  "private_key": "",
  "client_email": "",
  "client_id": "",
  "auth_uri": "",
  "token_uri": "",
  "auth_provider_x509_cert_url": "",
  "client_x509_cert_url": ""

}
Refer to documentation here 
https://developers.google.com/accounts/docs/application-default-credentials

* export GOOGLE_APPLICATION_CREDENTIALS=/home/username/cred-xyz.json
* python sentiment-analysis-gapi.py JumanjiTweets.csv 




