# vids.lol #
*a random website containing reaction videos that embed into discord.*
The url's of the videos on this website were designed to be easy to memorise so you can use them whenever you want without having to come here to check.

#### contributing a video ####
If you want to contribute a video, first make a fork of the repository, and locally download it to your device.
After that, copy the **templatevideo** folder and rename it to what you want your reaction video to be called.
Inside of your new folder you should see an `index.html` file, and a video file named `templatevideo.mp4`. **PLEASE REPLACE THIS WITH YOUR ACTUAL VIDEO AND RE-NAME IT TO SOMETHING** (preferably the name of the folder) There are some instructions inside but I will also list them here in a bit more detail:

- On **line 8** of the file, replace the first part of the url with your folder name, and the second part with your video name. EG: `https://vidz.lol/myawesomereaction/myawesomereaction.mp4`
- On **lines 10 and 11** you can change the videos dimensions. **This only really matters if you actually go and visit the page** so you dont have to change these but you can if you want
- On **line 14** replace the url with your folder name, EG: `https://vidz.lol/myawesomereaction`
- On **line 17** do the same thing as **line 8**
- At `line 42` replace the file after `source src=` with your video name, EG: `myawesomereaction.mp4`


Finally, go to the `videos.json` file in the repo and add your video like this:
```
    {
        "name": "whatever you have named your video, this will show up on the website..",
        "url": "what you named your folder with a slash at the end/" 
    }
```
##### PR Requirements #####

Your video should meet the following requirements:
- Must be 3 seconds or longer (you can freeze your video at the end, because the only reason this rule exists is to make sure it embeds into discord propperly)
- No NSFW/gore content
- No slurs/cuss words
- Make your folder/url unique but also easy to remember

Obviously, there might be exceptions made at certain times blah blah blah.

# in the future i might possible re-write the way that videos are stored to make it even easier to contribute, but for now it will stay like this.
