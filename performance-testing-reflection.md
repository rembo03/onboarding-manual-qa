Testing Performance & Responsiveness

Overview  
This task is about learning how to check whether Focus Bear performs well under different conditions. Even if all features work, slow or laggy performance can ruin the user experience.

Research & Learn

What are the key factors that impact app performance (CPU, memory, network, database queries, etc.)?  
From what I’ve learned, app performance depends on CPU usage, memory consumption, network speed, database queries, and how efficiently the app handles background tasks.  
If any of these are overloaded, the app can slow down, freeze, or crash.

How can QA testers measure app speed and responsiveness?  
I measure responsiveness by checking how quickly screens load, whether buttons react instantly, and whether animations run smoothly.  
Tools like DevTools, profiling tools, and simple observation (e.g., stopwatch timing) also help me evaluate speed.

What tools can be used for basic performance testing (e.g., Chrome DevTools, Lighthouse, mobile profiling tools)?  
Some useful tools include Chrome DevTools (Performance tab), Lighthouse audits, Android Studio Profiler, and Xcode Instruments.  
These tools show memory usage, CPU spikes, network activity, and rendering issues.

What common performance issues appear in web apps vs. mobile apps?  
Web apps often struggle with slow rendering, large scripts, and slow API responses.  
Mobile apps usually face memory issues, battery drain, frame drops, or slow start-up times.

How can QA test app behavior under high load or low resources (low RAM, slow CPU, unstable network)?  
I can simulate low-end conditions by using throttling, switching to older devices, filling the device storage, or running many apps in the background.  
For network instability, I use throttling tools or switch between WiFi and mobile data.

Reflection

How would you test Focus Bear’s performance on an older device or a slow internet connection?  
I would test on a device with low RAM or an older processor to see if the app becomes slow or crashes.  
Then I’d use slow network modes (like “Slow 3G” in DevTools) to check if the app handles delays properly and shows clear messages.

If a user reports that the app feels slow, what steps would you take to investigate?  
I would first try to reproduce the issue by using the same device or environment if possible.  
Then I would check logs, monitor network requests, watch for CPU or memory spikes, and measure page load times.  
I’d also compare the slow user flow with normal behaviour to spot the difference.

What performance optimizations could help Focus Bear run smoothly on low-end devices?  
Some ideas include reducing heavy animations, optimizing large images, minimizing background processes, caching data efficiently, and making API calls lighter.  
Keeping screens simple and reducing unnecessary UI elements can also help improve performance.

