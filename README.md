# sample-workflow-actions

```
Create two workflows:
```

| Lint, Test & Deploy on push |  Output Event Details on "issues" |
| --------------------------- | --------------------------------: |
| `Run the "lint", "test" &   |      `Output Event Details in the |
| "build" scripts`            |                 shell via "echo"` |
| Use one or three            | Use the "issues" event & "github" |
| sequential jobs             |                           context |
