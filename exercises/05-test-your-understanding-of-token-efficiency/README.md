---
readingTime:
  minutes: 1.4
  words: 350
fkglResult: 7.8
---

# 05.0 Test Your Understanding of Token Efficiency

Let's put your knowledge to the test! This quiz covers everything from this course: **how tokens work**, **best practices for token efficiency**, and the real meaning and purpose of **Auto mode** in tools like GitHub Copilot and Cursor.

Select the correct answer for each question.

1. What is the primary benefit of managing token usage effectively when working with coding agents?

   - [ ] It allows you to write code without any errors.
   - [x] It helps reduce costs and improves coding efficiency.
   - [ ] It guarantees the fastest code execution possible.
   - [ ] It enables the coding agent to write code without any user input.

2. What does **Auto mode** in Cursor actually do?

   - [ ] It enables ghost-text inline suggestions as you type in the editor.
   - [ ] It disables suggestions to save tokens.
   - [x] It automatically routes each request to the most appropriate AI model based on task complexity.
   - [ ] It only works with the most powerful model available.

3. Why might using the most powerful model for every task NOT be the best choice for token efficiency?

   - [ ] Because powerful models are slower to respond.
   - [x] Because they consume more tokens per request and may increase costs unnecessarily for simple tasks.
   - [ ] Because they do not support Auto mode.
   - [ ] Because they produce less accurate code suggestions.

4. Which of the following tasks is the best candidate for a **lightweight model**?

   - [x] Asking "What does this function return?" about a short code snippet.
   - [ ] Refactoring an authentication module across five files with edge case handling.
   - [ ] Designing a database schema for a multi-tenant SaaS application.
   - [ ] Debugging a complex race condition in an async system.

5. What is the most important reason to write **clear, specific prompts** when using coding agents?

   - [ ] To make the agent use a more powerful model every time.
   - [ ] To increase the number of tokens used and get longer responses.
   - [x] To help the agent understand the task precisely, reducing unnecessary back-and-forth and wasted tokens.
   - [ ] To avoid triggering Auto mode accidentally.

6. When should you manually **override Auto mode** and select a specific model yourself?

   - [ ] Every time you start a new Cursor session.
   - [ ] Whenever you're writing JavaScript instead of Python.
   - [x] When you know a task is complex and want to guarantee it's handled by the most capable model.
   - [ ] When you want to disable inline code suggestions.

Good luck — and remember: smarter token use means faster, cheaper, and better coding!
