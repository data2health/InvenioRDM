# Budget
Don't edit this - the RPPR generator populates this section

# Research Design
Infrastructure that can be easily deployed and managed locally to collect, record, preserve, and disseminate a wide range of digital works across the translational workforce (e.g., datasets, protocols, education or engagement materials, technical reports, supplemental materials, survey instruments) is critical to enhance their visibility, promote people and their expertise, support attribution of their work, aid the discovery and accessibility by the international scientific community, and support open and FAIR science. Such an initiative requires a trusted framework for digital objects, good data practice workflows; incorporation of standards and persistent identifiers; incorporation of privacy considerations, and strategies to support implementation and integration as well as incentivize individuals participating in such an ecosystem. Here we are developing an integrated, born-interoperable repository and data catalog to empower researchers as they engage in good data practices around research data management, licensing, preservation, credit, discovery, and reuse of these digital artefacts and data at their hubs. This next-generation repository is being built in partnership with CERN on their Invenio platform. Invenio is a a safe, secure, scalable, and RESTful architecture to power the repositories of CERN and many other organizations in a mature open source community. The software will be made openly available for local level implementation by hubs and we are working in parallel to make a cloud instance available for broad use.

Building on this foundation, in year 3 the Northwestern team will produce a containerized version of the software, readily deployable from the cloud; deploy at NU (local node, including migration of 6K+ files) and in NCATS cloud (to function as both a local node & also serves as master index). We will continue deep engagement with stewards for data discovery engine (DDE), such as the Data Catalog Collaboration Project and others sites, and work with stakeholders and the Scripps team to deploy DDE prototype to NCATS cloud (with indexed data from various sources & user submitted records). Our deliverables include a repository & data index for local deployment with enhanced features and select support for next-generation repository behaviors, a data discovery engine prototype, documentation & use cases. 

# Methodology

**Agile Methods**

The menRva project uses the Agile development methodology. This methodology embraces constant change and project complexity. Development is separated into two-week sprints. The sprint is kicked off with a planning meeting where it is decided what work will be completed in the two-week increment, and how the work will be achieved. Any dependencies or blockers are discussed at this time.  The team has daily stand-ups where reports of work are shared, as well as concerns or blockers. Course corrections are made quickly. The Agile methodology promotes communication, flexibility and a product mindset where the needs of the user are taken into account. This framework promotes continuous iteration of feedback, development, planning, integration, and testing through the lifecycle of the project. Development and testing are concurrent, unlike the Waterfall model which mandates all development must be complete before testing can begin.

It is important for us to be able to demonstrate that what we are creating works as intended. Each function (feature) is associated with a user story which is worked on during a sprint (or sprints). Acceptance criteria is used to confirm the function meets requirements.  This is essentially a checklist that verify the user story is completed and working. Before a story can be marked as ‘done’, all criteria must be fulfilled so that it’s ensured the user story works as planned and tested. Continuous integration and testing are important to this process.  This is a different mindset than the more old school waterfall practice where it is only at the end the product is tested. Using that methodology, if a requirement error is found or made, then the project must start from the beginning to fix deficits. 

**Invenio**

For this work, we are leveraging Invenio, a software platform created by the European Organization for Nuclear Research (CERN) and used as the group’s main repository for more than 10 years and the foundation of Zenodo, the foundation of the European OpenAire repository network. The Invenio team recently released a modernized, safe, and scalable version of the code. Invenio 3.0 offers a number of advantages:
- Safe: Created with security and long-term preservation in mind. 
- Scalable: Invenio is fast. Designed to manage 100M+ records and petabytes of files; data can be archived independently of the size. 
- RESTful: Born for the web, is JSON-native and provides RESTful APIs out of the box that will allow building apps on top of it.
- Open: Invenio is 100% open source licensed under MIT license. Invenio supports open standards for open science.
- A robust community: Large team of developers, active open source community, TIND (CERN spinoff) uses a SAAS-model for Invenio, used by many organizations, and the underlying technology (Python, Flask) is widely supported

**Definitions & Context**
- DigitalHub parity: DOI Characterization, Thumbnailing (through IIIF), Collections, Permissions, File Download, Citation generation Analytics (basic numbers for now - fancy graphics later) Similar record fields, User profile pages for deposits, analytics, preferences
- Next-Gen Repo: Signposting Resource Access Request Social Following Enhanced search Time Embargo Approval Embargo ActivityPub Versioning (COAR)
- Repo landscape assessment: attributes investigated include General, Architecture, Metadata handling, Next-gen repo features, Dissemination, Preservation, Coding, Additional Info

# Expected Outcomes

- Repository & data index for local deployment
- Repository landscape analysis
- Documentation & use cases
- Branding and outreach
- Guidebook content (Repository architecture and culture to support CTS, Best Practices for Disseminating CTS)

# Deliverables

* Repository & data index for local deployment
* Repository landscape analysis
* Documentation & use cases
* Branding and outreach

The relationships between the NGR behaviors and technologies ([image source data](http://ngr.coar-repositories.org/)): 

![alt text](https://github.com/data2health/menRva/blob/master/NGR_Behaviors_and_Technologies.png "NGR Behaviors and Technologies")

# Timeline (monthly)
- 7/1/19 Landscape analysis of repositories, repository frameworks, and data catalogs
- 8/31/19 DigitalHub parity
- 9/15/19 Documentation & use cases
- 9/15/19 Local instance deployed at NU (example of a local node)
- 9/15/19 Repository & data index for local deployment in container
- 9/15/19 outreach and engagement with stewards for discovery engine (ongoing)
- 9/20/19 Guidebook Chapter: Repository architecture and culture to support CTS
- 12/1/19 Guidebook Chapter: Best Practices for Disseminating CTS
- 4/1/20 Local instance deployed at NCATS cloud (example of a local node & serves as master index)
- 6/15/20 Discovery engine prototype (with indexed data from >1 sources, user submitted records and digital objects) to NCATS cloud
- 6/15/20  next-generation repository behaviors supported (in collaboration with CERN and NII)

# Potential Pitfalls and Alternative Strategies
The project team has carefully considered the project, scope, and technology in the development of this project during its visioning and development -- and we have carefully as well as throughout every stage stage since launch in support of continuous improvement. Moreover, we have worked carefully with multiple stakeholder groups gather input on desired features, requirements, and use cases. Even with careful planning, challenges often arise and must be addressed.  Some of the key outstanding potential challenges include:
- **Adoption of software by hubs.** We have already begun ramping up engagement efforts, connecting with the repository community as well as with the research community through conversations at professional meetings, virtual presentations, collaborative meetings, and phone calls. We will also work to meet hubs “where they are” so that those hubs with existing tools can be supported and offered guidance to understand what updates (if any) might be needed to open their repositories for discovery. This will also help us construct a community of practice around data assets and their preservation, indexing, interoperability, and discovery.
- **Coordination of interoperable instances of data to allow indexing and search.** Galter Library is in the process of signing a formal MOU to indicate our formal development relationship with CERN. Current collaborative efforts with CERN support a Next Generation Repositories (NGR) as envisioned by the Confederation of Open Access Repositories (COAR), of which Northwestern’s Galter Library is a member, along with other CTSA institution libraries. The NGR serves as a foundation for a distributed, globally networked infrastructure for scholarly communication and will support deployment of value added services, making the system more research-centric and supportive of innovation. NU has a strong collaborative relationship with COAR and CERN and are collaborating with several universities and COAR to launch a NGR group in the United States with the aim of platform-agnostic, cross-repository interoperability.
- **NGR development will lag or feature requests will overwhelm the development team.** Over the course of the next phases of development, Invenio will be further enhanced with NGR functionality and a range of user-focused features such as easy user profile creation, record upload and metadata options, incorporation of persistent identifiers, connection with site’s authentication system, attribution for contributions, HTML signposting, and robust social and impact components. This work will be completed at Northwestern, with partnership on the NGR work by CERN, NII, and others - allowing us to share the workload. Moreover, a collaborative effort led by CERN had coordinated a new research data management module enhancement for Invenio. This effort will help make research more findable, accessible, interoperable, and reusable in accordance with FAIR data principles.
- **Staffing.** The substantial work accomplished on this project has been completed by a relatively small team. At present, we are relying on only one very talented software engineer to make all development progress. Until we hire someone, this is a single point of failure and serious illness, change in life plans by this engineer, have potential to derail progress significantly.
