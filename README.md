1) I don't know how to program, 2) I don't know how to use GitHub  Please be patient.
2) 
3) This is some beginner level documentation for the Automa Chrome Plugin, which I discovered about a week ago and may be just the thing for an RPA (robotic process automation) project I'm working on.
4) I wasn't having much luck with how the variables and data is stored (I don't know javascript or .json), but I realized I could store the information on the web page, and it would be a great tool for beginners.

Before starting:  Install Automa from the Chrome web store, and make sure file access is enabled

How it works
a) Create a simple html web page with input boxes
b) open it in chrome with file:///
c) The element selectors are always the same, making learning easier.
e) The script opens the page and writes the word "one" in the input box

There are three files
AFS New Tab Write.json = the script.  Import it into Automa
AFS New Tab Write.txt = all the settings for the blocks
testpage.htm = the page to practice on.

If you want to write your own here is the whole thing:


<!DOCTYPE html>
<html>
<body>
<h1>Automa File System v0.001</h1>

<form action="/action_page.php">

<label for="1">For this box, use element selector #\31</label>	
  <input type="text" id="1" name="1"><br><br>

<label for="2">For this box, use element selector #\32</label>	
  <input type="text" id="2" name="2"><br><br>

<label for="3">For this box, use element selector #\33</label>	
  <input type="text" id="3" name="3"><br><br>

<label for="4">For this box, use element selector #\34</label>	
  <input type="text" id="4" name="4"><br><br>

<label for="5">For this box, use element selector #\35</label>	
  <input type="text" id="5" name="5"><br><br>

</form>

<!--https://github.com/MagEpub 6 Dec 2021-->

</body>
</html>    

I plan to publish the actual sequence of steps soon.

Thank you to https://github.com/Kholid060 who created Automa
