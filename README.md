# mb-backlog

My personal app for maintaining my personal backlog

## Summary

**mb-backlog** is a single user application designed for managing and maintaining a personal backlog of tasks. The application provides the user with a centralized platform to manage his tasks. This requirements specification outlines the functional and non-functional requirements for version 1.0 of the mb-backlog application.

### Key Objectives

- Provide a centralized platform for personal backlog management
- Enable easy creation of tasks
- Support flexible filtering and sorting of tasks
- Ensure intuitive user experience for personal productivity

### Scope
**In Scope:**
- Centralized platform for personal backlog management
- Easy creation and management of tasks
- Flexible filtering and sorting of tasks
- Intuitive user interface for personal productivity

**Out of Scope:**
- Authentication and authorization features
- User management and role-based access control
- Log in and registration functionality
- Multi-user collaboration and team features
- Advanced project management capabilities
- Third-party integrations and external system connections

### Target Users
- **Owner:** A single user who needs to manage tasks in a centralized location.

## Data structures

### Task
- **code**: A unique identifier for the task (string, required)
- **title**: A brief title for the task (string, required)
- **state**: The current state of the task (string, e.g., "To Do", "In Progress", "Done", required)
- **description**: A detailed description of the task (string, optional)

## Functional Requirements

| ID | Title | Description | Link |
|----|---------------|-------------|---|
| FR-001 | View tasks | User can view a list of all tasks with their required fields | [specification](specification/FR-001-view-tasks.html) |
| FR-002 | Sort tasks | User can sort tasks by a single column | [specification](specification/FR-002-sort-tasks.html) |
| FR-003 | Filter tasks | User can filter tasks by multiple columns | [specification](specification/FR-003-filter-tasks.html) |
| FR-004 | View task details | User can view task detail with all it's fields | [specification](specification/FR-004-view-task-details.html) |
| FR-005 | Create task | User can create a new task by providing all required fields and optionally some or all optional fields | [specification](specification/FR-005-create-task.html) |
| FR-006 | Edit task | User can edit all task's fields | [specification](specification/FR-006-edit-task.html) |
| FR-007 | Delete task | User can delete an existing task from the backlog | [specification](specification/FR-007-delete-task.html) |
