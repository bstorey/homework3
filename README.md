## Part One
I had some trouble with the homework, not because of the actual work but because the way IntelliJ does things differently. We should talk about how you write code and maybe I can learn more about your method.

1. *Edit Dog.java and fill in the portions where specified by comments. You're going to be writing setters and getters.*
I wrote the standard getters and setters for all the values. For feed() and play() methods, I set up a numerical value to represent the size (sizeState). I then created two private methods (sizeToSizeState() and sizeStateToSize()) to go between the sizes and set the values. I then applied those methods to feed() and play() to change the size based off of the number of feeds/plays. For cutHair() I just subtracted the HAIR_CUT_LENGTH from the current hair length and made sure the hair length was set to 0f if it went below 0f.
2. *After you've finished, compile your Java code.*
This gave me some problems. I'm still working through how IntelliJ sets up projects but I was ultimately able to compile the code.
3. *Correct compilation errors as they are a result of modifications made by you. After it returns successfully, cd into the bin directory:* 

`$ cd bin/`

4. *From within bin, execute your code*

5. *If you see a nice congrats message, you've implemented the methods properly.*
I executed the code within the project (see my coomment at the start) and I got the congrats message.



## Part Two

1. *Make sure you name the classes identically to their respective file names.* 
I extended the Dogs class and overwrote the necessary methods that applied to each java file.

2. *After you've finished, compile your Java code*

3. *Correct compilation errors as they are a result of modifications made by you. After it returns successfully, cd to the bin directory:*

`$ cd bin/`

4. *From within bin, execute your code*
 
5. *If you see a nice congrats message, you've written some pretty solid subclasses.*
I executed the code within the project (see my coomment at the start) and I got the congrats message.
