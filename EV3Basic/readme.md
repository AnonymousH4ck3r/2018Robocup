# Round 2: 21/07/2018

# Introduction:

This day as we tested the program, we came to some problems. This time, our Mum hadn't been giving us very little hints our any little advise, so we were put to a independent test. Here are some problems we went through. 

# Problems:

* 1. Our robot kept going off track when it came to curves or sharp turns. We fixed it by changing the speed down and found out that the speed can not be too fast nor too slow

* 2. The sensors are wearing out or going out when we are testing our code. We still haven't figured out why yet!

* 3. Our robot sometimes break-dances (Moves to the right and then the left) for unknown reasons.   



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

Second final modifications: 

Foward Speed: 15
Charge down: 1.4 sec 

The final code is good but the parents mucked it up for a good and bad reason. They advised us to changed the speed and sensor position and now it is not going the best, but the good thing is that it can make it to the destination in time. It is a really big risk and is still kind of buggy!

Last final modifications:

Forward Speed: 20
Charge Down: 1.4 sec

========================================

# Robot Coding Class:

Things I learned:

* You can not put end program blocks in loops, or switches

* The Repeat block can be used as a repeat until block

* Don't use too much loop blocks 

# #2 Robot Coding Class With Aron

* How to use the NXT sound sensor

* One rotation with one motor speed at 0 will do a 90 degree spin

* Normal a clap will reach to the sound level 21 and normal talk level can also reach to the sound level 21 or higher and it can be done with 4 blocks without using a loop ? repeat block

* I tried making a robot go forward with only 2 blocks and it was making a move tank block's condition time and make it run for a very long time (100000000000000000000000000000000000)

