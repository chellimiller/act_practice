# ACT Practice Site

This is a project that I'm designing for my little brother. I may not finish in time for it to be helpful to him, but I figure it's worth a shot.

## Planning

This project will be done in several phases. Currently the project is in the first phase. As time goes on, the plans will become more in depth.

### PHASE I: Client-Side Code

The first phase of this project will be functional client-side code. There will be minimal focus on appearance. By the end of this phase, I would like to have the following done:
 - Questions pulled from array and populate form
 - Questions associated to unique id's that are not related to their order in the array
 - Upon submission, answers are marked correct/incorrect and the radio buttons are disabled
 - Grade is calculated as a percentage, fraction, and potentially a ACT score estimate
 - Test is timed with timer up in the corner
 - Image urls are able to be included (if there is an associated image)

I also may decide to add pages/tabs to make answering questions more convenient.

### PHASE II: Database Connection

Eventually, I would like to pull the possible questions from a MongoDB or MySQL database. This will likely involve NodeJS backend code. Ideally, I would like to use NodeJS and MongoDB for a learning experience. To begin, I may use PHP and MySQL since I'm familiar handling forms with them. At this point, the focus will be placed on being able to provide the student with a wide variety of tests and track their score over time.

I'm not sure exactly what requirements or ideas I will have at this stage. However, I do have a few goals:
 - Randomized questions to generate unique tests
 - Questions have a "type" attribute. This could later help determine areas where the student is weak. It would also help ensure that the tests provide a variety of different types of questions. It would also allow a later addition of a link like "get help with this type of problem"
 - Student's score is tracked and they can see how they improve over time
 - Reports generated for parents/student/instructor to assess progress
 
 ### PHASE III: UX Design and Improvements
 
 The current user experience is silly and basic. Eventually I would like the webpage to have a modern, mobile-friendly design. At this point, I may consider using a framework like ionic to make a mobile version of this so the student is able to use the app on their phone.
 
 Another idea that I'm considering is making the user experience to mimic an ACT test. This would include having a "scantron" page or tab where the student answers the questions. It would also include hiding the clock and hovering over to see how much time is left.
 
## Progress

This project is currently in Phase I.

Completed:
 - Code populates a form with questions stored in an array
 - Code checks if answers are right/wrong
 - Timer is shown in upper-right corner
 - Form is submitted once timer reaches 0
 - Submit button and radio buttons are disabled upon submission

Currently, the ID for the questions are based on their positions within the array. I would like to change this. Other things that need to be changed:

 - Include the option for images (if applicable)
 - Associate questions to unique IDs
 - Change the timer format (currently in seconds)
 - Possible change: grab test from JSON file instead of array
 
 After these changes are complete, Phase II will begin. I will likely start with PHP code on the backend and a MySQL database. Eventually I would like to switch to NodeJS code and possibly MongoDB.
