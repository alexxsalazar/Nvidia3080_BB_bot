Originally I had intended this bot to only be used by me but nvidia bot situation is crazy so I thought I would level the playing field by releasing this. I do not intend to maintain this project. I am publishing this to hopefully help people create their own bots for these sites. I don't make bots to purchase items so if you have any questions or suggestions feel free to reach out to me. This bot is for Best Buy. I feel like most other bots have been made by the community this seems to be the only one missing.

**Before starting the please read the following section.**

**You need 2 things for this bot to work**
1. A virtual card. You can get these from privacy.command
2. Web cookie after valid sensor data has been sent by the browser

**What cookie?**

[Here is a picture of what the cookie values will look like](https://imgs.developpaper.com/imgs/2561717502-cccff2c795e46080_articlex.png).
Notice that the _abck cookie has a 1 value in between the first ~ ~. Make sure that when you copy your _abck it has a 0 value inside. Keep browsing until that area has a 0. You're going to paste all your cookies in data/sensor_data_cookie.json . Some of you might be wondering why this has to be done this way. The reason is that sensor data is trasnmitted from your browser to the server to in a sense legitimize that you are not a bot. The way this sensor data is produced changes over time so I felt like this was the most reliable way to inject it in. Every couple hours you will have to change the cookies used. I like to do this is use an incognito window, surf Best Buy a bit and copy the cookie. Apparently this is popular in the shoe bot wor

**Why do I need a virtual card?**

With a virtual card Best Buy does not make you go through 3dsecure checks which would add extra calls and frankly I did not want my actual card to be flagged or something. A credit card will not work only a virtual card.


To build install the requirements and then use the command

`python3 app.py`

This open up a GUI. If you look up bird bot on github you can look through the documentation they made for their GUI. The GUI works the same way. Just different bot. 

Please be responsible when using this. Use it only for yourself. Don't scalp.

**Again please feel free to use the code bot code in your own bots. Look through the API calls it makes.** 

**Also I would like to give credit to the BirdBot repository created by Nate Wong and contributors. Even though it has an MIT license I feel this is neccesary because I really liked their GUI and the project. It is no longer being maintained so please do not bother them with questions. I fixed up the actual bot portion. I kept their GUI.**