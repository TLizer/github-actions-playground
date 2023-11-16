This is template from github-actions-playground

# Description
JIRA issue: <Insert link here>
<Add description of changes in this PR that gives additional context to reviewers.>

# How to Test
<Add testing steps needed to verify changes>

# Considerations (if any)
- Does it require any major changes in the consumer
- Do we need Migration. If so:
    - Type of Migration (RESYNC / FORCELOGOUT)
    - Why this migration is required?
- Is there any speciffic fallback from those changes (revert / feature flag / other)

# Checklist
- [ ] Changes meets functional criteria of task
- [ ] Changes meets visual criteria of task [developer self review]
- [ ] New and updated code is logically covered with unit tests and does not violate other product requirements
- [ ] New and updated code do not triggers linter warnings or errors (Rules)
- [ ] Changes are made according to Organization Style guide and other Coding Standards ([link](https://github.com/Adaptavant/Anywhere-IOS-Container/blob/main/Documentation/Code%20Standard.md#ios-code-standard))
- [ ] Required documentation is added and/or updated (Inline or README)
- [ ] New and updated strings are using localized keys (are not hardcoded)
- [ ] New extension/helper/code is not duplicated
- [ ] Required Sentry Logs (or) Breadcrumbs are added
- [ ] Did I remove all unnecessary logging and print statements
- [ ] Thread-Safety is considered when utilizing Shared resources