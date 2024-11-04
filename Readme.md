
# LNI4.0 Business View
https://lni40.de/wp-content/uploads/2023/02/BusinessView-LNI40TestbedEdgeManagement_published-V2.0.pdf

# LNI4.0 Usage View
https://lni40.de/wp-content/uploads/2023/02/UsageView-TestbedEdgeConfiguration_publish-10032020.pdf

# LNI4.0 Whitepaper Implementation Options
https://lni40.de/wp-content/uploads/2023/02/2022-05-11_WhitePaper-TestbedEdgeManagement-06_final.pdf

# LNI4.0 Functional View
https://github.com/LNI40/Implementation-View/blob/main/FunctionalView-TestbedEdgeConfiguration_V8.4.pdf (Draft, not released yet.)

# LNI4.0 Implementation View

![image](https://user-images.githubusercontent.com/50681355/154436133-46863aa5-661c-4008-aa35-6d871edc52ab.png)

OpenAPI specification for an edge management REST API:
The basic idea is to specify system interfaces between the entities within the edge architecture by analyzing the interactions in the Functional View document.
Creating formal interface specifications using well-known standards like openAPI and asyncApi will allow automatic testcase creation and the use of a wide range of tools for the testbed.
We do not want to re-invent the wheel: Participants may come forward with already existing solutions and we may adopt them as much as possible!

![image](https://user-images.githubusercontent.com/50681355/154436060-e9fbaec2-91dc-4147-871c-0fe99572b62b.png)

View current state in Swagger-Editor:
[http://editor.swagger.io/open?url=https://github.com/LNI40/Implementation-View/blob/main/OpenApi-Implementation-View.yml](https://editor.swagger.io/?url=https://raw.githubusercontent.com/LNI40/Implementation-View/main/OpenApi-Implementation-View.yml)

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

## Legal Disclaimer

#### © Copyright 2022  Labs Network Industrie 4.0
This work is licenced under the Creative Commons Zero Licence (https://creativecommons.org/publicdomain/zero/1.0/deed.de)

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Specification.

THE SPECIFICATION IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SPECIFICATION OR THE USE OR OTHER DEALINGS IN THE SPECIFICATION.

