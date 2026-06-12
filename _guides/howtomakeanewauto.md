---
title: "How to Make a New Auto"
order: 5
---

<p>First, open <a href="https://github.com/mjansen4857/pathplanner/releases" target="_blank" class="btn">PathPlanner</a>.<br>
    Once it is open, click the '+' button in the top right corner.<br>
    <img src="assets/images/howtomakeanewauto/1.png" alt="image 1"><br>
    A new auto will appear. If it is the first auto that has been made, it will be called 'New Auto'. Each subsequent auto that is made (if the first is still called 'New Auto') will add one 'New ' to the front of the title.<br>
    (In this example, somewhere within the folders are the autos 'New Auto' and 'New New Auto', so the newly created auto is called 'New New New Auto'.)<br>
    <img src="assets/images/howtomakeanewauto/2.png" alt="image 2"><br>
    Click the '+' button in the top right corner to add commands, paths, and other things to your auto.<br>
    <img src="assets/images/howtomakeanewauto/3.png" alt="image 3"><br>
    To change the name of the auto, double-click on the name.<br>
    An important thing to remember is that, after changing the data in any field of PathPlanner, it is necessary to press enter. Otherwise, after a time interval, it will reset to the previous data.<br>
    <img src="assets/images/howtomakeanewauto/4.png" alt="image 4"><br>
    Open <a href="https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html" target="_blank" class="btn">WPILib VS Code</a>.<br>
    Add this line in your Autos.java file:<br>
           autoChooser.addOption('name', AutoBuilder.buildAuto('PathPlanner name'));<br>
    Replace 'name' with the text that you want to be seen in the auto chooser; replace 'PathPlanner name' with the name of the auto.<br>
        This line should be within<br><br>

    public class Autos {<br>
        &nbsp;&nbsp;&nbsp;&nbsp;public Autos(subsystems) {<br>
            &nbsp;&nbsp;line here<br>
        &nbsp;&nbsp;&nbsp;&nbsp;}<br>
    }<br>
    <img src="assets/images/howtomakeanewauto/5.png" alt="image 5"></p>
