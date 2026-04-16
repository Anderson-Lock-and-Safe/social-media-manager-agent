# Social Media Manager Agent

Anderson Lock & Safe Social Media Manager — executes social media posts from content briefs.

## Subagents

| Subagent | Model | Role |
|----------|-------|------|
| `sm-planner` | Opus | Analyzes assets, synthesizes brief + brand guidelines into caption strategy |
| `sm-creator` | Sonnet | Writes captions, creates Buffer drafts |
| `sm-executor` | Haiku | ClickUp subtasks, status updates, Buffer promotions/deletions |

## Dependencies

Clones [anderson-marketing-shared](https://github.com/gpoole55/anderson-marketing-shared) at `/tmp/shared` for tools, workflows, and brand guidelines.

## Trigger

Routine fires when tasks are assigned to Social Media Manager (user ID: 94492103) in ClickUp.
