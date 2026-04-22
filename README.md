# CS_360_Artifact

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The app I developed is a weight tracking tool designed to help users reach their target weight or maintain a healthy lifestyle, in an intuitive way. It addresses the needs of people who want to lose weight for health or fitness, those trying to gain weight for a specific body goal, and those who just want to stay at their current weight. The main requirements included a secure database to store user accounts, an easy way to input daily weight and goals, and a notification system to alert users when they reach their milestones.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

To support these user needs, I created five main screens including a login/sign-up screen, a main dashboard, an add daily weight screen, a screen to update goal weights and a screen to enable SMS notifications. The UI design kept users in mind by using a clean grid layout on the main screen to show progress clearly and by ensuring buttons were easy to find. I followed Android design guidelines for spacing and alignment to make the app intuitive. The designs were successful because they allow users to log their information quickly and navigate the app without confusion.


# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My approach to coding was based on taking small and manageable steps. I started by researching similar apps and creating wireframes to visualize the flow before writing any code. I used strategies like the DRY principle to make sure I did not repeat myself and created reusable modules for common functions. I also focused on writing clean code with comments in plain English so the logic is easy to understand. These strategies can be applied to future projects to ensure the code remains organized and easy to maintain as it grows.


# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I made sure my code was functional by testing each little feature as I built it using the Android emulator and log statements. At the very end, I tested the whole app logic together at least three times to be certain everything was working perfectly. I feel this process is so important because testing as you go helps you catch issues early. If I had waited until the end, finding where an error started would have been a much harder challenge. This steady testing revealed small issues in my chunks of code that I was able to fix before they became bigger problems.


# Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

During the development process, I had to innovate when I realized my initial plan for the SMS notification system needed to change. I originally put the functionality for asking for SMS permissions in my main java file, but I later found out that a separate SMS screen was actually needed to enable that feature properly. Keeping it in the main screen was making things unnecessarily complicated, so I had to change my files and structure the code so the permission is only prompted for within that specific SMS screen. So that was definitely something I had to innovate on to make the app work better!

# In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I feel I was particularly successful in the UI design of the app because I truly enjoy the creative side of designing. I put a lot of time and heart into making sure each screen was thoughtful and easy for a user to look at. I also feel like I did well on how I wrote my code. I tried my best to keep it clean and consistent across all files by using plain English comments to explain the logic simply. I believe this focus on both the look of the app and the neatness of the code is something that might show my growth and skills.
