---
name: Google Tasks
x-slug: google-tasks
description: The Google Tasks API lets you search, read, and update Google Tasks content
  and metadata. This document describes how to use a RESTful calling style and client
  libraries for various programming languages (currently Java, Python, and PHP) to
  access and edit Google Tasks data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Clear
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/google-tasks/apis.md
specificationVersion: "0.14"
apis:
- name: Google Tasks API Add Lists Task List Clear
  x-api-slug: google-tasks-api
  description: Clears all completed tasks from the specified task list. The affected
    tasks will be marked as 'hidden' and no longer be returned by default when retrieving
    all tasks for a task list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
  humanURL: https://developers.google.com/google-apps/tasks/
  baseURL: ://www.googleapis.com//tasks/v1//lists/{tasklist}/clear
  tags: Lists, Task, List, Clear
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/google-tasks/liststasklistclear-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/google-tasks/liststasklistclear-post-openapi.md
- name: Google Tasks API
  x-api-slug: google-tasks-api
  description: The Google Tasks API lets you search, read, and update Google Tasks
    content and metadata. This document describes how to use a RESTful calling style
    and client libraries for various programming languages (currently Java, Python,
    and PHP) to access and edit Google Tasks data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
  humanURL: https://developers.google.com/google-apps/tasks/
  baseURL: ://www.googleapis.com//tasks/v1
  tags: Clear
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clear/master/_listings/google-tasks/openapi.md
x-common:
- type: x-code
  url: https://developers.google.com/google-apps/tasks/setup
- type: x-concepts
  url: https://developers.google.com/google-apps/tasks/concepts
- type: x-documentation
  url: https://developers.google.com/google-apps/tasks/v1/reference/
- type: x-website
  url: https://developers.google.com/google-apps/tasks/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---