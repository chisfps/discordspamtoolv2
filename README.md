# Discord Spammer V2
A simple python spammer tool. (Used for Discord)

**I had an old one, but it would simulate the keyboard, so you had to stay on the Discord application. It would also lag ALL THE TIME, so I remade it!**
How this one works is that it sends message requests through your discord token in the channel url you put in.


# Installation
OPTIONAL: You can use Visual Studio or any IDE as you wish.

1. You will need to have [Python](https://python.org) installed.
2. Once Python is installed, open your command prompt and type "pip install requests"
3. Your done!

# Setup

1. Download the python file in releases.
2. Go to the website version of Discord.
3. On a random discord chat, do the shortcut Shift+Control+I (Opens Inspect Element)
4. Go to the network tab.
5. Now send a random message to the DM you are on.
6. A "messages" option should appear. Click it.
7. Scroll down to Authorization and copy the token. (WARNING: DO NOT SHARE YOUR TOKEN WITH ANYONE. THEY CAN INSTANTY LOGON TO YOUR DISCORD ACCOUNT WITH IT!)
8. Open to edit your Python file.
9. in the auth line where the '' are, put your token in between.
10. Go back to the inspect element and copy the request URL at the top.
11. Copy it and put it into the requests.post line (this is the channel where your message will be spammed in, either it's a group dm, dm, or server channel, dosen't matter)
12. After, you can put whatever message you want in the content line.
13. And in the for i in range line, you change the number to the amount of times you want that message to be spammed.
14. And you're done!
