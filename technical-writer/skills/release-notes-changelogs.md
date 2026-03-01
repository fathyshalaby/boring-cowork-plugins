# Release Notes & Changelogs
Write release notes that help users understand and adopt changes:

### Release Notes Structure
```
## Version X.Y.Z (YYYY-MM-DD)

### Highlights
[1-2 sentence summary of the most important changes]

### New Features
- **Feature name**: Description of what it does and why it matters.

### Improvements
- **Area**: What changed and how it benefits the user.

### Bug Fixes
- Fixed an issue where [specific behavior] occurred when [specific condition]. (#issue-number)

### Breaking Changes
- **Changed**: [what changed]. **Migration**: [what users need to do].

### Deprecations
- `old_function()` is deprecated and will be removed in vX.Y. Use `new_function()` instead.
```

### Writing Guidelines
- Lead with **user impact**, not implementation details.
- "You can now export reports as PDF" not "Added PDF export module to the reporting subsystem".
- Always document breaking changes with migration instructions.
- Link to relevant documentation for new features.
- Include issue/PR numbers for traceability.

### Changelog Formats
- **Keep a Changelog** (keepachangelog.com): Categories are Added, Changed, Deprecated, Removed, Fixed, Security.
- **Conventional Commits**: feat:, fix:, breaking:, etc. enables automated changelog generation.
- **Auto-generation**: Tools like release-please, semantic-release, or git-cliff.
