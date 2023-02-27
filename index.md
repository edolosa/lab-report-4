# **Lab Report 4 - Done Quick**
***

## Before the timer:

![Image](https://cdn.discordapp.com/attachments/717860504093327450/1079846936678506547/image.png)

Before starting the timer, I have a text file of the compile and run commands that I need to use during the challenges, this allows for easy access
of code without having to go to my browser to find them.

Also before the timer, have the ssh link for the lab7 repository already copied to your clipboard, such that it'll be printed out when you input `<CTRL-V>`

One last thing, is to have your `ssh` log in command be the last command on your local terminal.

## Step 4: Log into ineg6.

![Image](https://media.discordapp.net/attachments/717860504093327450/1079845282885406791/image.png)

Since the `ssh cs15lwi23ago@ieng6.ucsd.edu` was the last command I put on my local terminal, all I had to do to get it and log in
was to press `<up>` and `<enter>`. Since I had my ssh key already set up, I did not have to input my password and was automatically logged in.

## Step 5: Cloning my fork from my Github account.

![Image](https://media.discordapp.net/attachments/717860504093327450/1079846455004643368/image.png)
 
Prior to starting the timer, I had already had the ssh link for the lab7 repository copied, so to get this all I had to type was:

`$ git clone <CTRL-V>`

## Step 6: Running the tests and showing that they fail.

I then copied the `javac` and `java` code lines along with the line right below the `java` line so that when you use `<CTRL-V>` the code will be compiled then ran instantly. This would be lines 1-3 of the text file, (refer to first image of this page).

I then `cd` into the lab7 file with `$ cd lab7`.

Then input `<CTRL-V>`. The output looks as such:

![Image](https://media.discordapp.net/attachments/717860504093327450/1079848442668523580/image.png)

## Step 7: Edit the code file to fix the failing test.

I input `$ nano ListExamples.java`

Then held `<down>` until I reached two lines above the return line. I would then use `<up>` or `<down>` accordingly if I missed the line.

I pressed `<right>` 12 times, then changed `index1` to `index2` with a quick `BACKSPACE` followed by a `2`.

![Image](https://media.discordapp.net/attachments/717860504093327450/1079849702998147102/image.png)

I then pressed `<CTRL-X>`, `<Y>` then `<ENTER>`. This saved my changes and exited out of nano.

![Image](https://media.discordapp.net/attachments/717860504093327450/1079850276627939348/image.png)

## Step 8: Run the tests, demonstrating that they now succeed.

Since I haven't copied anything else since step 6, I am able to press `<CTRL-V>` and the files will once again compile and run instantly.

![Image](https://media.discordapp.net/attachments/717860504093327450/1079850877839474773/image.png)

## Step 9: Commit and push the resulting change to your Github account.

Next, I copied lines 4-7 of my text file which contains my needed inputs for commiting and pushing (refer to the first image of this page). 

After copying I then press `<CTRL-V>` and my changes are committed and pushed instantly.

![image](https://user-images.githubusercontent.com/122570924/221667782-3923ef62-b7e3-4261-a3bf-405f04285b59.png)
