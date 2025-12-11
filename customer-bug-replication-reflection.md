Replicating Bugs Reported by Customers

Overview  
This task is about learning how to reproduce bugs reported by customers. These issues often happen in real-world situations that are hard for QA to replicate, so I need to look for clues, ask questions, and sometimes request more logging.

Research & Learn

What steps should QA take when a customer reports a bug that can’t be easily reproduced?  
First, I try to follow the same steps the customer mentioned.  
If it doesn’t reproduce, I test on different devices, browsers, networks, and accounts.  
I also check logs, timestamps, and any details shared by support.  
If needed, I try to recreate the environment as closely as possible.

What information should QA request from customer support to help diagnose an issue?  
I would ask for:  
- screenshots or screen recordings  
- device or browser info  
- app version  
- exact steps the customer followed  
- when the issue happened  
- any error messages they saw  
This information helps narrow down the cause.

How can logs, screenshots, and error messages help with bug reproduction?  
Screenshots show what the customer saw.  
Error messages help identify where the issue is coming from.  
Logs are the most useful because they give technical details developers can check.  
Together, these make reproduction much easier.

When should QA recommend adding more logging to capture hard-to-reproduce issues?  
If the bug is happening for users but not for QA or developers, then more logging is needed.  
I suggest adding logs when there is not enough information to explain what happened at the time of the error.

How do other teams handle "Cannot Reproduce" customer bugs effectively?  
Teams usually keep the issue open but mark it as “Needs more info.”  
Support may ask customers for more details.  
QA and developers monitor logs or add more logging until enough data appears to reproduce it.

Reflection

If a customer reports a crash but you can’t reproduce it, what are your next steps?  
I would check crash logs, ask for a screen recording, and collect device/app details.  
Then I try different conditions like low battery, slow network, background apps, or long usage.  
I also check if the crash happened on a specific device model.

When should you ask developers to add more logging, and what kind of logs would help?  
I ask for more logging when the current logs don’t explain the issue or when the crash only happens for some users.  
Useful logs include error stacks, API responses, device state, and timestamps.

What are some common patterns in bugs that only occur for some users but not others?  
Some patterns I’ve seen include:  
- device-specific behaviour  
- old app versions  
- poor network conditions  
- corrupted local data  
- user settings or permissions  
These differences can explain why only some users face the problem.

