Learn How to Use Browser Developer Tools

Overview
This task is about understanding the basic features of browser developer tools. These tools help with checking UI issues, seeing errors, and understanding what happens behind the scenes when a website loads.

Research & Learn

1. Main features of developer tools in Chrome and Firefox
- Elements/Inspector – lets you look at the HTML and CSS of any page and make quick changes to test things.
- Console – shows JavaScript errors and log messages. Very useful for spotting what went wrong.
- Network – shows all the API calls, their status codes, load times, and the data being sent or received.
- Sources – allows you to look at JavaScript files and set breakpoints for debugging.
- Application/Storage – shows cookies, local storage, session storage, and cached files.
- Performance – used to check how fast a page loads and where delays come from.
- Responsive Mode – helps test how the site looks on different screen sizes.

2. How to check for JavaScript errors in the Console
- Open DevTools and click the Console tab.
- Any red text indicates an error.
- You can see where the error happened (file name and line number).
- This helps understand why a button, form, or feature isn’t working.

3. How to use the Network tab to monitor API requests
- Open DevTools → Network.
- Refresh the page.
- You will see a list of all requests the browser makes.
- Check status code, response data, request headers, and load time.
- This helps confirm whether the backend is working or failing.

4. How to simulate different network conditions
- Go to Network → Throttling.
- Choose “Slow 3G”, “Fast 3G”, or “Offline”.
- Helps test performance on weak internet.

Reflection

1. How to confirm if an API call is successful
- Open the Network tab.
- Do the action that triggers the API call.
- Status 200 = successful.
- 4xx or 5xx = error.
- You can also open the response to see the returned data.

2. How DevTools helps debug UI issues that appear in one browser
- Check the Console for browser-specific errors.
- Inspect elements to see if CSS is applied differently.
- Compare behavior across Chrome and Firefox to spot differences.

3. Information from DevTools useful when reporting a bug
- Screenshot of console errors,
- API request/response info,
- Status codes,
- Response body,
- Browser version,
- Steps to reproduce,
- UI screenshots.

All of this helps developers fix the issue faster.
