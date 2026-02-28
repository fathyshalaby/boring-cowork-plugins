# User-Facing Error Messages & Microcopy
Write effective error messages, tooltips, and UI text:

### Error Message Formula
```
What happened + Why it happened + What to do about it
```

**Bad**: "Error 500: Internal Server Error"
**Good**: "We couldn't save your changes because our server is temporarily unavailable. Please try again in a few minutes. If this continues, contact support."

### Error Message Principles
1. **Be specific**: Tell the user exactly what went wrong.
2. **Be human**: Use plain language, not error codes alone.
3. **Be actionable**: Tell the user what to do next.
4. **Take responsibility**: "We couldn't process" not "You failed to provide".
5. **Avoid jargon**: "Something went wrong" > "NullPointerException".

### Microcopy Best Practices
| Element | Guideline | Example |
|---------|-----------|--------|
| Button text | Use a verb that describes the action | "Save changes" not "OK" |
| Form labels | Clear, concise | "Email address" not "Enter your electronic mail" |
| Placeholder text | Example format, not instructions | "name@example.com" not "Enter your email" |
| Tooltips | Explain WHY, not just WHAT | "API keys are used to authenticate..." |
| Empty states | Guide the user to take action | "No projects yet. Create your first project →" |
| Confirmation dialogs | Specific about consequences | "Delete 3 files? This can't be undone." |
