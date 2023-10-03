
Project-1

Important Considerations Before Running the Code.


1) For this project in order to try the code, it may pop up an error in the RobotTokenManager.java that doesnt let you run the code, to solve this, go to that file and in the function that provides the error in line 707, leave it without arguments.

2) Eventhough this version does not allow to play functions, it is because I had a small issue with some line that wouldn´t let me invoke properly a function, nevertheless if the function that I call for parsing would work it will execute the function. IMPORTANT in the console when you declare a function you will see the structure I used to store the information, and eventhough it does not run it, the same logic that is used to run a function was used to run the while and repeat.

3) If you wish to execute a while or a repeat you MUST define a function previously named "function". For Example,
   defproc function (a,b) {jump(1,2)} if you do so, the while and repeat will work just fine. Some examples we used      to try it where: {while can ( walk(1,back) ) {walk(1,back); walk(1,tright); leap(1,left) } } and for the repeat
   USER  INPUT: {repeat 5 times {walk(1,front); turn (tright)}}

4) Defined Variables may not work on cycles but they do on conditionals, (because cycles were implemeted the same way as a function would so that is a small isue with this). Neverhteless they are stored as well in a Hash.

5) An If should always go with and else when you declare a condition.

