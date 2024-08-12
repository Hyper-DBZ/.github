## Branch Guidelines

1. Start each branch with your chosen name tag for ease of identification.
2. End it with a slash.
3. Follow it with the issue ticket number to link it to its card.
4. End it in a hyphen.
5. Then add the issue ticket title as a description.
6. Use hyphens to separate the words of the description.
7. Use only alphanumeric lowercased characters and hyphens.

Example:

```sh
nametag/123-finisher
```

## Commit Guidelines

- Keep each commit as unitary as possible.
- Ensure each commit keeps the code functional, without breaking anything.
- Use a prefix in your commit message that describes the type of change.
- Follow it with the scope of the change.
- Provide a concise and descriptive commit message detailing the changes introduced.
- Ensure that your commit message starts with a present tense verb.
- Use only alphanumeric lowercased characters and hyphens.

### Commit Message Types

- `chore:`: Includes commits related to project maintenance tasks.
- `docs:`: Updates or adds documentation.
- `feat:`: Introduces a new feature.
- `fix:`: Addresses a bug or defect.
- `refactor:`: Restructures code without changing its external behavior.
- `style:`: Makes non-functional changes like formatting.

Example:

```sh
fix(emotional): aura issue on win pose charge
```

## Merge Request Guidelines

1. Aim to create small merge requests.
2. Review and test your own code.
3. For a single commit, the title should be the subject of the commit message.
4. For multiple commits, the title should summarise the set of commits.
5. Add the purpose of the branch in the description. What is it changing?
6. Assign it to yourself.
7. Add one or more reviewers.

**To ensure your code is up to date, please use rebase instead of merge:**

```sh
git pull --rebase origin main
```

You might have commits to pull and push. Make sure you push them after resolving any potential conflicts.

```sh
git push -f
```

This ensures the commit history is nice, clean, and easy to read.

## Code Review Process

All pull requests undergo a code review process to ensure quality, maintainability, and adherence to coding standards.

### Here's what to expect during code review

1. The team reviewer will assess your code for functionality, clarity, efficiency, and adherence to coding conventions.
2. Feedback and suggestions for improvement will be provided through comments on your pull request.
3. You'll have the opportunity to discuss feedback and make necessary changes before merging.

### Tips for a Smooth Code Review

- Focus each pull request on a single feature or bug fix.
- Write clear and concise commit messages.
- Include relevant documentation updates or tests alongside code changes.
- Respond promptly to reviewer feedback.
