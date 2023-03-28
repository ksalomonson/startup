# startup

Have you ever struggled to find the motivation to accomplish your daily tasks?
Now RPG Daily Planner will help you organize those tasks into a convientent list and help you stay motivated with the power of gaming. This app lets you input quests and gives you expeirence points (xp) when you accomplish your tasks. You can level up and compare your score with the global leaderboard.

https://lostindev.click/

sudo service caddy restart

___.pem

I learned that for linking the proper format is : <li><a href="index.html">Home</a></li> (Link won't work because raw code is posted here
When deploying, make sure you're in the correct folder
HTML formatting is eazy until you start putting in fillable fields.

Command for deploy: ./deployFiles.sh -k ~/OneDrive/Documents/260/production.pem -h lostindev.click -s simon

CSS is hard, make sure that you take the Flex and set the parameters correctly.

------------random notes for midterm----------------------------------------------------------
Javascript is hard

const c () => {}

promises are also hard.

.then()

--simon service--
Functinally, using caddy is a lot like using javascript for anything else. It has similar synatx and similar deployments. The most important thing will be keeping track of which ports I'm hosting my software on.

Random useful code snipits for express:
const express = require('express');
const app = express();

app.listen(port, () => {
  console.log(`Listening on port ${port}`);
});

--Simon database--
Had to add "" around username and pass inside java code.
to find connection files, but click the production file
Remember to use nano not vi, vi is impossible

--simon login--
Stuff learned:
I learned about keeping credentials out of your code and github along with configuring mongo to dynamically assign variables into databases.
I also learned about using cookies to store the authtoken and why you would want to do such a thing.
