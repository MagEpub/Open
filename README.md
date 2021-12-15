1) I don't know how to program, 2) I don't know how to use GitHub      Please be patient.
2) I wasn't kidding when I said I don't know how to program or use github.  Just a smattering of dos, bash, pshell, lots of forgotten ones.  Autohotkey is what I'm best at and that's not much.
3) This is some beginner level documentation for the Automa Chrome Plugin, which I discovered about a week ago (12/1/2021) and may be just the thing for an RPA (robotic process automation) project I'm working on.
4) I wasn't having much luck with how the variables and data is stored (I don't know javascript or .json), but I realized I could store the information on the web page, and it would be a great tool for beginners.

<b> If you are brand new to Automa scroll down to "Let's begin"</b>

Before starting:  Install Automa from the Chrome web store, and make sure file access is enabled

How it works
a) Create a simple html web page with input boxes
b) open it in chrome with file:///
c) The element selectors are always the same, making learning easier.
e) The script opens the page and writes the word "one" in the input box

There are three files

AFS New Tab Write.json = the script.  Import it into Automa (scripts are called workflows)

AFS New Tab Write.txt = all the settings for the blocks.  For now I'm storing this in a global variable in the workflow

testpage.htm = the page to practice on.

I plan to publish the actual sequence of steps soon.

Thank you to https://github.com/Kholid060 who created Automa

------------------------------------------------------------------------------------------------
<!-- a normal html comment -->
<!-- filenames are case sensitive-->

Once Automa is installed, go into chrome's extensions manager.  My settings are 

site access = on all sites

allow in cognito = on

allow access to file urls = on (that's important if you want to try out testpage.htm)

I notice no matter how often I set it to all sites it keeps getting changed back to on click, ymmv

<!-- ![abc](https://github.com/MagEpub/Non-Public/blob/main/automa%20chrome%20settings.png?raw=true) -->
![abc](https://github.com/MagEpub/Non-Public/blob/main/automa%20chrome%20settings.png?raw=true)

<b>Let's begin.</b>  Here is the procedure for the simplest workflow you can create:

1.  Click on Automa

![a1](https://github.com/MagEpub/Non-Public/blob/main/a1.png?raw=true)

2.  Click on Dashboard

![a2](https://github.com/MagEpub/Non-Public/blob/main/a2.png?raw=true)
<!--  ![a2](?raw=true)  -->

3.  Click on workflows

 ![a3](https://github.com/MagEpub/Non-Public/blob/main/a3.png?raw=true)
 
4.  Click New Workflow

 ![a4](https://github.com/MagEpub/Non-Public/blob/main/a4.png?raw=true)
 
5.  Name your workflow bing and click Add

 ![a5](https://github.com/MagEpub/Non-Public/blob/main/a5.png?raw=true)
 
6.  Click on your new workflow right where it says bing
   
![a6](https://github.com/MagEpub/Non-Public/blob/main/a6.png?raw=true)

7.  Click and hold on New Tab, and drag it up near Trigger

 ![a7](https://github.com/MagEpub/Non-Public/blob/main/a7.png?raw=true)
 
8.  Click and hold on the white circle on Trigger and drag a connectrion to the black circle on New Tab

 ![a8](https://github.com/MagEpub/Non-Public/blob/main/a8.png?raw=true)
 
9. Hover the mouse over New Tab to get the dropdown menu with the edit pencil and the trash can.  Click on the edit pencil.

 ![a9](https://github.com/MagEpub/Non-Public/blob/main/a9.png?raw=true)
 
10.  Type http://bing.com where it says http://example.com

 ![a10](https://github.com/MagEpub/Non-Public/blob/main/a10.png?raw=true)
 
11.  Click Save

 ![a11](https://github.com/MagEpub/Non-Public/blob/main/a11.png?raw=true)
 
You have finished writing your first workflow.  Now let's test it.

12.  Click on Execute

 ![a12](https://github.com/MagEpub/Non-Public/blob/main/a12.png?raw=true)
 
A new tab will open and go to bing.  Now let's check on how our workflow ran.  

13.  Click on the Automa icon in the new tab, then on the workflow name right where it says bing

 ![a13](https://github.com/MagEpub/Non-Public/blob/main/a13.png?raw=true)
 
14.  Click on Logs

 ![a14](https://github.com/MagEpub/Non-Public/blob/main/a14.png?raw=true)
 
15.  Click on the word bing for he newest one

 ![a15](https://github.com/MagEpub/Non-Public/blob/main/a15.png?raw=true)
 
16.  You'll see trigger and new tab ran.  The brown box with [] in it is for any data you created, but you didn't create any.  This is the end of the procedure for the simplest workflow you can create.

 ![a16](https://github.com/MagEpub/Non-Public/blob/main/a16.png?raw=true)
