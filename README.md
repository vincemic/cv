# **Vincent Miceli - Enterprise Architect**

![Picture Vincent Miceli](https://www.gravatar.com/avatar/301658e9a5451302b1e179bc9726b424)

Buffalo, NY
[vjm@orchardparksoftware.com](mailto:vjm@orchardparksoftware.com)

Latest resume version: <https://github.com/vincemic/cv>

---

## **Professional Summary**  

I am a goal-driven **Enterprise Architect & Technology Leader** with over 30 years of full-spectrum expertise in software development, enterprise architecture, and agile project execution. I have a proven track record of leading technology transformations, building high-performing teams, and delivering innovative digital experiences. I am very experienced at aligning technology with business strategy to create user-centric solutions.

---

## **Core Competencies**

- Software & Cloud Architecture
- Creating and Communicating Architectural Vision
- Team Formation, Leadership & Cross-Functional Collaboration
- Establishing and leading high-performing teams and cross-functional departments
- Building and managing 
- Agile & SAFe Project Management
- Solution Design & Enterprise Integration
- SSDLC & CI/CD/CT Technology and Practices
- Conversational AI & Emerging Tech Innovation  

---

## **Professional Experience**

**Independent Health**  
Williamsville, NY  
**Enterprise Architect, Cloud Enablement & Digital Experience**  
*Feb 2012 – Present*  

I am one of six Enterprise Architects acting in a distributed CTO capacity. Each architect is aligned with a business portfolio servicing a set of technical solutions. I am aligned with customer experience, software development, integration, and cloud strategy. I often lead proof-of-concept development projects. I have established and scaled multiple agile delivery teams for cloud infrastructure, .NET development, and enterprise correspondence management. I specialize in providing enterprise directives and solutions for software development, SSDLC, CI/CD/CT, agile project management.

- I delivered transformative digital platforms including:
  
  - **Benefit Chatbot Charlie**: I created a conversational AI chatbot proof-of-concept. The chatbot is able to answer dozens of standard member questions by using real-time member information queried from back-end systems. Charlie's architecture used the following:

    - Angular SPA hosted on Azure App Service with .NET Core REST API
    - Azure OpenAI
    - Azure Document Intelligence: Unstructured data source
    - Azure AI
    - Azure Function App
    - Independent Health Member Portal Rest API: Real-time structured data source
    - I released a video about [Charlie's architecture](https://youtu.be/wVZYdv2xFuI?si=w9rBhcJYAXgcVEhW)
    - I released a video showing [Charlie in Action](https://youtu.be/J-9OxlRuvxk)
  
  - **FHIR**: I was the lead Enterprise Architect on Independent Health's first FHIR server deployed to support Patient Access Interoperability regulations. I helped design the following components:

    - PostgreSQL Schema to manage benefit, clinical, and consent data
    - ETL Integration to extract MDM and EDW member data for FHIR use
    - Duende IdentityServer / OAuth integration
    - ASP.NET Authorization and consent flows
    - HEALTHeLINK integration

  - **FHIR - V2**: I was the lead Enterprise Architect for updating Independent Health's FHIR solution and migrating it to Microsoft Azure

    - Migrate from Duende IdentityServer to Azure B2C and eventually  Microsoft Entra External Id
    - Migrate from HEALTHeLINK FHIR solution to Azure Health Data Services

  - **Member Center**: I created an Enterprise Architecture proposal to create an internal customer service interface called Member Center. Member Center is a web based portal SPA built on ASP.NET and Angular. It provides Independent Health associates from any department an easy and convenient way to find member information. It offers a full 360 view of member data from across multiple backend systems. It also provides a wide array of administrative actions that the user could invoke on behalf of the member. In 2022, work was started for Member Center and it was put into production that same year. It was deployed to a dedicated group of call center agents that help critically ill members enroll in specialty home nursing programs.

  - **Member Portal**: I led the transition from a fully outsourced member portal to an in-house developed, Microsoft .NET-based solution. I helped build a new development team, establish modern development processes, and architected the new portal platform for scalability and maintainability. The portal team continues to deliver new capabilities and features every sprint for over a decade since their inception.

  - **MyIH Mobile App**: I created an Enterprise Architecture proposal to allow Independent Health's .NET development team to create its own cross-platform mobile app. I used my personal experience developing mobile apps to create a proof-of-concept prototype to demonstrate platform capabilities to Independent Health leadership. The new mobile was developed and replaced the low quality app that had been developed by a third-party. The new mobile app has the following architectural components:

    - Apache Cordova: Recently converted to Capacitor
    - HTML, CSS, JavaScript - sharing components and design from Member Portal
    - I created a proof-of-concept and released a video of it [Mobile App Proof-of-Concept](https://youtu.be/Pr-FahmlgAc) - sorry for the low quality, I lost the original file.
    - In 2019, development of MyIH mobile app started and the first releases hit Google and Apple app stores in 2020. Since then, hundreds of new features have been released. Today I believe it may be the best mobile app from any insurance company.

  - **Member Action Plan**: I helped design a specialized campaign management system that tracked targeted campaigns across multiple communication channels. The design included a multi-dimensional state engine to track action items across various activities and dispositions. This enabled Independent Health to create specialized action list for members based on demographics, eligibility, and clinical information. Each action is individually tracked for each member until completion. Member Action Plan engages members across various communication channels :

    - Adobe Marketo  - email channel / mobile push
    - Member portal  - web channel
    - Oracle Siebel CRM  - voice channel
    - ECM - printed mail channel

  - **RedShirt Rewards**: I helped design a member rewards system that tracked member activity via Member Action Plan. Members receive gift card codes for completing actions on their personalized member action list.

    - Oracle Database
    - Java amd Apache Camel ESB services
    - [tangocard.com](https://www.tangocard.com/) API integration

  - **Gaps in Care**: I designed a web portal solution that enables providers to correct information for member NCQA HEDIS measures. Enabling providers to proactivity correct HEDIS measures ensured Independent Health's Medicare claims reimbursement rate.

    - Administration Portal - Internal business workflow tool for processing provider supplied corrections
    - Gap Correction Widget - Specialized web component designed to work within the provider portal to enable providers to submit corrections and supporting evidence
  
  - **Azure DevOps**: I transitioned Independent Health from Rally to Team Foundation Server over a decade ago. Since then, I have helped the organization become more agile and adopt CI/CD/CT and SSDLC practices. I helped them move from Team Foundation Server to Azure DevOps Services when it became available. I personally helped many teams transition their source code to Azure Repos and configure pipelines for automated building and deployment to on-premise and cloud environments. I also developed customized integrations for OpenText ALM that enables Azure pipelines call automated regression tests in ALM.

    - I created a video to promote Azure DevOps and explain how Azure DevOps works in an ITSM organization to help the organization meet SAFe and COBIT control objectives [ITSM Integration](https://youtu.be/OLR6cn0Db3s)

  - **Splunk**: After the introduction of a new claim processing system and enterprise service bus at Independent Health, infrastructure systems where consistently overwhelmed. I led a project to identify performance issues and resolve them. The first performance issue I identified was increased telemetry log volume being produced by new software. This new volume exceeded the IOPS available from underlying storage arrays. I designed a solution, and then led a project to deploy, a Splunk based solution using dedicate hardware that would direct telemetry traffic away from transaction processing systems.

    - Infrastructure consisted of dedicated hardware clusters running Splunk indexers
    - I developed a custom Log4NET and Log4J Splunk forwarder that used only TCP/IP to transport telemetry and consumed almost no IOPS.

  - **MyIH Alexa Skill**: I used my personal experience in creating Alexa Skills to help Independent Health design and deploy its own Alexa skill. The skill is able to:

    - Retrieve member deductibles
    - Locate the nearest Urgent care center
    - Recite the member's top benefits
    - Provide the member's Health Extras debit card balance
    - Link to [Alexa Skill](https://www.amazon.com/Independent-Health/dp/B072R5FF5B)  

  - **Greyhound ESB**: I worked with Information Risk Office, CIO, and Director of Application Delivery to lobby for the creation of an enterprise service bus based on Java and open source software such as Apache Camel. The solution enabled Independent Health to get off of IBM Message Broker and proprietary IBM hardware. I also recently lobbied for a new ESB called Airbus which would be based on native Azure cloud services and use modern Zero Trust security designs.

**CTG**  
Buffalo, NY  
**Software Architect – Independent Health SOA Architect**  
*Jun 2011 – Feb 2012*

I designed and implemented a fully integrated and automated document generation system for member correspondence using HP Exstream. I worked with multiple departments within Independent Health and gathered information about  corresponding generation, printing, and mailing. I created a new Enterprise Correspondence team to create a correspondence center of excellence. While I was working on the Core Administrative Program project, I recognized there was a need to organize solution architects and collaborate together. I founded the Architect's Round Table and organized frequent collaboration sessions between enterprise architects and dozens of solution architects. I helped organize architectural roadmaps and share them across the various project teams. This work led to Independent Health hiring me as a full-time Enterprise Architect.

**Meritain Health**  
Buffalo, NY  
**Principal Application Architect**  
*May 2009 – Apr 2011*  

I led a project to develop a new customer service interface for call center operations. The goal of the new interface was to reduce the complexity of servicing member calls. I led the team that gathered requirements and interviewed dozens of call center managers and service representatives. We used customer centric approaches to our design, sharing low-fidelity user interface mock-ups to solicit end-user feedback before development began. We frequently deployed pre-release versions into test environments to validate designs and operation.

The new customer service interface architecture consisted of:

- Microsoft Silverlight based user interface
- I developed a specialized Model-View-ViewModel layer to facilitate remote service calls and XAML data binding
- ASP.NET Rest API backend
- Integration to Meritain's enterprise service bus
  
When the new customer service interface was released.

- Required training for new representatives went from three weeks to two days
- Average call handle time went down 50%
- Quality went up by 75%

**Datatel (Ellucian)**  
Buffalo, NY  
**Software Architect, ActiveCampus eMarketing**  
*Feb 2003 – May 2009*  

I was the lead architect and software developer for ActiveCampus eMarketing 2.x. My duties encompassed:
  
- Building and mentoring .NET development teams
- Implement test driven development methodologies
- Implement agile development methodologies
- Collecting business requirements
- Documenting technical requirements and specifications
- Creating and keeping coding standards
- Object-to-relational database mapping
- Exception handling
- Security
- Unit testing

The ActiveCampus eMarketing 2.x application code base contained over 500,000 lines of code and its database schema consisted of over four hundred tables. The released application included tools for:

- Web-based content management
- E-commerce
- Event ticketing
- One-to-one marketing
- WYSIWYG web page editing

**Commerce Innovations Group**  
Buffalo, NY  
**Co-Founder / Architect**  
*Mar 2002 – Feb 2003*  

I was a co-founder and lead systems architect for Commerce Innovations Group. I specialized in building customized e-commerce software solutions based on the Microsoft .NET platform and technology. I offered complete solution development from project planning and requirements gathering to design and implementation. My clients included:

- Delaware North Companies:
  - Created e-commerce online gift stores in ASP.NET and Commerce Server 2000
- TD Garden Arena
  - Created e-commerce event ticketing website for premiere customers of the Boston Bruins and Boston Celtics in ASP.NET
- Kingdom Financial Holdings
  - Created “Western Union” style money transfer system for web-based orders using ASP.NET, SOAP and Window Forms based applications.

**LiquidMatrix**  
Orchard Park, New York  
**Chief Architect**  
*August 2001 – March 2002*  

I was the chief architect and software developer for ActiveCampus eMarketing 2.0. This product is based on Microsoft .NET platform. The product had an internet front-end based on ASP.NET and middleware components based on SOAP/Web Services and Microsoft SQL Server. As the lead architect and project manager my responsibilities included developing and delivering comprehensive training on .NET technologies for the development team. I designed new and innovative applications delivered as ASP.NET web-based interfaces and .NET desktop applications.

- Developed Object-to-Relational framework for ADO.NET, before NHibernate and Entity Framework were available.

**Reciprocal**  
Buffalo, New York  
**Software Architect Enterprise Management Systems**  
*January 1997 – July 2001*  

I spearheaded research, design, and implementation of a sophisticated datacenter enterprise management system for a heterogeneous network of SUN, Microsoft NT, and Nortel equipment using BMC Patrol and IBM Micromuse Netcool/Omnibus. I developed Knowledge Modules for proprietary applications using BMC Patrol agents and BMC Patrol PSL. The system centralized management of operations for three production datacenters and one disaster recovery site. I created software and documentation for the installation of new datacenters. I successfully led a four-week project to install a digital rights clearinghouse datacenter implementation for Mitsubishi in Yokohama, Japan.

- Check Point Firewall Administrator
- EMC Storage Administrator
- Sun Solaris Unix Administrator

**ClientLogic**  
Buffalo, New York  
**Chief System Software Architect**  
*January 1996 – January 1997*  

I was the designer and chief programmer of a fault tolerant and load balanced distributed system framework similar to Object Management Group’s CORBA. I was also the designer and chief programmer of internet order entry software based on ParcPlace’s Visual Wave. The success of this web-based order entry software led to the development of Client Logic’s Internet Commerce division. I helped design the first web-base systems for Client Logic customers including:

- Microsoft - Microsoft's first internet shopping chart application
- Traveling Software - technical support application
- Informix - technical support application
- IBM - OS/2 Warp product registration application back-office services
  - I invented the General Transaction Protocol (GTP) used in this solution

**ClientLogic**  
Buffalo, New York  
**R&D Manager of Electronic Services**  
*February 1994 – January 1996*  

I founded ClientLogic’s Interactive Voice Response application development group. Development languages included C, C++, VoiceTek Generations, and Informix Embedded SQL for C. The IVR system created a new million-dollar revenue stream for Client Logic.

Applications developed included:
  
- Call Tree Processing
- Technical Support Self Help
- Dealer Locator Fax Back
- Order Status
- Automated Order Entry
- Automated Customer Account Management
- Super NES Online Gaming Personalization and Parental control back-office for Catapult Entertainment [XBAND](https://en.wikipedia.org/wiki/XBAND)
- Interactive Television back-office for [Zing Interactve System](http://www.faqs.org/rulings/rulings1995HQ957321.html)
- Coined the term "ClientLogic in a can" to promote the development of a standard API for partner integration.

**O.A . Systems**  
Buffalo, New York  
**Senior Network Engineer / Repair Depot Manager**  
*March 1992 – February 1994*  

I installed and supported Novell and Windows NT computer networks for local hospitals, town government offices, law firms, and various small businesses. I specialized in troubleshooting and solving difficult hardware and software problems. During this time, I also managed an electronic repair depot where I repaired computers, monitors, and printers.

---

## **Technical Proficiencies**

**Languages & Frameworks:**  
C#, C++, C, SQL, JavaScript, TypeScript, Node.js, Angular, React, HTML/CSS, ASP.NET, Playwright, AI/LLM (OpenAI)

**Tools & Platforms:**  
Visual Studio, Visual Studio Code, Azure DevOps, SQL Server, PostgreSQL, Oracle, Azure Cloud and AWS Cloud

**Process & Methodologies:**  
Trained in Leading SAFe, Certified Scrum Master, SSDLC, CI/CD/CT, Agile, XP, RAD, Test-Driven Development, Relational & Object-Oriented Design

---

## **Certifications**

[AWS Certified Cloud Practitioner](https://www.credly.com/badges/23cb0723-931d-4e64-b663-94690f8b77a9/public_url)

[Microsoft Certified: Azure Fundamentals](https://learn.microsoft.com/api/credentials/share/en-us/VincentMiceli-8720/A080F7C08668E77?sharingId)

---

## **Hobby Projects**

**bitdog.io**
I created bitdog.io as a hobby project to learn more about home automation, AI voice assistants, and mobile development.
  
- Published one of the first Alexa Skills on Amazon’s platform. There were a total of ten at the time.
- Created a home automation hub based on Node that could run on Raspberry Pi.
- [Blog](https://cookbook.bitdog.io)
- [Bitdog Hub Video](https://youtu.be/KvEhGHpWIg8)
- [Bitdog Alexa Skill Integration Video](https://youtu.be/bTyWyyuCeeY)
- Link to [Alexa Skill](https://www.amazon.com/Bitdog-Home/dp/B072K6TVKD)
- [Bitdog Google Home Integration Video](https://youtu.be/fluZOkQmAs0)

**Drone Mower**
I am working on a fully automated robot to mow my excessively large lawn.

- [Prototype Rover Video](https://youtu.be/2xoTmh7zPiI)
- [Little Mower Video](https://youtu.be/frFU9pNqIiI)
- [Big Mower Video](https://youtube.com/shorts/XBVs-bLQMFM?feature=share)

**Restraining Bolt**
After a robotic mower ran away, I created a specialized microcontroller based solution to monitor the navigation computer for any errors. If any navigation errors are detected, the robot is shutdown.

- [Open source project](https://github.com/bitdog-io/restraining_bolt)
- [Testing Video](https://youtu.be/QM2f_M2HsgQ)

**Internet Radio Device**
I created an ESP32/Arduino device to stream internet radio
  
- Used SquareLine Studio to configure LVGL user interface
- [User Interface Video](https://youtu.be/TLgxNaJ1kg0)
- [Code](https://github.com/vincemic/ESP32-S3-InternetRadio)

**Ghostbusters Proton Pack**
I wanted to create interactive art with steampunk style.

- ESP32/Arduino control
- Smoke, steam, lights, and sound special effects
- [Pack Overload Video](https://youtube.com/shorts/v15teEuBYOc?si=-qfatj2tpyOcYJWo)  

**Splunk Voice**
This is a project I created for a Splunk Hackathon that enabled mobile access to Splunk information
  
- I developed on Windows Phone using Cortana voice assistant for hands-free information access
- I create special Splunk integrations to enable query execution from mobile app
- [Mobile App Video](https://youtu.be/SWGTSLgeVI4?si=rfV6gRL7FhOT2IOf)

---

## **Education**  

**Born with technology in my DNA**, Buffalo NY  
"Life-long learner, 1969"  

- Electronic hobbyist starting at age 8
- Taught myself Basic on TI/99 4A at age 12
- Taught myself 6502 Assembler on Commodore 64 at age 14
- Building electronic projects using microcontrollers at age 18

**Erie Community College**, Orchard Park, NY
*Computer Science, 1988*  

- Left program when professor wouldn't let me use my home computer to finish Pascal programming assignments. ECC's mainframe was slow and over utilized. It often took hours to complete simple assignments which would take only minutes on my Commodore 128.

**Bryant & Stratton Business School**, Clarence, NY  
*Electronic Technology, 1991 — GPA: 4.0*  

- Left program with only a half credit remaining towards an associates degree for first job repairing computer equipment.
