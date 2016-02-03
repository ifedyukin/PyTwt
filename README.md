# PyTwt
### Install  
Open *Terminal*:  
```bash
sudo pip install twitter
sudo pip install termcolor
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
##### Text post
Open *Terminal*:  
```bash
./post "twitter post text"
Tweet "twitter post text" was published.
```  
##### Text post with IMG-file
Open *Terminal*:  
```bash
./post "twitter post text" img.png
Tweet "twitter post text" + "IMG" was published.
```  
##### Several text posts
Open *Terminal*:  
```bash
./post --c
Input text and push Enter for post.
Input /exit for finish this.
>Tweet1
Tweet "Tweet1" was published.
>Tweet2
Tweet "Tweet2" was published.
>/exit
Finish program.
```  