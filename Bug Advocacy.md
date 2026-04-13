🎓 QA Learning — Bug Advocacy: Reporting Bugs Effectively
Date: 13 April 2026
Tester: Badal Moreya
Resource: James Bach & Michael Bolton — Bug Advocacy talks + Focus Bear QA SOP Section 4.7
SOP Link: https://docs.google.com/document/d/1XRfau1UPmmLQWBQdo1GeKyxRwT8DLF6tO8Z6pQr-3s4/edit

📚 What I Learned
What makes a good bug report vs a bad one?
A good bug report is clear, specific, and gives the developer everything they need to reproduce the issue without asking follow-up questions. A bad bug report is vague, missing steps, or unclear about what actually went wrong.
What details must be included?

Title — specific, includes feature, platform, and build
Steps to reproduce — numbered, precise, starting from app launch
Expected result — what should happen
Actual result — what actually happened
Device info — device name, OS version, build number
Evidence — screenshot or screen recording embedded (must pass QA evidence checker)
Severity and RICE score — helps developers prioritise

How to make a bug easier to reproduce?
Write steps in the exact order followed. If the bug is inconsistent, mention the reproduction rate (e.g. 3/3). Include logs or screen recordings where possible.
Severity vs Priority:

Severity = how serious the bug is technically
Priority = how urgently it needs to be fixed
Example: a UI glitch may be low severity but high priority if it affects brand perception. A backend error may be high severity but scheduled for next sprint


🔁 Reflection
UI glitch vs critical login failure — how I'd report them differently:

UI glitch → screenshot + short description + Low severity
Login failure → detailed steps + error logs + screen recording + High severity + High priority — blocks all users

If a developer dismisses a bug as not important:
I would explain the user impact clearly — show how it affects the experience, causes confusion, or blocks a flow. I frame it in terms of real user harm rather than technical detail alone.
How screenshots, logs, and recordings improve reports:
They remove guesswork. A screenshot shows exactly what I saw. A recording shows the full flow. Logs identify the root cause. These save time for both tester and developer.

✅ Applied Today
Filed bug #4353 — Custom Habit Not Saved After Importing Habits During Onboarding [Android · Build 1.18.0 · 1003937]. Followed SOP Section 4.7 exactly — specific title, numbered steps, expected vs actual, device info, RICE score (15 — High Priority), embedded evidence. Ran through AI Prompt 2 before submitting.
