# Task Manager

## Project Purpose

This project is a task manager for organising daily work.
Users can create, edit, complete, and delete tasks.
Tasks can be viewed in one place so users can easily track their progress.

## Coding Conventions

JavaScript will be used for the application logic.
React components will be used to build the user interface.
Use one component per file and avoid putting unrelated logic in the same file.
Use `const` by default and only use `let` when a value needs to change.

### Naming

Use `camelCase` for variables and functions, such as `taskName` and `createTask`.
Use `PascalCase` for React components, such as `TaskCard` and `TaskList`.
Use descriptive names that explain what the variable, function, or component does.
Boolean variables should start with names such as `is`, `has`, or `should`.

### General Rules

Keep functions focused on one task and avoid functions longer than necessary.
Do not duplicate the same code when a reusable function or component can be created.
Keep React components focused on displaying or managing one main part of the application.
Do not change unrelated files when adding or fixing a feature.

## Project Structure

`src/components/` contains reusable React components such as `TaskCard`.
`src/pages/` contains complete application screens such as the task dashboard.
`src/services/` contains API and external service code.
`src/utils/` contains reusable helper functions.
Test files should be stored beside the code they test.

## Testing

Use **Jest** and **React Testing Library** for application tests.
Test files should use the `.test.js` naming format, such as `TaskCard.test.js`.
Every new feature should include tests for its main behaviour and common errors.
Bug fixes should include a test that reproduces the original problem.
All tests must pass before a feature is considered complete.


