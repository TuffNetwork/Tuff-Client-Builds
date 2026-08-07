# Tuff Contributing Guidelines

These guidelines lay out general rules when interacting with Tuff repositories. There are general rules for all contributions below:

## General Contribution Rules

- Stay on topic in any threads.
  - You can always make a new issue/discussion.
- Do not share your or others' personal information.

## Issue Rules

General Contribution Rules above still apply. Specific rules for each template are found below.

- Always give issues precise, but concise titles.
  - Incorrect example: "Issue with *x feature*"
  - Correct example: "*x feature* not loading when *x*"
- Always check if the issue has been made previously, check both open and closed issues.
  - Feel free to leave a comment or reaction on issues, but stay on topic.
- Read the entire issue template, agree to required agreements, and double check all information you entered for missing info, typos, etc.
- Respond to any questions from maintainers and testers (labeled with `Member`). This makes it easier for developers to test and make updates.

### Feature Request

- Provide a brief description of what you want added/changed.
- If this feature exists elsewhere, include links and/or screenshots

### Bug Report

- Provide a brief description of the bug.
- Provide system details, server/client versions, other plugins, etc; anything that could be relevant to this bug.
- Provide exact reproduction steps
  - Incorrect example:
      1. Join the server
      2. Observe
  - Correct example:
      1. Install *x*, *x*, and *x* on *x server version* (with *x proxy*)
      2. Enabled *x setting* and restart
      3. Join the server with *x client version*
      4. Observe *x issue* when *x*

## Pull Requests Rules

- Give your PR a precise, but concise title.
  - Incorrect example: "Optimize"
  - Correct example: "Optimize *x feature* during *x case*"
- Check other PRs for duplicate changes.
- Avoid making multiple, unrelated changes in one PR.
- Avoid including unnecessary files in your PR; update `.gitignore` when appropriate.
- Avoid making a PR from your fork's `main` branch to prevent build files from being included in your PR. You can merge your PR branch to your `main` branch to test the build.
- Add tests when adding/changing sensitive code.
- Always respond to maintainers and resolve change requests from both bots and maintainers (including Nitpick Comments unless there is a good reason not to).
- Follow code standards and formatting. Don't hesitate to ask maintainers.
