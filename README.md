# InTaVia Milestone-3
InTaVia Milestone 3 Documentation - Basic Operational Sytem 

Individual components of the system operational with connectivity partially established and ready for evaluation by WP7.

**_What is part of the system at MS3? Document parts here with description of compontents and relations between them + URLs_**

**_Please create releases of the GitHub repositories and link here_**

## WP2
**Ingestion workflow**
-  Finland (Aalto / UH)
- Austria (OeAW)
- BiographyNet (VU)
- Slovenia >> talk to Joh

**InTaVia graph-related workflows**
- v1
- v2
- v3

**JSON API**
2 endpoints (grlc) / object type

## WP3

**Conversion Pipeline APIS data**

**Ingestion pipeline**

**Basic enrichment pipeline for CH data**

**API definitions**

## WP4
- Martin's Work > Deliverable 4.2
- Performancer: Model selection & comparison

## Frontend (WP5 & WP6)
The Milestone 3 Prototype (v0.1.0) of the InTaVia web client (frontend) is available as a permanent release: [https://github.com/InTaVia/web/releases/tag/v0.1.0](https://github.com/InTaVia/web/releases/tag/v0.1.0)

The current prototype is available online: [https://intavia.acdh-dev.oeaw.ac.at/](https://intavia.acdh-dev.oeaw.ac.at/).

The data shown in the application are automatically generated mock data including person and place entities. As soon as the connection between the backend and the frontend is established, the mock data will be replaced. **Note:** if below linked visualizations do not show results, please first do a search on the search page and then switch back to the visualization.

The prototype implements aspects of the three top-level components (Data Curation Lab, DC lab; Visual Analytics Studio, VA studio; Visual Storytelling Suite, ST suite) in a single applications on separate pages. The components implented are:

### DC lab
"DC Lab:
- Keyword search and list view of search results: [https://intavia.acdh-dev.oeaw.ac.at/search](https://intavia.acdh-dev.oeaw.ac.at/search)
- Detail view of entities: e.g., [https://intavia.acdh-dev.oeaw.ac.at/person/876859d3-dee8-468d-9c61-a29e97ef478a](https://intavia.acdh-dev.oeaw.ac.at/person/876859d3-dee8-468d-9c61-a29e97ef478a)
- Basic editing compatibilties of person entities (name, description, event types & dates) - click edit on the detail view page.
- Shared glboal Redux store that can be accessed by all components 
- Shared frontend network module using RTKQuery (handles requests to data endpoints and deduplication of results)

### VA studio
Data views:
- Timeline view showing a set of person entities with selected life events (e.g. birth, death, lived): [https://intavia.acdh-dev.oeaw.ac.at/timeline](https://intavia.acdh-dev.oeaw.ac.at/timeline)
- A geographic map view showing localized life events (i.e., birth and death) connected with a line in a chronological order: [https://intavia.acdh-dev.oeaw.ac.at/geomap](https://intavia.acdh-dev.oeaw.ac.at/geomap)

Coordinated views:
- Multiple views integrated on a single page are shown here: [https://intavia.acdh-dev.oeaw.ac.at/coordination](https://intavia.acdh-dev.oeaw.ac.at/coordination)
- list-timeline-map highlighting

Visual querying:
- query for persons based on attribute constraints including name and date of birth and death: 

### ST suite = ST creator + ST viewer
- Definition of GUI structure for storytelling editor
- Development of clickable prototype (Fluxguide - online?)
- A clickable Adobe XD prototype of the ST viewer is available online: [https://xd.adobe.com/view/b3de8bf3-1e43-434a-b06f-a99939eb2e6e-e68d](https://xd.adobe.com/view/b3de8bf3-1e43-434a-b06f-a99939eb2e6e-e68d)

## Next Steps
- Establish the connection between the backend and the frontend.
- Finalize the response shape of the endpoints an the frontend data schema.
- Integratge the different components in a joint user interface with panels to better support user workflows (and not on seperate pages).
- Prepair the protoype for evaluation (Workshops in August 2022)
- Further develop the data views, including set and network visualizations.
