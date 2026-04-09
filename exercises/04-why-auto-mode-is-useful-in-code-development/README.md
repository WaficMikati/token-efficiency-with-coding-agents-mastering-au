---
readingTime:
  minutes: 2.052
  words: 513
fkglResult: 10.32
---

# 3.3 Why Auto Mode is useful in code development

Coding efficiently is not just about writing code fast; it's about writing smart. **Auto mode** in tools like GitHub Copilot transforms your coding experience by offering real-time, context-aware suggestions that help you write better code with less effort and fewer tokens.

## Enabling Auto Mode in GitHub Copilot

To start using Auto mode in GitHub Copilot:

1. Open your IDE (such as Visual Studio Code).
2. Navigate to **Extensions > GitHub Copilot > Settings**.
3. Toggle **Auto Suggest** to **ON**.

Once enabled, Copilot will provide inline code suggestions as you type, reducing the need for manual prompts and repetitive typing.

## How Auto Mode Enhances Your Coding Workflow

- **Continuous Suggestions:** As you type, Copilot predicts and suggests the next parts of your code, from simple lines to complex functions.
- **Context Awareness:** Suggestions are based on your current file, project context, and comments, making them relevant and precise.
- **Token Efficiency:** By accepting well-targeted suggestions, you minimize manual input and token consumption, saving time and cost.

### Example: Writing a React Component

Start typing:

```javascript
function UserProfile() {
```

GitHub Copilot may suggest the entire component body, including state hooks and JSX elements. You can accept suggestions with the `Tab` or `Right Arrow` keys.

```javascript
function UserProfile() {
  const [user, setUser] = React.useState(null);

  React.useEffect(() => {
    fetchUserData().then(setUser);
  }, []);

  if (!user) return <div>Loading...</div>;

  return <div>{user.name}</div>;
}
```

## Best Practices to Maximize Auto Mode Benefits

- **Write Clear Comments:** Use descriptive comments before functions or blocks to guide Copilot's suggestions.
- **Type Partial Snippets:** Instead of full prompts, start with meaningful code fragments to trigger relevant completions.
- **Review Suggestions:** Always check generated code for correctness and adapt as needed.

## Visualizing Auto Mode in Action

![Conceptual illustration showing a developer typing code on the left, GitHub Copilot's Auto mode generating inline suggestions in the middle, and the developer accepting or modifying these suggestions on the right. The flow is color-coded to differentiate user input, automated suggestions, and decision points, with annotations explaining how Auto mode streamlines coding and optimizes token usage. The illustration uses friendly colors and simple shapes to clarify the interaction process.](./.learn/assets/copilot-auto-mode-concept.png)

## Summary

Using **Auto mode** in GitHub Copilot helps you:

- Write code faster with continuous, context-aware suggestions
- Reduce manual typing and token consumption
- Leverage comments and partial code to guide suggestions
- Improve code quality and development speed

---

### Reflect on Your Learning

What are the key advantages of using Auto mode in GitHub Copilot, and how can it improve your coding efficiency? Write your answer below.

```question eval="The user should explain benefits such as faster coding, context-aware suggestions, token efficiency, and improved workflow."
CORRECT: Auto mode provides continuous, relevant code suggestions that speed up coding and reduce manual input.
CORRECT: It helps save tokens by minimizing repetitive typing and prompts.
CORRECT: Using comments and partial code guides better suggestions, improving code quality.
INCORRECT: Auto mode writes all code automatically without user input.
INCORRECT: It replaces the need to understand coding concepts.
```
