# Checkerboard Retrospective

#### 1. Reflect on (think about) the work you did for the challenge. How did you do? What did you get right? What did you get wrong? What did you do differently (and possibly better) than what was posted in the solution? What was hard to do?

Speaking in general terms, I think I did well on this project. I did well on the majority of the aspects of the project including
changing the colors on the board, changing the rows and columns of the board, and having the checkerboard respond to changes
in the size of the window. As far as things that didn't go well in the project, I could not get my checkerboard to fit tightly within
the parameters of the window. I set my lambda expression to listen for changes in the size of the stage instead of the scene which
caused my checkerboard to seem larger than the window it was in. That was the only part of the project that really challenged me.

#### 2. How well did you understand the programming concepts and foundational knowledge needed to complete the challenge?

As far as programming concepts, I felt comfortable writing lambda expressions and was able to implement that to listen for changes in the
height and width of the window. The project demonstrated in class previous to this assignment, the random grid project, introduced me
to many of the foundational knowledge about JavaFX to be able to tackle this project. The area that I struggled with was understanding
the structuring of a JavaFX application in sense of containers which is what led to my confusion between the functionality of
scenes and stages.

#### 3. How well did you meet the requirements as set out in the challenge? What requirements did you not meet correctly (if any)?

As touched on in the first question, I was able to display the checkerboard, change the number of rows and columns of the checkerboard,
change the colors of the checkerboard, and resize the checkerboard to respond to the size of the window.

#### 4. How well does your solution match the posted solution? What is different?

To begin, the posted solution uses the ready method on the UI controller as opposed to the start method which is the one I chose to use.
Additionally, the lambda expressions implemented in the posted solution listened to the height and width of the scene instead of the stage
which is what my lambda expressions listened to causing an error in the size of the checkerboard. Also I changed the number of rows
and columns with seperate functions for 3, 8, 10, and 16 rows and columns respectively while they were all lumped into one switch
statement in the posted solution.

#### 5. How could you improve going forward? What don't you still understand that was required for the challenge?

I could streamline the changes in the numbers of rows and columns by consolidating them into one function. Also, as I've spoken on many
times within this piece, I should have implemented my lambda expressions to watch for updates in the scene instead of the stage.
Those are the two places I think I could have improved my project.
