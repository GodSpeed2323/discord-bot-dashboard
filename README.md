Welcome to the first public Discord Bot Dashboard!

+=Contributors=+
This code was created by yaman, LucasDevGames (LucasGamer213) and slem

If you need help please join our discord! http://discord.me/yaman


+=Getting Started=+

Firstly you must install NPM. But you might be wondering "Hmmm, how do I do that?" well read the next line to find out!

Before we start you must get node.js 

If you have already got that you can skip this step.

To install node.js you want to go to: https://nodejs.org/en/download/

and select your platform. Then you want to set it up. Once you have done you are good to go to the next step!

You can install NPM in windows by going to the 'discord-bot-dashboard' folder, once you are there make sure none of the files a selected (light blue). Then you want to hold 'CTRL' 'SHIFT' and then you want to two finger click on your mouse pad. If you use a mouse then you would click the right button on the mouse.
Now you want to click on the option 'Open PowerShell window here'. Click on that option then you will be directed to a different type of cmd. Once you are in a blue backgrounded window you want to type: 'npm install' and hit the enter or return key on your keyboard.

Congratulations! You have made it to part 2!

Now let's get your bot connected it!

Once the installation of the 'npm install' command is done you want to close the window.

Now let's create a bot user so we can use it!

To create a bot user go to: https://discordapp.com/developers/applications/me
If you have done this kind of stuff you might have a few bots listed below.
If you haven't then there should be nothing but a button called 'New App'.
You want to click that button. Once you have bene directed to the 'Create' page you want to fill out some stuff. Let's start of by getting a name! You can use any name you want. Make sure no more than 9,999 people have got that name, just don't choose a too pupolar name. Choose something unique! In the 'App name' you want to type the name that you choose, that name will be your bot name. In the 'App Description' you don't need to put nothing. If you just want to write a description of your bot feel free to! Then lastly on the 'App Icon' you want to click on the blue circle and browse a cool profile picture for your bot. It should look like this: https://i.imgur.com/JO32LAc.png Now to finish your app you want to click on 'Create App'.

Creating the bot user!

Ok now that you have created a app we want to create the user.

Do to that it is pretty simple. Scroll down the page and you will find a button called 'Create a Bot User' here is a image on where the button is: https://i.imgur.com/6yaQRA6.png Once you have clicked on 'Create a Bot User' a popup will show. You want to click 'Yes, do it!'. It will replace the 'Create a Bot User' button with some settings of your bot. What we want is the token. Make sure to not give that token to anyone or else someone could use your bot as their account. Click the the blue text next to 'Token:'. Some crazy letters with apair, that is your token. https://i.imgur.com/sTctGa6.png Now you want to copy it by hilighting the text and pressing 'CTRL' 'C' and 'CMD' 'C' for mac users. Once you have copied that you want to go to the bot dashboard file and find a file called 'config.json' open that file and where it says 'BOT_TOKEN' replace that with your token by pasting your token, 'CTRL' 'V' to paste and on Macs 'CMD' 'V'. If you would like another prefix instead of '!' you can change that to whatever you want. For those who are new to the discord.js library you might not know what a prefix is. So it is basically what you use before doing a command. Here is a short example: %help the prefix for the command 'help' is '%'.

Well done! You have connected your bot and now you are ready to run it!

To start the bot go to the bot dashboard folder and make sure no files are selected. You want to hold 'CTRL'
'SHIFT' two finger click to open up a option menu. On that option menu there will be a option called 'Open PowerShell window here'. Click that and a blue window will open. You want to type 'npm start' and you are good to go! To go to your dashboard you want to type on a url: localhost:3000 You will be directed you the dashboard. 

Now let's invite the bot to your server. So you want to go to the https://discordapp.com/developers/applications/me website and click on your application that you just made. Below your token there will be a button called 'Generate OAuth2 URL'. Click that button and you will be directed to a different page. On the 'SCOPES' settings below make sure that the 'bot' option is selected. Now we want to give the bot 'Administrator' permissions. So below the 'SCOPES' settings there will be another settings called 'Bot Permissions' make sure that the 'Administrator' permission is checked. Now you have to get a link. Which should be right above the 'Bot Permissions' settings. Copy that link to the url and hit enter. On a dropdown select the server where you want your bot to go. Then click 'Authorize' button. Lastly you want to do a reCaptcha to make sure you are not a robot. Finish that reCaptcha and you should be good to go!S


+=Optinal Things=+

If you would like your own custom bot with your own code you can do that!

Go to the bot dashboard file and go to a folder called 'discord-bot-sourcefiles' there should be two files, one named 'bot-commands.json' and the other one named 'main.js'. Open the main.js file and enter your code there.

+=Writer=+

LucasGamer213