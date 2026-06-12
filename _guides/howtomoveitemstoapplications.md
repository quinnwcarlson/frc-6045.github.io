---
title: "How to Move Items to the Applications Folder (Mac)"
order: 10
---

<p>First, find the item that you want to move and write down its file path. You will need to shut down your computer, so you will not be able to copy and paste it.<br>
    Now, shut down your computer.<br>
    Hold the upper right key to turn it back on, but continue to hold while it says "Continue holding for startup options..." and until it says "Loading startup options...".<br>
    Click Options, then Continue. Once it has loaded, in the upper left, click Utilities and Terminal.<br>
    Type <code>cd ../../Volumes/"Macintosh HD"/Users/username</code>, where username is your username (example: 27johnhen), to get to your username folder.<br>
    From here, you can navigate to the folder that contains the item that you want to move as shown on <a href="howtonavigatefilesinterminal.html" class="btn">this page</a>.<br>
    Count the number of folder levels that you go through.<br>
    Once you have found it, type <code>mv "filename" ../../Applications</code>, but add one <code>../</code> near the others for each additional folder level that you went through.<br>
    For example, if it was in your Downloads folder, which is one folder level beneath your username folder, you would type <code>mv "filename" ../../../Applications</code>.<br>
    The reason for this number of <code>../</code>s is because the first moves it up one level to the username folder, then to the Users folder, then the Macintosh HD folder. Once it is here, it is moved into the Applications folder that is inside the Macintosh HD folder.<br>
    After you have moved everything that you want to, you can shut down your computer again and start it normally.
    </p>
