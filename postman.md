# Postman Collections
- A collection is a folder that stores all the requests related to an API or they are somehow related to one another.

- Variables:
  - the variable name is between curly brackets {{baseUrl}}
  - current value - a value used by Postman; privat to your account, no one else can see the current values.
  - initial value - important for sharing; can/should be overwritten, replaced with a placeholder when sharing sensitive data.
  - collection variables are unresolved if the request is not saved in the same collection where the variable is defined.

# Query Parameters
- can be optional or mandatory (as specified by the API documentation)

# Path Parameters
- always mandatory if the endpoint mentions them
- the notation for path parameter is :variableName (don't forget the colon)
- path parameters are just placeholders
- the name of the path parameters are not being sent with the request
- you can have both query and path parameters
