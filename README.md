# CS-360-Portfolio-Baber


- Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
    
  The app developed for this project was a weight-tracking app developed in Android Studio using Java.  The app needed users to be able to login to the app, or register for an account if not already registered.  The app then needed to allow users to enter a goal weight, and enter individual weights accompanied by the date.  These entries needed to be able to be edited or deleted as the user saw fit.  Finally, the app required a means of notifying the user when they reached their goal weight vis SMS message if the user granted the app those privileges.


- What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
    
  To achieve these goals, the app needed a login/registration activity linked to a SQL table containing user credentials.  Secondly, an activity was needed allowing the user to enter weights that would dynamically create objects in a grid layout on-screen.  Thirdly, app needed a screen asking the user for permission to send SMS messages and routines to follow if they did or didn't allow the app these privileges.  The necessary features were fairly sparse, so keeping the UI simple and coherent wasn't a challenge.  The main challenge was in using SQL tables correctly and dynamically creating grid objects.
   
   
- How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
    
  Before coding, I first consulted the list of requirements listed in the assignment materials.  By taking use-cases into account, I ensured that no unnecessary features were included that would make the assignment harder than it needed to be.  Because Android apps are broken down into activities, the development of this project lent itself more to the process of modularization than some other development projects might.  Breaking down each process into its component parts made the coding process easier and less daunting than it otherwisemight have been.  I suspect that learning how to code an Android app will come in useful in several other domains of programming.  The focus on integration between activities, for example will be useful when integration testing.
    
    
- How did you test to ensure your code was functional? Why is this process important and what did it reveal?
    
  In the end, my code was "less than functional", meaning that I was unable to create an app that did what I needed it to do.  However, I know that this question is mostly approaching the topic of QA testing.  While I noticed that Android Studio auto-creates directories for unit tests, the course itself never covered an effective unit testing strategy for mobile app development.  In lieu of this, it's important to plan for every contingency when users are given the opportunity to input information.  If a field only accepts a certain data-type as input, the developer should create responses for incorrect input.  Planning for the unexpected is always the best course of action, and will reduce the number of needless app crashes.
    
    
- Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
    
  Although my app was incomplete in the end, I was somewhat proud of the way I handled the interactions between the login/registration screen, the SQL table I generated to hold credentials, and the following weight-entry activity.  Understanding how activities will pass along data to other activities is difficult, and rather than using the weight-entry table to hold my users' goal weights, I opted to do so as part of the user credential table.  Because the goal weight wasn't likely to change very often, it made more sense to store it connected to each user's information rather than as a function of the weight history.  This was a small victory and probably how the data should have been handled, but figuring this out took a lot of uncertainty about the app's SQL design off of my plate.
    
    
- In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  By and large, this project was a failure on my part.  I've gotten used to being able to throw myself at projects like these and brute-force my way to a solution.  In this case, I should have sought help rather than deciding to just make do.  If I were to count anything as a success, it would be my UI design.  I've seen mock-ups of similar projects that I found to be pretty unappealing compared to the design I ultimately landed on.  I'm by no means a design-minded person, but I can appreciate a coherent UI when I use one, and am happy at least that I can tuck a tiny bit of design-literacy in my toolbelt.  Android Studio makes this much easier, of course, and uses an incredibly intuitive layout designer.  Either way, however, making my app look professional (or at least passable) was a win for me.
