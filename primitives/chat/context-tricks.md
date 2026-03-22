## Chat Context Tricks

**Category:** chat  
**Description:** Tips for giving Copilot Chat the right context to produce better answers.

### Use `#file` to pin a specific file
```
#file:src/auth/login.ts How does the login flow work?
```

### Use `@workspace` for broad questions
```
@workspace Where is the database connection configured?
```

### Use `#selection` to focus on selected code
Select a block, then open chat — Copilot automatically uses the selection as context.

### Use `/explain` and `/fix` slash commands
```
/fix the null pointer issue in this function
/explain what does this regex do
```
