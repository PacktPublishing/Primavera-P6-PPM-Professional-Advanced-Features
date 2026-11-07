# Workspace Guidelines

## GitHub Synchronization

- After completing any workspace change, stage and commit the work, then push it to the current GitHub remote branch without waiting for a separate request.
- Include the relevant customization, source, schedule, layout, and documentation files affected by the work.
- Preserve unrelated local changes. Do not commit, reset, discard, or overwrite files you did not create for the current task.
- Use a concise imperative commit message that describes the completed work, for example: `Update Primavera schedule layouts`.
- Verify the repository status and push result before reporting completion.
- Never commit secrets, credentials, tokens, personal data, or generated backup artifacts unless they were explicitly requested and appropriate for the repository.
- If Git or a GitHub remote is unavailable, install Git or add the remote as appropriate; do not silently leave completed work local-only.
- If the push is rejected because the remote has new commits, fetch and integrate those commits safely, then retry the push without discarding either side's work.
