Exploratory Testing vs. Regression Testing

Overview  
This task is about understanding the difference between exploratory testing and regression testing. Both are important in manual QA, and knowing when to use each one helps in finding bugs and keeping the app stable.

Research & Learn

What is exploratory testing, and how does it differ from scripted testing?  
From what I’ve learned, exploratory testing is when I freely explore the app without following a fixed set of steps. I learn the feature as I test it.  
Scripted testing is more structured — I follow written test cases and check specific behaviours.  
Exploratory testing lets me think like a user, while scripted testing makes sure I don’t miss important checks.

What is regression testing, and why is it important in software development?  
Regression testing is when I re-test existing features to make sure they still work after updates or bug fixes.  
It’s important because one small code change can break something that was working before.  
This helps maintain stability in the app.

When should exploratory testing be used instead of regression testing (or vice versa)?  
I use exploratory testing when a feature is new, unclear, or needs creative thinking.  
I use regression testing when the app has just been updated or when a bug has been fixed and I need to make sure old features still work.  
Exploratory testing helps me discover unexpected behaviours, while regression ensures nothing breaks after changes.

How can exploratory testing reveal bugs that scripted tests might miss?  
When I explore without a script, I try unusual actions, different inputs, or random flows that a test case might not cover.  
Scripted tests follow a fixed path, but exploratory testing helps me find issues that happen only in rare or unexpected scenarios.

Reflection

Why is exploratory testing particularly useful for an app like Focus Bear?  
Focus Bear has features like routines, focus sessions, and onboarding flows where users behave differently.  
Exploratory testing helps me understand the app from a real user’s point of view.  
It also helps me find confusing flows or edge cases that wouldn’t appear in simple scripted tests.

What risks come with relying too much on exploratory testing vs. only doing regression testing?  
If I rely only on exploratory testing, I might miss important repeated checks because I don’t follow a structure.  
If I rely only on regression testing, I might miss new or unexpected bugs because I only test what is written.  
A balance of both is important.

How would you document and report issues found during an exploratory testing session?  
When I find something during exploratory testing, I write down the exact steps I took, even if they were not planned.  
I include what I expected to happen, what actually happened, screenshots or videos, and the device or browser I used.  
I try to clearly explain how I reached the issue so developers can reproduce it easily.

