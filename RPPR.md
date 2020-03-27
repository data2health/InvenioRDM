# Budget
Don't edit this - the RPPR generator populates this section

# Research Design
Infrastructure that can be easily deployed and managed locally to collect, record, preserve, and disseminate a wide range of digital works across the translational workforce (e.g., datasets, protocols, education or engagement materials, technical reports, supplemental materials, survey instruments) is critical to enhance their visibility, promote people and their expertise, support attribution of their work, aid the discovery and accessibility by the international scientific community, and support open and FAIR science. Such an initiative requires a trusted framework for digital objects, good data practice workflows; incorporation of standards and persistent identifiers; incorporation of privacy considerations, and strategies to support implementation and integration as well as incentivize individuals participating in such an ecosystem. Here we are developing an integrated, born-interoperable repository and data catalog to empower researchers as they engage in good data practices around research data management, licensing, preservation, credit, discovery, and reuse of these digital artefacts and data at their hubs. This next-generation repository is being built in partnership with CERN on their Invenio platform. Invenio is a a safe, secure, scalable, and RESTful architecture to power the repositories of CERN and many other organizations in a mature open source community. The software will be made openly available for local level implementation by hubs and we are working in parallel to make a cloud instance available for broad use.

Building on this foundation, in year 3 the Northwestern team will produce a containerized version of the software, readily deployable from the cloud; deploy at NU (local node, including migration of 6K+ files) and in NCATS cloud (to function as both a local node & also serves as master index). We will continue deep engagement with stewards for data discovery engine (DDE), such as the Data Catalog Collaboration Project and others sites, and work with stakeholders and the Scripps team to deploy the DDE to the NCATS cloud (with indexed data from various sources & user submitted records). Our deliverables include a repository & data index for local deployment with enhanced features and select support for next-generation repository behaviors ([relationships between the NGR behaviors and technologies](http://ngr.coar-repositories.org/)), version 1 of a production-ready data discovery engine, documentation & use cases. 

# Methodology

**Agile Methods**

The InvenioRDM project uses the Agile development methodology. This methodology embraces constant change and project complexity. Development is separated into two-week sprints. The sprint is kicked off with a planning meeting where it is decided what work will be completed in the two-week increment, and how the work will be achieved. Any dependencies or blockers are discussed at this time.  The team has daily stand-ups where reports of work are shared, as well as concerns or blockers. Course corrections are made quickly. The Agile methodology promotes communication, flexibility and a product mindset where the needs of the user are taken into account. This framework promotes continuous iteration of feedback, development, planning, integration, and testing through the lifecycle of the project. Development and testing are concurrent, unlike the Waterfall model which mandates all development must be complete before testing can begin.

It is important for us to be able to demonstrate that what we are creating works as intended. Each function (feature) is associated with a user story which is worked on during a sprint (or sprints). Acceptance criteria is used to confirm the function meets requirements.  This is essentially a checklist that verify the user story is completed and working. Before a story can be marked as ‘done’, all criteria must be fulfilled so that it’s ensured the user story works as planned and tested. Continuous integration and testing are important to this process.  This is a different mindset than the more old school waterfall practice where it is only at the end the product is tested. Using that methodology, if a requirement error is found or made, then the project must start from the beginning to fix deficits. 

**Invenio**

For this work, we are leveraging [Invenio](https://invenio-software.org/), a software platform created by the European Organization for Nuclear Research (CERN) and used as the group’s main repository for more than 10 years and the foundation of Zenodo, the foundation of the European OpenAire repository network. The Invenio team recently released a modernized, safe, and scalable version of the code. Invenio 3.0 offers a number of advantages (https://invenio-software.org/):
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

- Establishment of infrastructure that can be easily deployed and managed locally to collect, record, preserve, and disseminate a wide range of digital works across the translational workforce (e.g., datasets, protocols, education or engagement materials, technical reports, supplemental materials, survey instruments).
- This infrastructure is necessary to enhance their visibility, promote people and their expertise, support attribution of their work, aid the discovery and accessibility of datasets and other digital objects by the international scientific community, and support open and FAIR science. 

# Deliverables

* Repository & data index for local deployment by hubs
* Repository landscape analysis
* Documentation & use cases
* Branding and outreach
- Guidebook content (Repositories and CTS; Discoverability of datasets)

# Timeline (monthly)
- 7/1/19 Landscape analysis of repositories, repository frameworks, and data catalogs
- 8/31/19 DigitalHub parity
- 9/15/19 Documentation & use cases
- 9/15/19 A containerized InvenioRDM instance will be deployed and installed at NU in a local production environment, and the InvenioRDM team will continue to add features and functionality into 2020
- 9/15/19 Outreach and engagement with stewards for data discovery engine (ongoing)
- 10/1/19 Begin work with 1+ pilot implementation sites; this deliverable and subsequent work toward it will depend on local timelines at pilot sites (engagement to identify pilots has begun)
- 10/15/19 Code made available for the community to download
- 11/20/19 Guidebook Chapter: Repository architecture and culture to support CTS
- 4/1/20 Local instance deployed at NCATS cloud (example of a local node & serves as master index)
- 6/15/20 InvenioRDM will be deployed in the NCATS cloud and will contain indexed user submitted records and digital objects from more than one institution
- 6/15/20  Next-generation repository behaviors supported (in collaboration with CERN and NII)

# Potential Pitfalls and Alternative Strategies
The project team has carefully considered the project, scope, and technology in the development of this project during its visioning and development -- as well as throughout every stage stage since launch in support of continuous improvement. Moreover, we have worked carefully with multiple stakeholder groups gather input on desired features, requirements, and use cases. Even with careful planning, challenges often arise and must be addressed.  Some of the key outstanding potential challenges include:
- **Adoption of software by hubs.** We have already begun ramping up engagement efforts, connecting with the repository community as well as with the research community through conversations at professional meetings, virtual presentations, collaborative meetings, and phone calls. We will also work to meet hubs “where they are” so that those hubs with existing tools can be supported and offered guidance to understand what updates (if any) might be needed to open their own repositories for discovery. This will also help us construct a community of practice around data assets and their preservation, indexing, interoperability, and discovery.
- **Coordination of interoperable instances of data to allow indexing and search.** Galter Library is in the process of signing a formal MOU to indicate our formal development relationship with CERN. Current collaborative efforts with CERN support a Next Generation Repositories (NGR) as envisioned by the Confederation of Open Access Repositories (COAR), of which Northwestern’s Galter Library is a member, along with other CTSA institution libraries. The NGR serves as a foundation for a distributed, globally networked infrastructure for scholarly communication and will support deployment of value added services, making the system more research-centric and supportive of innovation. NU has a strong collaborative relationship with COAR and CERN and are collaborating with several universities and COAR to launch a NGR group in the United States with the aim of platform-agnostic, cross-repository interoperability.
- **NGR development will lag or feature requests will overwhelm the development team.** Over the course of the next phases of development, Invenio will be further enhanced with NGR functionality and a range of user-focused features such as easy user profile creation, record upload and metadata options, incorporation of persistent identifiers, connection with site’s authentication system, attribution for contributions, HTML signposting, and robust social and impact components. This work will be completed at Northwestern, with partnership on the NGR work by CERN, NII, and others - allowing us to share the workload. Moreover, a collaborative effort led by CERN had coordinated a new research data management module enhancement for Invenio. This effort will help make research more findable, accessible, interoperable, and reusable in accordance with FAIR data principles.
- **Staffing.** The substantial work accomplished on this project has been completed by a relatively small team. At present, we are relying on only one very talented software engineer to make all development progress. Until we hire someone, this is a single point of failure and serious illness, change in life plans by this engineer, or other impacts have potential to derail progress significantly.

# Y3 (July 1, 2019-June 30, 2020) Accomplishments 
The following content is from the June 30 - Dec 30, 2019 mid year progress report [here](https://docs.google.com/document/d/1LLe3uCfEUakWxIJyi5SA4ZocYDmINvhySTperaui1Bw/edit).  Please add progress for Jan 1 - June 30th, 2020. 

* Repository & data index for local deployment:
    * Establishment of infrastructure that can be easily deployed and managed locally to collect, record,   preserve, and disseminate a wide range of digital works across the translational workforce (e.g., datasets, protocols, education or engagement materials, technical reports, supplemental materials, survey instruments).This infrastructure is necessary to enhance their visibility, promote people and their expertise, support attribution of their work, aid the discovery and accessibility of datasets and other digital objects by the international scientific community, and support open and FAIR science.

    * The first deployment of a research data management repository and data index was completed in 09/2019 on a Northwestern server and made available openly to the public with a login and password to help demonstrate the full function of the platform, available [here](https://vtfsmghslapps04.fsm.northwestern.edu/); [download and installation instructions](https://github.com/inveniosoftware/invenio-app-rdm/wiki) are also available. This local instance was deployed and made available for CTSA Fall Meeting. Since this time, we have merged our code with the collaborative InvenioRDM development effort and have accomplished monthly software releases:
        * [October release](https://invenio-talk.web.cern.ch/t/inveniordm-alpha-1-october-release/44) on 10//2019
        * [November release](https://invenio-talk.web.cern.ch/t/inveniordm-alpha-2-november-release/51) on 11/29/2019
        * [December release](https://invenio-talk.web.cern.ch/t/inveniordm-alpha-3-december-release/61) on 12/20/2019

    * This work is ongoing and wrapped into the larger InvenioRDM collaborative development effort. The same schedule of monthly releases is planned for January, February, and March 2020 to complete the early development and testing activities and produce the release candidate. The final release is due June 2020.

    * The GitHub project [roadmap](https://inveniosoftware.org/products/rdm/roadmap/) and [monthly project boards](https://github.com/orgs/inveniosoftware/projects) detail what has been completed, current work, and future tasks. We’ve made significant progress on development and plan to continue this work in the Phase 3 period as part of the development work.

* Repository landscape analysis:
    * We have created a list of repositories, repository frameworks, and data catalogs to:

      * Provide a "lay of the land" summary of existing software
      * Identify important features (especially those that fall in the "next generation repository" category) that we'll want to incorporate in our repository and data index project, InvenioRDM
      * Identify the tools that may have some level of interoperability with our project

    * This survey focuses on technical architecture, how metadata is handled and what standards are used, and what next-generation repository features (if any) are implemented.

    * This is an ongoing analysis. To access the living doc, go here. Ticket 77 is associated with this work and is marked as an ‘good first issue’ for new contributors to the project. It is regularly updated and new related tools are added as appropriate. Here is the living document and associated GitHub repository.


* Documentation & use cases:
    * Our project Github is a living source of documentation and uses cases and we have made significant progress over this funding cycle in this area, outlined below:

    * InvenioRDM use case slides were made for the CTSA fall meeting and are available here. 

    * Other project resources to support documentation and use case objective 
      * CD2H GitHub site for InvenioRDM
      * Galter Library GitHub site for local deployment
      * InvenioRDM GitHub site at CERN
      * Invenio Framework:
        * Documentation
        * Training
      * The Invenio Project Read the Docs is a rich source of documentation. It is also a live document, constantly being updated.
      * InvenioRDM Read the Docs, similar to above but specifically for the turn key RDM project
      * InvenioRDM deployment and installation Wiki

* Branding and outreach:
    * We have focused significant efforts on outreach and branding efforts for the collaborative project and especially to support requirements gathering and US-based adoption.
      * We have contacted all CD2H participants who’ve onboarded and indicated an interest in this project to say hi, remind them of our github, and direct them here.
      * We continue to contact people who have indicated interest in our project but never onboarded, share this [CD2H GitHub site](https://github.com/data2health/InvenioRDM).
      * Make use of #InvenioRDM on [CD2H Slack](https://cd2h.slack.com/messages). This channel will be used to chat about the project, answer questions, be a community spot. We'll also share relevant files, presentations, announcements for feedback, networking.
      * Social coding - Use Github to communicate, share work and collaborate with above mentioned communities
      * Conferences/Workshops - Attend Open Source Conference - [OSCON](https://conferences.oreilly.com/oscon/oscon-or) (Summer 2019)
      * Explore collaborations with existing systems such as the [Data Catalog Collaboration Project](https://www.datacatalogcollaborationproject.org/) (DCCP), NYU, UVA, and others to enhance interoperability.
      * Collaboration with the [Institute for Innovations in Developmental Sciences](https://devsci.northwestern.edu/), a transdisciplinary group at Northwestern University focused on the lifespan. We attend biweekly meetings to understand their needs, and will work with them as our first user group upon deployment.
      * Create documentation and support for the community
      * Periodic briefs and/or presentations to key stakeholders
      * Social media - Share updates and/or examples of work through blog posts, [Twitter](https://www.twitter.com/data2health), newsletters.
      * [InvenioRDM website](https://inveniosoftware.org/products/rdm/) launched September 2019.
      * Current project [Roadmap](https://inveniosoftware.org/products/rdm/roadmap/).
      * [Discussion Forum](https://invenio-talk.web.cern.ch/c/projects/invenio-rdm) for collaborative decision making and documentation of decisions
      * [Gitter channel](https://gitter.im/inveniosoftware/InvenioRDM) for technical and conceptual discussion
      * [InvenioRDM-related Events](https://inveniosoftware.org/events/) such as webinars, training bootcamps, and workshops
      * [InvenioRDM Features and FAQs](https://inveniosoftware.org/products/rdm/#features)
      * [InvenioRDM Project Board](https://github.com/orgs/inveniosoftware/projects): describes individual technical tasks that are completed, in-progress, and upcoming. The project boards are created monthly and lay out the scope of work for the sprint. 
      * [InvenioRDM Request For Comments (RFCs)](https://github.com/inveniosoftware/rfcs): RFCs help to coordinate the design process, produce consensus among stakeholders, and document design decisions. It also allows community members to express their opinions on design and features for the project, available on GitHub.

* Engagement
    * InvenioRDM project press, such as the[Announcement](https://invenio-software.org/blog/2019-04-29-rdm/) for InvenioRDM collaboration.
   * Online meeting introducing Andrew Willliams of Tufts to Invenio (Kristi Holmes, Matt Carson, Sara  Gonzales, Guillaume Viger, Lisa O'Keefe - 12/2/2019)
   * Presentation and Demo - InvenioRDM: Deployable Digital Repository Software by CERN and Northwestern University (Guillaume Viger, Code4Lib Chicago Fall 2019 Meeting, 11/14/2019)		
   * Presentation - Personas and their use in a Library Development Project (Sara Gonzales, Code4Lib Chicago Fall 2019 Meeting, 11/14/2019)
   * Presentation - [CERN InvenioRDM kickoff, slides](https://digitalhub.northwestern.edu/files/77a0ca55-82c7-4256-9f1f-94c39af49cbe)
   * [Presentation](https://zenodo.org/record/3570807) and real-time installation demonstration, Coalition for Networked Information meeting
    * Seminar at Washington University 11/4/2019 
    * Seminar at  Northwestern University 12/3/2019
    * Presentation - The Association of Black Cardiologists (ABC) Cardiovascular Implementation Study (CVIS), CD2H and InvenioRDM. 12/15/2019

* Collaborations
    * The team has been encouraged by the discussions and opportunities for collaboration with the Data Catalog Collaboration Project (DCCP) through various meetings and activities (DCCP includes NYU Langone Health; Duke University; Memorial Sloan Kettering Cancer Center; University of Maryland, Baltimore; University of North Carolina at Chapel Hill; University of Pittsburgh; University of Virginia; Wayne State University; Weill Cornell Medicine; Zucker School of Medicine at Hofstra/Northwell, with extensive  conversations and/or demos for NYU, University of Virginia, and Duke to date). This larger collaboration is moving to a “platform-agnostic model” and Northwestern has joined this open collaboration. Sara Gonzales has been invited to a workshop about data catalogs and indexes in February at NYU based on her extensive work to date on the InvenioRDM tool.

* Demos completed/scheduled
    * UVA, Caltech, Tufts, University of Maryland/JHU, University of Nebraska Medical Center, UCDavis
University of Arizona, University of Buffalo, and Yale University. 

* Communications
    * Emails about InvenioRDM activities have been sent to the following listservs: the Association of Academic Health Sciences Libraries (AAHSL), Research Impact Services, and Transforming Research

    * The project and outputs have been shared widely on Twitter, targeting #CTSAProgram, #medlibs, #datalibs, and events such as the CTSA Program fall meeting, the Coalition for Networked Information fall meeting, and others.

* Guidebook content (Repository architecture and culture to support CTS, Best Practices for Disseminating CTS)
    * The Guidebook Chapter is complete and available for viewing [here](https://reusable-data-best-practices.readthedocs.io/en/latest/chapters/chapter_7.html). 
