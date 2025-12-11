How to Test Accessibility

Overview  
This task is about learning how to check if Focus Bear is accessible for users with different disabilities. Since many users have ADHD, Autism, or visual/motor challenges, it’s important that the app is easy to navigate for everyone.

Research & Learn

What is WCAG (Web Content Accessibility Guidelines), and what are its key principles?  
From what I learned, WCAG provides rules that help apps and websites be accessible.  
The main principles are:  
- Perceivable (users can see or hear the content)  
- Operable (users can navigate and use it)  
- Understandable (content is clear and easy to follow)  
- Robust (works well with assistive tools like screen readers)

How do screen readers (e.g., NVDA, VoiceOver, TalkBack) work, and how can QA test with them?  
Screen readers read aloud what is on the screen and help users navigate with gestures or keyboard shortcuts.  
To test with them, I would turn on VoiceOver or TalkBack, try moving through the app, and listen to whether buttons, labels, and actions are announced correctly.

What are some common accessibility issues in apps and websites?  
Common issues include:  
- missing alt text or labels  
- low color contrast  
- buttons that are too small  
- poor keyboard navigation  
- elements not announced properly by screen readers  
- animations that are too fast or distracting  

How can you test keyboard navigation and focus management?  
I use only the keyboard (Tab, Shift+Tab, Enter, Space) and check if I can move through the app without a mouse.  
I also check if the focus highlight is visible and if it moves in a logical order.

What tools can help automate basic accessibility checks?  
Some helpful tools include:  
- Lighthouse  
- Axe DevTools  
- WAVE  
These tools can quickly find basic accessibility problems like color contrast or missing labels.

Reflection

How would you test if Focus Bear is usable with a screen reader?  
I would turn on a screen reader and try to complete normal tasks like starting a focus session or creating a routine.  
I would listen to how buttons and text are read, check if navigation is smooth, and make sure nothing is skipped or confusing.

What accessibility barriers could affect someone with ADHD or Autism using the app?  
Fast animations, cluttered layouts, unclear instructions, or too many steps can be overwhelming.  
Difficulty focusing or understanding the flow may also be an issue.  
I would check if the app feels simple, predictable, and calm to use.

If a developer says "this doesn't impact most users", how would you advocate for fixing an accessibility issue?  
I would explain that accessibility issues still impact real users and that even a small barrier can make the app unusable for someone.  
I would remind them that accessibility improves the experience for everyone, not just people with disabilities.  
I would keep the conversation respectful and focused on user experience.

