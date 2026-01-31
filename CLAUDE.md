No implementation plans were found. The `/execute` command requires a plan file path to execute.

**Error: Plan Not Found**

```
{
  "command": "execute",
  "phase": "context_analysis",
  "error_type": "plan_not_found",
  "expected": "Valid plan file in docs/plans/",
  "found": "No docs/plans/ directory exists in this repository",
  "mitigation": "Create a plan first using /plan command or specify a valid plan path",
  "requires_user_input": true
}
```

**To use the execute command, you need to:**

1. **Create a plan first** - Use the `/plan` command to generate an implementation plan from a ticket or requirements
2. **Or specify a plan path** - Run `/execute docs/plans/your-plan-name.md` with the path to an existing plan file

Would you like me to:
- Help you create a new implementation plan using `/plan`?
- Show you how to structure a plan file manually?
