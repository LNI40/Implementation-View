# Das LNI4.0 Edge Management Testbed
## Motivation
Industrie 4.0 verbindet die traditionelle Welt der Fertigung (OT) mit den Möglichkeiten der modernen IT. Ein zentrales Element dieser Verbindung sind Edge-Geräte. Diese spielen in der Fabrikautomatisierung eine Schlüsselrolle. Jedoch stellt die Auswahl und Einrichtung, also Konfiguration dieser Geräte nur einen Teil der Herausforderung dar. Denn vor allem in der Integration sowie des Managements der Geräte liegt häufig eine besondere Komplexität. Auch die entsprechende Software und Verbindungen werden benötigt, um ein effizientes und interoperables Projekt zu gewährleisten.

Derzeit sind die meisten Edge Management Systeme proprietär. Das bedeutet, dass sie nur mit den Geräten des einen jeweiligen Herstellers vollständig kompatibel sind, weil sie nicht auf einheitlichen Standards aufsetzen. Dies stellt ein erhebliches Hindernis für die Flexibilität dar und erschwert die weitere Verbreitung von Edge-Geräten.

Im [LNI4.0 Edge Management Testbed](https://lni40.de/angebot/testbeds/testbed-emt/) haben sich verschiedene Hersteller von Edge Management Lösungen zusammengeschlossen und entwickeln gemeinsam herstellerübergreifende Standard-Lösungen, damit Edge-Geräte verschiedenen Hersteller nahtlos zusammenarbeiten können.

## Business View
https://lni40.de/wp-content/uploads/2023/02/BusinessView-LNI40TestbedEdgeManagement_published-V2.0.pdf

## Usage View
https://lni40.de/wp-content/uploads/2023/02/UsageView-TestbedEdgeConfiguration_publish-10032020.pdf

## Functional View
https://github.com/LNI40/Implementation-View/blob/main/FunctionalView-TestbedEdgeConfiguration_V8.4.pdf (Draft, not released yet.)

## Implementation View
![image](https://user-images.githubusercontent.com/50681355/154436133-46863aa5-661c-4008-aa35-6d871edc52ab.png)

## Whitepaper Implementation Options
https://lni40.de/wp-content/uploads/2023/02/2022-05-11_WhitePaper-TestbedEdgeManagement-06_final.pdf

## Testbed Edge Management - Demonstrator 
https://lni40.de/wp-content/uploads/2023/04/LNI-4.0-Testbed-Edge-Management-Demonstrator.pdf
[Live-System](https://ca-ems-frontend-dev-001.yellowtree-6659c4fd.northeurope.azurecontainerapps.io/dashboard)   
![image](https://github.com/user-attachments/assets/77933741-e446-4245-bdea-88e6dc914d1f)   
![image](https://github.com/user-attachments/assets/0973598d-c343-4f83-af88-ac5355fcb92c)   

## OpenAPI Spezification für eine Edge Management REST API
Die Grundidee besteht darin, Systemschnittstellen zwischen den Einheiten innerhalb der Edge-Architektur zu spezifizieren, indem die Interaktionen im Dokument „Functional View“ analysiert werden.
Die Erstellung formaler Schnittstellenspezifikationen unter Verwendung bekannter Standards wie openAPI und asyncApi ermöglicht die automatische Erstellung von Testfällen und den Einsatz einer breiten Palette von Werkzeugen für die Testumgebung. Wir wollen das Rad nicht neu erfinden: Teilnehmer können sich mit bereits existierenden Lösungen melden und wir können diese so weit wie möglich übernehmen!

![image](https://user-images.githubusercontent.com/50681355/154436060-e9fbaec2-91dc-4147-871c-0fe99572b62b.png)

Aktueller Stand der API:
[http://editor.swagger.io/open?url=https://github.com/LNI40/Implementation-View/blob/main/OpenApi-Implementation-View.yml](https://editor.swagger.io/?url=https://raw.githubusercontent.com/LNI40/Implementation-View/main/OpenApi-Implementation-View.yml)

## Weitere Veröffentlichungen
- M. Rentschler, D. Rohrmus, U. Lowen, A. G. Gatterburg, B. Vojanec, and A. Willner, "*Standardization of Edge Configuration*", in 2020 25th IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), Vienna, Austria. https://doi.org/10.1109/ETFA46521.2020.9212053
- M. Rentschler, X-T. Dang, D. Rohrmus, A. G. Gatterburg,"*Edge-Management im Industrial Internet of Things*", in KommA 2024, Lemgo, Germany. https://jk-komma.de/index.php/programm

## Legal Disclaimer

### © Copyright 2022  Labs Network Industrie 4.0
This work is licenced under the Creative Commons Zero Licence (https://creativecommons.org/publicdomain/zero/1.0/deed.de)

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Specification.

THE SPECIFICATION IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SPECIFICATION OR THE USE OR OTHER DEALINGS IN THE SPECIFICATION.

