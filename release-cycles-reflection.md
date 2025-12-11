Understanding Release Cycles & Version Control

Overview  
This task is about learning how QA fits into the software release cycle and how Git version control affects testing. Knowing this helps me plan my testing and understand where issues might come from.

Research & Learn

What are the typical stages in a software release cycle (development, testing, staging, production)?  
From what I’ve learned, the usual flow is:  
- Development: new features and changes are created.  
- Testing: QA checks the features to make sure they work.  
- Staging: a pre-production environment for final checks.  
- Production: the version released to real users.  
QA plays a role mainly in testing and staging.

How does QA work differ between a feature release and a hotfix?  
For a feature release, I test new functionality, explore edge cases, and check how it interacts with existing features.  
For a hotfix, I focus only on the specific issue that needs to be fixed and quickly verify that it works without breaking other things.

What is version control (Git), and how does it impact testing?  
Git keeps track of changes to the code and helps developers work together.  
For testing, it helps me understand which version of the app I’m testing and which changes might be causing issues.

What are Git branches, and why do testers need to be aware of them?  
Branches are separate versions of the code for different features or fixes.  
As a tester, I need to know which branch a feature is on, because bugs might exist only in one branch and not another.  
It also helps me confirm whether I’m testing the latest updates.

How does QA handle rollbacks if a release causes major issues?  
If a release breaks something important, the team might rollback to a previous stable version.  
As QA, I would re-test the older version to make sure everything is working again and report any remaining issues.

Reflection

How would you adjust your testing strategy for a major feature release vs. a small bug fix?  
For a major feature release, I would explore the new feature deeply, test user flows, edge cases, and interactions with other parts of the app.  
For a small bug fix, I would focus on the exact area affected and do a quick regression check around it.

If a developer says, “This bug only happens on an older branch,” how would you handle it?  
I would switch to that older branch or build version and try to reproduce the issue there.  
If it happens, I document it clearly. If it doesn’t, I compare differences between branches to see what changed.

Why is it important for testers to know which version of the app they are testing?  
Because different versions have different code.  
If I don’t know the version, my testing might be inaccurate or confusing.  
It also helps developers understand where the bug exists and which build needs fixing.

