# Notes on Tools to Work with REST APIs

[Postman](https://github.com/kkumykova/working-with-rest-apis/blob/main/postman.md)

[cURL](https://github.com/kkumykova/working-with-rest-apis/blob/main/curl.md)

## Two most common types of APIs:
- Web APIs (REST)
- Platform APIs (Java, C++, etc.)

## Documentation
### API Conceptual Material

Conceptual Material Consists of:
- Overview
  - Explain **why** to use the API
    The overview must explain why you would use it
    - Describe key features
    - Provide a few use cases

  - List Requirentments for the API
    - Provide a list of what is required.
    - Get this list from the development team.
    - For Web APIs:
      - This usually isn't included
      - However, for some APIs, you need a separate authentication server. 

  - Key Concepts
    - APIs typically have important concepts that should be described.
    - This usually depends on the "domain" - what does the API do?
    - Write a paragraph or two for each concept. Examples:
      - Learning Management System: Roles, classes, grades, etc.
      - Online Banking: Accounts, transactions, etc.

  - Explain Workflow: what are the most common steps to do common tasks.
    
  - Diagrams - a good place for visual information: architechture diagrams and/or data model diagrams
    - Architecture Diagrams: how do the pieces fit together?
    - Workflow Diagrams: what happens when?
    Get diagrams from the development team.
    
- Getting Started
  -  Getting Started Section [Example](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm) 
  - Lead people through a simple task
  - Web APIs
      - Registration
      - Get an app key
      - Making one or two HTTP requests that return a response
      - Typically not something that requires complex authorisation (like three-legged OAuth)
      - Authorisation
      - Doing something simple

  - Platform APIs
      - Downloading the SDK (softwear development kit)
      - Setting up your IDE
      - Doing something simple
        
- Tutorials - have the same structure as Getting Started is because Getting Started _is_ a tutorial!
  - 3 to 5 tutorials are usually enough
  - Common Tasks
  - Step-by-step instructions
  - Sample HTTP requests or code they can copy and paste
  - Screenshots, if they make sense - usually are not needed for Web APIs; only if the tutorial involves doing something with the developer portal.
  - Start with basic tasks, move to advanced

- Sample Code
  - Short, simple programs that work
  - Developers like to be able to copy and modify them
  - Common tasks
  - Well-commented
