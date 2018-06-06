# How to write the If command

```Small Basic
If Sensor.ReadRawValue(RightSensorPort, 1)=1 Or Sensor.ReadRawValue(RightSensorPort, 1)=7 Then
      Motor.Move ("C", 5, -360, "True")
    Else
      Motor.Move ("BC", 5, -360, "True")
    EndIf
```

# How to upload the code to your robot

* Save the code you have made under github version controlled folder (On my desktop, C:\Users\raymo\github\learnpython\EV3Basic)
* Find EV3 Explorer at C:\Program Files (x86)\Microsoft\Small Basic\lib\EV3Explorer\
* Double click the icon that says EV3Explorer (Make sure the robot is connected, if not, connect and retry)
* The right side should put C:\Users\raymo\github\learnpython\EV3Basic 
* The left side should be under /home/root/lms2012/prjs/
* Create a new folder using the new folder option (The folder name should be the same name as your code you are going to compile in it!)
* Go into that folder, select the code you want to compile into the robot, then click the compile option, and you should see it on the left side with the same name but just having .rbf at the end
* Unplug your robot (Optional but recommended!) and go to files (In your EV3 Robot!) and run your code
* Don't forget to git control your code!

# Robot History
Foward Speed: 15
Charge down: 1.4 sec 

The final code is good but the parents mucked it up for a good and bad reason. They advised us to changed the speed and sensor position and now it is not going the best, but the good thing is that it can make it to the destination in time. It is a really big risk and is still kind of buggy! 