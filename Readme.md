# LNI4.0 Implementation View

![image](https://user-images.githubusercontent.com/50681355/154436133-46863aa5-661c-4008-aa35-6d871edc52ab.png)

OpenAPI specification for an edge management REST API:
The basic idea is to specify system interfaces between the entities within the edge architecture by analyzing the interactions in the Functional View document.
Creating formal interface specifications using well-known standards like openAPI and asyncApi will allow automatic testcase creation and the use of a wide range of tools for the testbed.
We do not want to re-invent the wheel: Participants may come forward with already existing solutions and we may adopt them as much as possible!

![image](https://user-images.githubusercontent.com/50681355/154436060-e9fbaec2-91dc-4147-871c-0fe99572b62b.png)


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


