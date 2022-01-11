# GitHub Conventional Commits:

The way to write a commit that is meaningful and readable by machines and humans.

## Commits structure should be like:

```
<type>[optional scope]: <description>

```

## Types:

> **_Most used_**:

- **`feat`**: A new feature is added for the user, not for build script.
- **`fix`**: A bug fix(or error) for the user, not for build script.
- **`docs`**: Documentation only changes(README.md,etc.)
- **`style`**: Changes that do not affect the meaning of the code (white-space, formatting, missing, etc...).

> **_Others_**:

- **`refactor`**: A code change that neither fixes a bug or adds a feature
- **`perf`**: A code change that improves performance
- **`test`**: Adding missing tests
- **`chore`**: Changes to the build process or auxiliary tools and libraries such as documentation generation
- **`revert`**: Revert to a commit
- **`WIP`**: Work in progress
- **`automation`**: Changes that are automated

#### Examples:

- **feat commit without scope:**

```
feat: add navigation bar to the top of the page.
```

- **feat commit with scope:**

```
feat(lang): add arabic language

```

**_*References:*_**

- [GitHub Conventional Commits](https://www.conventionalcommits.org/)
