# ig-autopost
Automation script for Instagram photo upload 


## Step 1:
   Install ‘instabot‘ package using the below command in the terminal. 
```
pip install instabot
```

```
Step 2:
Import class ‘Bot‘ from ‘instabot‘ package. 
from instabot import Bot 
Step 3:
Create a varibale let’s say ‘bot’ and store the class ‘Bot’ in it.
bot = Bot() 
Step 4:
Login to your instagram account using the below command. Provide your Instagram ‘username’ and ‘password’.

filter_none
brightness_4
bot.login(username = "******",  
          password = "ppppppp") 
Step 5:
Upload your photo using the following command.

filter_none
brightness_4
bot.upload_photo("provide the path to the picture here",  
           caption = "provide the caption that you \ 
           want to display on the post here") 
```
