Understanding Logs & Debugging Tools for QA

Overview  
This task is about learning how to use logs and debugging tools to investigate issues that aren’t easy to reproduce just by using the app. Logs help me see what’s happening behind the scenes.

Research & Learn

What are logs, and how do they help with debugging?  
Logs are records of what the app is doing in the background.  
They show errors, warnings, API failures, and important events.  
They help me understand why something went wrong even if I didn’t see the issue happen directly.

How can you capture logs from a web app (browser DevTools)?  
I can open DevTools → Console to see JavaScript errors and warnings.  
In the Network tab, I can see API requests, responses, and failures.  
I can right-click and save network logs if needed.

How can you capture logs from a mobile app (Android/iOS debugging tools)?  
On Android, I can use Logcat from Android Studio or ADB commands to capture live logs.  
On iOS, I can use Xcode’s device logs or Safari’s Web Inspector for web views.  
These tools help capture crashes, errors, and background events.

What are some common error messages and log patterns testers should recognize?  
Some common ones include:  
- 404 or 500 (API failure)  
- “Undefined” or “Null” errors in JavaScript  
- Permission denied  
- Network timeout  
- Crashes with stack traces  
Recognizing these helps me explain the issue clearly.

How do network requests in browser DevTools help diagnose API failures?  
The Network tab shows me the request URL, status code, response data, and error messages.  
If an API fails, I can see whether the backend or frontend is responsible.  
This helps developers identify the issue faster.

Reflection

If Focus Bear crashes on a user’s device but not on yours, how would you use logs to investigate?  
I would ask for crash logs or screenshots from the user.  
Then I would test on similar devices or OS versions while monitoring my own logs (Logcat/Xcode).  
Comparing both logs helps me find patterns or missing details that caused the crash.

What are some useful log messages that should be included when reporting a bug?  
I include:  
- error messages  
- stack traces  
- API response codes  
- timestamps  
- device or browser info  
These details help developers trace the exact point of failure.

If an API call returns an unexpected response, what steps would you take to analyze the issue?  
I would:  
1. Check the Network tab to see the request and response.  
2. Look at the status code (200, 400, 500, etc.).  
3. Compare expected vs actual data.  
4. Try the same request again to see if it’s consistent.  
5. Report the findings with screenshots or saved network logs.  
This helps developers know whether the issue is on the backend or frontend.

