---
readingTime:
  minutes: 1.644
  words: 411
fkglResult: 8.55
---

# 03.1 Using Auto Mode in GitHub Copilot

Let's dive into how you can enable and make the most of **Auto mode** in GitHub Copilot to write code faster and more efficiently.

## Enabling Auto Mode in GitHub Copilot

1. Open your code editor (e.g., VS Code) where GitHub Copilot is installed.
2. Go to the **Extensions** panel and find **GitHub Copilot**.
3. Click on the settings (gear icon) for the extension.
4. Toggle **Enable Auto Suggestions** to **ON**.

Once enabled, Copilot will start providing continuous, context-aware code suggestions as you type.

## How to Use Auto Mode Efficiently

- **Start with a clear function signature or comment:** Begin typing a concise function header or a comment describing what you want. For example:

  ```js
  // Function to fetch user data from API
  function fetchUserData(userId) {
    
  }
  ```

- **Watch Copilot generate suggestions inside the function body automatically.**
- **Accept suggestions quickly:** Press the **Tab** key to accept a suggestion or **Ctrl+Space** to view alternatives.
- **Provide just enough context:** Avoid overly verbose comments or redundant code. For example, use variable names like `apiEndpoint` instead of full URLs if they are defined elsewhere in your project.
- **Edit prompts incrementally:** If a suggestion isn't quite right, tweak your prompt slightly instead of rejecting and rewriting large blocks. This helps reduce token consumption.

## Practical Tip

Try creating a simple React component by typing:

```js
function UserProfile() {

}
```

Copilot will suggest JSX code based on your project imports and state variables. Accept and refine these suggestions to build your component efficiently.

## Summary

Using **Auto mode** in GitHub Copilot helps you:

- Write code faster with proactive suggestions
- Save tokens by minimizing manual input
- Maintain clean and concise code context
- Improve your coding workflow with less effort

---

### Ready to practice? Try the exercise below!

```code_challenge_proposal
In this exercise, you will practice using Auto mode in GitHub Copilot by creating a simple React component named `UserProfile`. The main file will be `app.js`.

Instructions:
- Start by typing the function declaration `function UserProfile() {}`.
- Use GitHub Copilot's Auto mode to generate the JSX inside the component.
- The component should display a user's name and email, using props or hardcoded values.
- Focus on accepting suggestions quickly and refining prompts incrementally to maintain token efficiency.

This exercise will help you get hands-on experience with Auto mode and understand how to leverage it for efficient code generation.
```
