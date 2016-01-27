# PyTwt
### Install  
Open *Terminal*:  
```bash
sudo pip install twitter
git clone https://github.com/ifedyukin/PyTwt.git
chmod +x PyTwt/post
```  

### Create Twitter Application
+ Go to [Twitter.Apps](https://apps.twitter.com/app/new)
+ Fill in all fields
+ Push *Create...* button  

### Configuration  
+ Go to *Key and Access Tokens* page for your application
+ Generate new *Access Token*
+ Copy *access_token*, *access_token_secret*, *consumer_key*, *consumer_secret* and Paste to *post* file  

### Using  
Open *Terminal*:  
```bash
./post "twitter post text"
```  