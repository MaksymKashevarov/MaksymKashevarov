<p align="center">
  <img src="./assets/banner.png" alt="ARC Banner" width="100%" />
</p>

<h1 align="center">Maksym Kashevarov</h1>

<p align="center">
  <b>Software Engineer · System Architecture · Cloud Automation · Game Development</b>
</p>

<p align="center">
  Building modular systems, automation pipelines, and gameplay architecture.
</p>

---

## Featured Work

### [ARC Cloud Runtime](https://github.com/MaksymKashevarov/atene-arc-cloud-runtime)

Cloud execution layer for automated document-generation workflows.

```text
SharePoint
→ Power Automate
→ Request Queue
→ Azure Functions
→ Python Runtime
→ Excel Generation
→ Microsoft Graph Upload
→ Result Link in SharePoint
```

### Implemented

* single and batch document generation
* Forschungszulage and ZIM workflows
* SharePoint-based request queue
* generic processor flow
* Azure Function request routing
* absence workbook import
* automatic Excel parsing and normalization
* document generation per employee
* calendar and holiday validation
* SharePoint upload through Microsoft Graph
* automatic result delivery back to SharePoint
* request archive and cleanup flow

### Runtime Structure

```text
INPUT
├── Standard Request Assembly
└── Absence Import Request Assembly

QUEUE
└── request.json + ready.trigger

PROCESSING
└── Generic Processor Flow
    └── Azure Function /arc-request
        └── ArcRequestProcessor

USE CASES
├── Single Generation
├── Batch Generation
└── Absence Workbook Import

OUTPUT
└── Microsoft Graph Upload
    └── SharePoint Result Link
```

The generators remain atomic:

```text
One employee
→ One year
→ One region
→ One document type
→ One Excel file
```

Batch requests and imported workbooks are processed through repeated calls to the same single-document generators.

---

## Selected Projects

### [ARC Cloud Runtime](https://github.com/MaksymKashevarov/atene-arc-cloud-runtime)

Cloud runtime for ARC workflows using Azure Functions, Power Automate, SharePoint, Python, openpyxl, and Microsoft Graph.

### [LLMWorkshop](https://github.com/MaksymKashevarov/LLMWorkshop)

Original modular reporting system for German Stundenzettel generation. The project became the foundation for the later ARC cloud runtime.

### InjectDustry

Unity dependency injection and composition framework focused on explicit initialization, modular system assembly, and predictable lifecycle management.

---

## Technical Areas

### System Architecture

* modular architecture
* composition-based systems
* dependency injection
* explicit initialization flow
* stable entry-point design
* service-oriented processing
* builder pipelines
* request routing
* reusable atomic components
* validation layers
* incremental system expansion

### Cloud Automation

* Azure Functions
* Power Automate
* SharePoint workflows
* Microsoft Graph API
* request queues
* batch processing
* document-generation pipelines
* Excel automation
* structured data parsing
* workflow orchestration
* validation and reporting

### Game Development

* Unity
* C#
* Unreal Engine 5
* gameplay systems
* AI behavior architecture
* Behavior Trees
* modular player and entity systems
* dependency injection for game systems
* custom tools and editor workflows
* cinematic game design

---

## Tech Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

### Game Development

<p>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white" />
</p>

### Cloud and Automation

<p>
  <img src="https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" />
  <img src="https://img.shields.io/badge/SharePoint-038387?style=flat-square&logo=microsoftsharepoint&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Graph-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" />
</p>

### Data and Integration

<p>
  <img src="https://img.shields.io/badge/Excel_Automation-217346?style=flat-square&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/openpyxl-2C5F2D?style=flat-square" />
  <img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=flat-square" />
</p>

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

---

## Architecture Patterns

```text
Modular Architecture
Composition
Dependency Injection
Builder Pipelines
Behavior Trees
Service Layers
Atomic Generators
Request Routing
Batch Processing
Validation Layers
```

---

## Contact

<p>
  <a href="https://www.linkedin.com/in/maksym-kashevarov-852a47322">
    <img src="https://img.shields.io/badge/LinkedIn-Maksym_Kashevarov-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:kmaximlk04@outlook.com">
    <img src="https://img.shields.io/badge/Email-Contact-5E5E5E?style=flat-square&logo=microsoftoutlook&logoColor=white" />
  </a>
</p>
