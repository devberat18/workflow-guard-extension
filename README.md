# Workflow Guard Extension

Workflow Guard is a Chrome extension that helps developers prevent repetitive workflow mistakes by showing context-aware checklists on specific web applications.

The first target use case is Azure DevOps Pull Request pages, where the extension can remind or block the user until required checklist items are completed.

## Initial Goal

Build a local-first Chrome Extension MVP that:

- Detects matching URLs
- Shows a checklist overlay
- Blocks or reminds the user based on rule configuration
- Stores rules and checklist state locally
- Works without backend, login, or cloud sync
