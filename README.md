# features 
- token validation
- message sending
- customizable cooldown
- supports up to 10 users
- changeable groupchat name
- changeable groupchat profile picture

# os support
- windows
- linux

# requiremnts 
- python 3.x

# usage
- git clone crime > **git clone https://github.com/unconfiguring/crime**
- install requirements in command prompt > **pip install -r requirements.txt** in the directory you installed crime in
- configure config.json **example below this**
- crime.py

# example of config.json
```js
{
    "token": "MTI1NjA5Mz----Y0ODIwODM4YT.GPtmD1.qV78wCddn---5CTMjgg3SiZiR----IOzPpJpFoU",

    "user_ids": [
        "1256093368648254284",  
        "1088847910990490684"
    ],

    "default_name": false,

    "cycle_names": true,

    "name_list": [
        "example",
        "example",
        "example",
        "example",
        "example"
    ],

    "send_message": true,
    "message": "@everyone @here this is an example message",

    "change_profile_picture": true,
    "profile_picture_path": "c:\\users\\example\\downloads\\example.png"
}
```

