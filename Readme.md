# LNI4.0 Implementation View

OpenAPI specification for an edge management REST API

## OpenAPI

OpenAPI Specification (formerly Swagger Specification) is an API description format for REST APIs. An OpenAPI file allows you to describe your entire API, including:

- Available endpoints (/users) and operations on each endpoint (GET /users, POST /users)
- Operation parameters Input and output for each operation
- Authentication methods
- Contact information, license, terms of use and other information.

API specifications can be written in YAML or JSON. The format is easy to learn and readable to both humans and machines. The complete OpenAPI Specification can be found on GitHub: OpenAPI 3.0 Specification

(Source https://swagger.io/docs/specification/about/)


### Tooling
- Specification: https://swagger.io/docs/specification/basic-structure/
- Online Editor: https://editor.swagger.io/
- Offline Editor: [Visual Studio Code](#https://code.visualstudio.com/ ) + [OpenAPI (Swagger) Editor](#https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi) (recommended)

### Workflow

GitHub is a provider of Internet hosting for software development and version control using Git. Git is great tool for tracking changes in any set of files. This way, a file can easily always be overwritten and you can always jump back to an older state or track all changes. A main feature of git are branches, effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes. After you finished your changes, you can merge your branch into the main branch (Pull Request).

**short**: 
- create featureBranch
- push your Changes to your feature branch
- create a pull request to merge your feature branch in the main branch 

All these steps can also be done via the github web interface.
- [create new Branch](#https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#creating-a-branch)
- [changing files](#https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [create pull request](#https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)


