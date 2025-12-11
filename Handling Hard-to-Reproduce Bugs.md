Handling Hard-to-Reproduce Bugs

Overview  
This task is about learning how to deal with bugs that don’t happen every time. These bugs can be tricky because they depend on timing, device type, or specific conditions. My goal is to learn how to collect enough information so developers can figure out what's going on.

Research & Learn

What are common causes of intermittent bugs in software?  
From what I’ve seen, intermittent bugs are usually caused by timing issues, slow networks, memory problems, race conditions, or device-specific differences. Sometimes they only appear after long usage or when multiple actions happen at once.

What tools can help capture debug logs, network requests, and app crashes?  
I can use Chrome DevTools, Logcat (for Android), Xcode device logs (for iOS), and tools like Sentry or Firebase Crashlytics if they are integrated. Screen recordings are also helpful to show the moment the bug appears.

What strategies can testers use to make flaky bugs more reproducible?  
Some things I try include repeating the steps slowly and then quickly, changing the order of steps, testing on another device, testing on different network speeds, and letting the app run for a while before trying again.  
Sometimes I also try to isolate one part of the flow to see which action triggers the bug.

How do teams handle "Cannot Reproduce" issues?  
Usually, if the bug can’t be reproduced, the developer asks for more details.  
The issue may be put on hold until more evidence appears.  
My job is to give as much information as possible so they have something to investigate.

Reflection

How would you report a bug that only happens occasionally?  
I would mention how often it happens (for example, 1 out of 5 tries), describe the conditions when it happened, add screenshots or screen recordings if possible, and include logs.  
I would also mention the device and network I was using.

If a developer marks a bug as "Not reproducible", what’s your next step?  
I would try to reproduce it again on my side, this time paying closer attention to small details.  
I might switch devices, try different networks, or change the timing of actions.  
If I can reproduce it again, I update the issue with clearer steps or new evidence.

What tools or techniques can help capture extra details for unpredictable bugs?  
I can use logs (Logcat/Xcode), the Network tab, screen recordings, screenshots, and console messages.  
Sometimes slowing the app down or running it on a slower network helps reveal patterns.  
I also try to record the exact sequence of actions so I don’t miss anything.

