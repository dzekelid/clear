swagger: "2.0"
x-collection-name: Google Tasks
x-complete: 1
info:
  title: Tasks
  description: lets-you-manage-your-tasks-and-task-lists-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /tasks/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lists/{tasklist}/clear:
    post:
      summary: Add Lists Task List Clear
      description: Clears all completed tasks from the specified task list. The affected
        tasks will be marked as 'hidden' and no longer be returned by default when
        retrieving all tasks for a task list.
      operationId: tasks.tasks.clear
      x-api-path-slug: liststasklistclear-post
      parameters:
      - in: path
        name: tasklist
        description: Task list identifier
      responses:
        200:
          description: OK
      tags:
      - Lists
      - Task
      - List
      - Clear