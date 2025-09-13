Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

21) Because it was assigned to start 00:00

22) the display string shows the value you've entered in Int

23) You will need to call the timeTick method 60 times. You could do this in another way by
right clicking on the clockDisplay diagram, clicking new clockDisplay and setting your own chosen int.
or do setTime.

24) NumberDisplay digit = new NumberDisplay(10);

25) Rectangle window = new Rectangle (20,10);

26) This is a separate method that allows you to type in your own values. Compared to the other method, the clock display
starts at 00:00

27) For the first constructor, the role for the updateDisplay to display 00:00 after the object is created because
this method always starts at 00:00. You cant choose your own desired values.
For the second constructor, setTime replaces it. Since the second method allows you to choose what time you want, 
you do not need an updateDisplay.

28) Method 1)  p1.print("I love vanier", true)
    Method 2) int Status = p1.getValue(67);
    
29) wall, window, roof, sun.

30)         roof.changeSize(60, 180);
            roof.moveHorizontal(20);
            roof.moveVertical(-60);
            roof.makeVisible();
            
31) Of course

32) 2

33) i tried (-8 % 3); and it worked.

34) 0,1,2,3,4

35) I dont understand.

36)