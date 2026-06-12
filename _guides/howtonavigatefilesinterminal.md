---
title: "How to Navigate Files in Terminal (Mac)"
order: 11
---

<p>To navigate folders from within Terminal, you can use the commands cd, ls, pwd, and mv.<br>
        <ul><li><code>cd</code> changes the directory that you are in.</li>
        <li><code>ls</code> lists the files and folders within your current directory.</li>
        <li><code>mv</code> moves files and folders.</li>
        <li><code>pwd</code> prints the filepath of your current folder.</li></ul>
        For example, imagine that you have a folder called 6045, with folders inside it called robot and website.<br>
        The robot folder is currently empty, while the website folder has a file called website.html. You are currently in the 6045 folder.<br>
        Enter <code>ls</code> to learn that robot and website are in the folder.<br>
        Enter <code>pwd</code> to learn the location of the 6045 folder.<br>
        Enter <code>cd robot</code> to move to the robot folder.<br>
        Enter <code>cd ..</code> to move back up one level in the folder structure (back to the 6045 folder).<br>
        Enter <code>cd website</code> to move to the website folder.<br>
        Enter <code>mv website.html ../robot</code> to move the website.html file into the robot folder (through the 6045 folder).<br>
        Enter <code>ls</code> to learn that the website folder is now empty.
        
    </p>
