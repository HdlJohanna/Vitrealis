# GitHub
Discord/Github Connection Utils

* Create Webhooks  
* View Repository insights  
* Manage Webhooks  

## Initialize your Account
Account Syncs are currently handled via AUTH-Tokens [(How do we use your Data?)](#privacy).  
Connect to your Account: `gh init key`. The Bot will dm you, asking for your API-Token. This is a One-time-setup.  

Connect a Webhook: `gh init logs user/repo #channel`.  
This will create a Webhook pointing to https://github.zerotwo36.repl.co


### Privacy
We handle your Data with great Care: Your Access Tokens will be encrypted using Python's [Fernet](https://cryptography.io/en/latest/fernet/) before being saved. I will never ever read your Tokens. That's all I can say.
