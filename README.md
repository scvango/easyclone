# easyclone
This is just a bash script which aims to ease the process of cloning , moving and syncing and other rclone operations.
The script gives the option to either install the rclone modded binary called [fclone](https://github.com/mawaya/rclone) or [gclone](https://github.com/donwa/gclone) which helps us to bypass the 750GB daily limit by google present in rclone

![sample_pic](https://i.ibb.co/H4qHh1h/Screenshot-20210128-211947-2.jpg)

# Pre Requisites
* Firstly , you should have generated the service accounts and have them downloaded in a folder named accounts. Follow steps from [here](https://github.com/smartass08/Service-Accounts-to-Google-groups/blob/master/README.md) if you don't have service accounts yet. Also rename any of the json file as 1.json inside accounts folder
* Secondly , you need to make a new repository named accounts in your github account and upload all the service accounts json files directly in that repo.
* Lastly , you need to generate your own client id & secret from [here](https://developers.google.com/drive/api/v3/quickstart/python). It will have to be entered during config creation

# How to install / update
* ```bash <(curl -L http://tiny.cc/easyclone)```

The above given script is the only single thing one would need to do run to setup everything from scratch . According run it at a later stage to update script and binaries as and when needed.
Proceeding installation, just enter ```clone``` whenever you need to execute the script henceforth 

# Note for Termux Unrooted users
Since the original script needs access to root directory for adding script in source , i have made a separate script for unrooted termux users. Simply run the below given 2 commands
* 

# Credits
* [rclone](https://github.com/rclone/rclone)    -  for existing 
* [domwa](https://github.com/domwa/gclone)      -  for gclone 
* [mawaya](https://github.com/mawaya/rclone)    -  for fclone 
* [mervin](https://github.com/tomyummmm/gclone) -  for updating gclone
