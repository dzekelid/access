swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/quizzes/id/validate_access_code:
    post:
      summary: Validate quiz access code
      description: Validate quiz access code.
      operationId: validate-quiz-access-code
      x-api-path-slug: coursescourse-idquizzesidvalidate-access-code-post
      parameters:
      - in: query
        name: access_code
        description: The access code being validated
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Quizzes
      - Id
      - Validate
      - Access
      - Code