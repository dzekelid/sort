---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/assortment/:
    get:
      summary: Get Users Assortment
      description: Retrieve the assortment for the user.
      operationId: getUsersAssortment
      x-api-path-slug: usersidassortment-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
    post:
      summary: Post Users Assortment
      description: |-
        Set a user&#8217;s assortment and returns the assortment for the specified
        user.
      operationId: postUsersAssortment
      x-api-path-slug: usersidassortment-post
      parameters:
      - in: query
        name: plan
        description: The assortments package to upgrade/downgrade to
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
---