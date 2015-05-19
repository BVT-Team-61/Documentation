# Programming Style
None of the following are errors, they are best practices for easy to read code. This is primarily for future reference. **If you want the short version, just read the bold parts.**

###Capitalization:
I noticed in your code that the solenoids are named 'Up' and 'Down'. To avoid confusion between objects and classes, they should be named 'up' and 'down'. The same goes for the functions 'BucketUp' and 'BucketDown'. **Only classes should start with a capital letter. Variables and functions should start with a lowercase letter.**

###Nouns/Verbs:
In the 2015 code, the names of all the subsystems are one noun. **Its quite important that these nouns are specific and unique.** In the [2014 code](https://github.com/wastevensv/Team61RobotProject), the subsystem names were DriveTrain, Arm, Armapult, Grasper, Shifter. Arm and DriveTrain makes sense. Grasper probably should have been called Hand (or the functions could have just been put into the Arm subsystem). Shifter's purpose still confuses me today. Armapult is probably the worst name of all, its not a real word, and it can easily be confused with Arm.

**The names of all the commands are generally a noun then a verb** (ClawSpin, ClawToggle). Some commands like DriveForDistance, ClawMoveAuto, and ElevWithJoysticks don't follow this convention. This isn't exactly a good thing. Maybe thats something you can improve next year.

###Order of Functions:
In Java, the order you place the functions has no effect on the functionality of the program (this is different in other languages like Python and C). Because the order doesn't matter, the functions can be ordered in order of importance, in order of execution, or even alphabetically. **Go with whatever makes sense to you as long as there is some kind of consistent order.** In the Bucket subsystem initDefaultCommand should probably be placed first since it is an initialization function. Thats not a really big deal, but its a good practice.

###Indentation:
I'm sure by now you've noticed how picky I am about whitespace. **Each time you open a curly bracket '{' everything between that and the closing bracket '}' should be indented. Tabs are okay. But 2-4 spaces are better.** This is because spaces are the same no matter what text editor you use. A tab can appear differently in different text editors (Notepad++ has 'smart tabs' that can cause problems in other editors). The 'initialize' function in 'BucketLift' is missing its indentation. One error usually isn't noticeably different, but code with no indents (or even worse, inconsistent indentation) in nearly impossible to read.

###Names:
'up' and 'down' are good names for the solenoids in Bucket. They describe what they do and are short and easy to remember. An alternative is changing them to 'upSolenoid' and 'downSolenoid' so that you know what they are and what they do. **Its a tradeoff between length and specificness.** This is probably the most nitpicky suggestion of them all. Following this suggestion is totally up to you as the programmer.
