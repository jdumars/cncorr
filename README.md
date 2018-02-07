# Cloud Native Computing Organizational Readiness Review

## Introduction

This document provides an organizational readiness self-assessment framework for companies wishing to migrate to Cloud Native Computing. This review ensures that the technical and business alignment of the organization reflects DevOps and Cloud-Native best practices. Where gaps exist, the reviewer should seek effective ways to remediate and increase organizational efficacy, trust, and manageability. If optimally organized, your company will yield improved retention, employee satisfaction, and agility.

The foundation for these practices comes from multiple sources including the experiences of the author, Jaice Singer DuMars, the annual State of DevOps reports, industry research and the practices of highly-successful technical organizations.  

## Managing the Technology Lifecycle

Migrating a company to cloud-native application delivery requires a very different approach to all phases of technology management.  No part of the business or engineering organization is untouched by the changes, but every one of them benefits.  A high-performing technology organization provides tremendous value.  For example, employees at such companies are 2.2 times more likely to recommend their workplace to friends and colleagues.  The ramifications of that one benefit extend to every corner of the business, no matter how large the enterprise.  Additionally, high-performing organizations experience 3x lower failure rates for changes introduced into customer-facing environments, 24x faster recovery times and near exponential improvements in lead times and deployment frequency.  These environments are also characterized by high levels of peer and organizational trust, as they are optimized for predictable and repeatable results, both technologically and organizationally.

In terms of the technology lifecycle, strong relationships between business units and technology silos becomes even more important than with traditionally-deployed software since the lag between ideation and delivery is significantly decreased.  Many parts of the organization may have to change the way they operate in response.  For example, traditional program and project management is typically focused on waterfall processes, even where Agile has a strong foothold in development.  This is because handoff points between product management, operations, security, compliance, architecture, marketing and legal are not smooth enough to allow for rapid, iterative deployment.  For this reason alone, many enterprises shrug off cloud computing for core business lines, limiting it to new or emerging products to experiment with.  As a result, benefits do not necessarily spread across the company, and a mature, cloud-focused suite of processes and skillsets never develops.  Some enterprises have misguidedly implemented "DevOps Teams" or DevOps as a job description to address gaps between traditional engineering organizations and cloud-optimized ones.  This is not the answer, as will be covered in more detail later.

## Organizational Review Process

Depending on the size and complexity of the organization, meetings and interviews should be held with individuals and teams.  Representation will be required from all parties who have material involvement in the line of business moving to cloud-native computing.  Ideally, executive management will also participate, as top-level buyin has a significant impact on the overall success of the initiative.  

The questions in the assessment must be asked of the primary team affected, as well as incidentally from other groups so a rounded view of perception can be assembled.  For example, Information Security teams may feel very prepared for cloud computing, but software engineers may feel security teams are not.  Where conflicting or polar opposite views exist, additional teams or individuals should be consulted to better refine where trouble spots may develop.   The aim is not to impugn anyone's efforts, but to instead limit risks by identifying and mitigating them from the outset.  

Another important, and less qualitative strategy is to run retrospectives across teams or groups to get more unfiltered feedback on the current state.  It is not uncommon for whomever conducts the analysis to receive a large volume of negative feedback since they are considered a safe harbor for that information, and may help institute change.  This is an absolutely critical part of the process and may provide much value above and beyond the cloud implementation.  

## Assessment Scoring

The assessment is based on a 5 point scale with 1 being least true and 5 being most true.  The scoring is subjective and based on observations gathered during the organizational review.  Assessment questions are stated as facts. If the fact is rated a 5, then it will need little or no work.  If it is rated a 1, it will require the most work.  Urgency and severity can be assigned at the discretion of the reviewer if particular areas are rated universally low.

## Assessment Statements

## 1. Program and Project Management

Program and project management is the conduit between business strategy and execution.  Because cloud-native technologies remove blockages from the value stream, it can be difficult for organizations to manage iterative project delivery.  Quarterly "big room" Agile planning events may be necessary to untangle dependencies and align stakeholders, departments, and engineering teams.   Also, a key success factor is participation of delivery teams in plan generation since a tightly-coupled feedback loop encourages trust and limits waste.  

<table>
  <tr>
    <td>1.1</td>
    <td>Quarterly planning (or rolling planning) events occur to align technology implementation with business strategy.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.2</td>
    <td>Project managers use Agile, Lean or comparable practices to ensure early feedback and adjust requirements accordingly.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.3</td>
    <td>Programs with software components or technology focus have active, regular input from all stakeholders including operations, software engineering, compliance, architecture and security.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.4</td>
    <td>Requirements are vetted with subject matter experts before being finalized and are adaptable to information gathered while the project is underway.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.5</td>
    <td>A value stream map has been created for the delivery of program or project deliverables.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.6</td>
    <td>Flow between project handoff points and silos is smooth and does not delay projects.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.7</td>
    <td>Funding is allocated as a budget, not an estimate with program and project decisions optimized to best utilize the budget.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.8</td>
    <td>Software projects are structured so delivery can happen iteratively, not necessarily at the end of the project.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.9</td>
    <td>Strategic themes behind projects and programs are clearly communicated to not only stakeholders but also all project participants.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.10</td>
    <td>Project prioritization is accomplished through a formal exercise such as "weighted, shortest job first".</td>
    <td></td>
  </tr>
  <tr>
    <td>1.11</td>
    <td>Corporate programs and projects use Kanban or other easy-to-understand way to radiate status to both senior leadership and stakeholders.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.12</td>
    <td>Decision-making is decentralized wherever possible.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.13</td>
    <td>Project value flow is closely monitored against customer demand.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.14</td>
    <td>Business cases are only as detailed as they need to be to deliver customer value.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.15</td>
    <td>Work breakdown structure is focused on estimating complexity and Agile estimation.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.16</td>
    <td>Decisions are made with varying levels of certainty, acknowledging that the further out delivery is, the less certain the outcome.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.17</td>
    <td>Projects use objective, fact-based measurements to determine progress, not arbitrary milestones.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.18</td>
    <td>Project governance is focused on identified key performance indicators.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.19</td>
    <td>Qualitative data is gathered throughout the life of the project to help inform and improve future projects.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.20</td>
    <td>There is a high level of trust between the business and program/project managers.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.21</td>
    <td>Business decisions around technology are primarily based on value delivery.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.22</td>
    <td>Customers (not just stakeholders) of programs and projects are clearly identified and consulted regularly during the progression of work.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.23</td>
    <td>Program and project-level retrospectives are held regularly.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.24</td>
    <td>The organization handles change smoothly as part of normal operations.</td>
    <td></td>
  </tr>
  <tr>
    <td>1.25</td>
    <td>The governance model around cloud computing balances agility with risk management.</td>
    <td></td>
  </tr>
</table>


## 2. Product Management

The product organization is the "why" behind everything that engineering teams do.  If there is not a steel thread running between corporate strategy, product, and engineering, it can be a serious inhibitor to success.  Product is the voice of the customer in every important conversation.  Cloud computing presents the product organization with both an opportunity and a challenge: rapid delivery of customer value.  Their job is to balance agility with non-disruptive delivery, as well as ensure that what got delivered is what customers actually want.  This includes both internal and external customers.  Additionally, operations and DevOps must become client-facing engineering organizations as well, complete with product representation.

<table>
  <tr>
    <td>2.1</td>
    <td>Customers of software projects are well understood.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.2</td>
    <td>Requirements are limited as much as possible, instead focusing on value delivery.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.3</td>
    <td>The "voice of the customer" is always present in design, implementation, and delivery decisions.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.4</td>
    <td>Product management has product staff (product owners) embedded directly in development and delivery teams to ensure their backlog is organized in accordance with strategy and commitments.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.5</td>
    <td>Product backlog and prioritization is highly visible to stakeholders, participants, and executive management.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.6</td>
    <td>Customers are part of planning events.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.7</td>
    <td>Product managers and product owners attend engineering retrospectives.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.8</td>
    <td>The feature release process is well-understood and flexible enough to accommodate continual product updates.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.9</td>
    <td>Product managers leverage rapid delivery capabilities for business advantage.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.10</td>
    <td>Product roadmaps are in a state of continual refinement in response to customer feedback.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.11</td>
    <td>Product scope is regularly compared to the understood velocity of delivery teams.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.12</td>
    <td>Features can be isolated and presented selectively to customers programmatically.  </td>
    <td></td>
  </tr>
  <tr>
    <td>2.13</td>
    <td>Change is expected and adjusted for at regular planning events.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.14</td>
    <td>The organization handles change smoothly as part of normal operations.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.15</td>
    <td>Program vision and roadmaps are clearly understood by Product Management, as is the role of product efforts in the greater strategy.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.16</td>
    <td>Product management effectively communicates the program vision and roadmap to delivery teams.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.17</td>
    <td>Product value is clearly understood by participants, stakeholders and customers.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.18</td>
    <td>Product Management drives the overall release cadence and increments.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.19</td>
    <td>Product Managers and Owners attend engineering demos.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.20</td>
    <td>Product teams have retrospectives after every significant customer delivery.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.21</td>
    <td>Product teams work directly with release management to coordinate stakeholder progress on budget, release strategy and readiness of their specific features.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.22</td>
    <td>Delivery teams trust product management to drive good technical decisions.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.23</td>
    <td>Product teams trust delivery teams to accurately estimate their efforts and consistently deliver.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.24</td>
    <td>At the software engineering level, features are broken down into small-point user stories that can be completed in a single sprint or less.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.25</td>
    <td>Work in Progress (WIP) is limited on all delivery teams, and no team is required to exceed the WIP limit except under extraordinary circumstances, and only for very short periods of time.</td>
    <td></td>
  </tr>
  <tr>
    <td>2.26</td>
    <td>Product owners are fully versed in and practice Agile/Lean methodologies.</td>
    <td></td>
  </tr>
</table>


## 3. Architecture

Enterprise architecture is vested with the challenge of maintaining long-term vision while actively exploring innovation.  Because architects are typically seasoned technology and process veterans, they are able to temper desire for change with a need for consistency.  Their role in cloud computing is critical because they must fully embrace the paradigm in order to reap the most value from it.  If they are ambivalent about the cloud, then they represent a risk to viability in the organization.  There may be serious resistance in architecture, specifically, because it upends so many traditional paradigms.  The common resistances are cost, reliability and portability, which are not reflective of the current maturity of cloud providers.

<table>
  <tr>
    <td>3.1</td>
    <td>Enterprise architecture is established as the governing body for strategic technical decisions.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.2</td>
    <td>Architectural standards, guidelines and requirements comply with the best practices of 12-factor application development.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.3</td>
    <td>Service-oriented architecture is the expected pattern for application development.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.4</td>
    <td>When evaluating architectural decisions, preference is weighted toward cloud-based solutions.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.5</td>
    <td>Container orchestration solutions are designed with partnership between architecture and engineering.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.6</td>
    <td>Architects have significant, current experience with containerization.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.7</td>
    <td>Architects have significant, current experience with cloud computing.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.8</td>
    <td>Enterprise architecture is an active stakeholder in product decisions.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.9</td>
    <td>Technology strategy is aligned at the architecture level with business strategy.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.10</td>
    <td>Continuous integration and delivery is a key part of the architecture roadmap.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.11</td>
    <td>Architectural decisions and projects are rolled out incrementally in accordance with Agile, Lean or comparable best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.12</td>
    <td>Enterprise architects regularly observe day-to-day engineering activities to get a better understanding of real-world impacts of architectural decisions.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.13</td>
    <td>Service catalogs exist such that SOA consumers and providers are easily determined and documented.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.14</td>
    <td>Operational data is fed back into architectural planning to address long-term scale issues.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.15</td>
    <td>Total cost of ownership (TCO) is understood for cloud computing.</td>
    <td></td>
  </tr>
  <tr>
    <td>3.16</td>
    <td>There is a strong and regularly reinforced line of communication between architects, software engineering, and technical operations.</td>
    <td></td>
  </tr>
</table>


## 4. Software Engineering

Software engineering is the engine behind the idea.  These groups are heavily affected by cloud computing because it drives decisions all the way down to how they write and maintain code.  Writing containerized microservices is a completely different mindset, skillset and experience than constructing traditional monolithic applications.  The pivot to cloud-based compute resources may represent a major challenge from a hiring perspective.

<table>
  <tr>
    <td>4.1</td>
    <td>Applications conform to 12-factor best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.2</td>
    <td>Software source control is used for every application.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.3</td>
    <td>Deployment artifacts are immutable.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.4</td>
    <td>Application scaling is strictly horizontal. </td>
    <td></td>
  </tr>
  <tr>
    <td>4.5</td>
    <td>There is an expectation that applications can be delivered to production environments programmatically.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.6</td>
    <td>Application testing and delivery is automated.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.7</td>
    <td>Engineering teams practice test-driven development.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.8</td>
    <td>Testing teams leverage Agile, Lean or comparable best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.9</td>
    <td>Development environments provide an accurate reflection of target/production environments.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.10</td>
    <td>Application-dependent services are differentiated via configuration value.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.11</td>
    <td>Service discovery is ubiquitous.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.12</td>
    <td>A service catalog exists.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.13</td>
    <td>Rollback and more ideally, rollforward, are are expected in all application deployments.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.14</td>
    <td>Semantic versioning is used on all projects and deployments.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.15</td>
    <td>There is a strong and regularly reinforced line of communication between software engineering and technical operations.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.16</td>
    <td>Software engineers have a clear understanding of business, product and release strategy.</td>
    <td></td>
  </tr>
  <tr>
    <td>4.17</td>
    <td>Product owners are embedded in engineering teams.</td>
    <td></td>
  </tr>
</table>


## 5. Quality Assurance and Software Testing

Testing and validation in cloud environments is relatively different than in traditional monolithic, datacenter environments.  In many ways, testing is one of the highest beneficiaries of cloud-native applications since they are built with testing in mind, and can be spun up and down quickly and easily.  Dependency management is also much better since 12-factor applications should be stateless.  In full CI/CD environments, challenges may shift to maintaining build systems, and this can become a serious burden if not carefully managed.  Test flakes can be the bane of quality engineers.

<table>
  <tr>
    <td>5.1</td>
    <td>Software testing is accomplished completely through automation. </td>
    <td></td>
  </tr>
  <tr>
    <td>5.2</td>
    <td>Once all tests pass on code, it can be deployed without human intervention.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.3</td>
    <td>Testing teams leverage Agile, Lean or comparable best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.4</td>
    <td>Test environments are as closely analogous to production as possible.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.5</td>
    <td>Cloud-specific failure domains are regularly tested.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.6</td>
    <td>QA and testing engineers are experienced with cloud-based application deployments.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.7</td>
    <td>QA and testing engineers participate in up-front project/product planning.</td>
    <td></td>
  </tr>
  <tr>
    <td>5.8</td>
    <td>Global application test coverage exceeds 90%</td>
    <td></td>
  </tr>
  <tr>
    <td>5.9</td>
    <td>Continuous integration testing provides real-time status of application code branch deployability.</td>
    <td></td>
  </tr>
</table>


## 6. Deployment/Release Management

In scaled Agile implementations, the release management process is a critical component of seamless delivery because it ties all of the actors together to ensure unblocked flow of value to the customer.  This should not be a heavyweight process.  It should be optimized through automation wherever possible.  Human oversight should be focused on what value is being delivered, not how.  

<table>
  <tr>
    <td>6.1</td>
    <td>Applications can be continuously deployed programmatically.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.2</td>
    <td>Deployment management is included in program, project and product planning.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.3</td>
    <td>Non-delivery stakeholders such as marketing and legal participate in the release management process.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.4</td>
    <td>The deployment and release management team is aware of and follows the release governance model.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.5</td>
    <td>After major releases, deployment and release retrospectives occur with participation of the full release team.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.6</td>
    <td>Business stakeholders have an easy and effective way of viewing release status at all times.</td>
    <td></td>
  </tr>
  <tr>
    <td>6.7</td>
    <td>Release cadence is not limited by the release management process, but rather governed by it.</td>
    <td></td>
  </tr>
</table>


## 7. Operations

Traditional technical operations may offer some resistance to cloud computing since it represents a completely new paradigm.  While many skills overlap between datacenter operations and cloud operations, many tasks such as provisioning are obviated.  A risk among traditional operations adopting cloud-native computing is the tendency to port datacenter practices over.  For example, there may be attempts to use traditional configuration management practices inside of containers instead of relying on 12-factor practices.  Also, network operations can be challenged by the use of overlays and policy agents.  Because operations is arguably the most impactful to customer satisfaction (downed systems are the number one cause of customer exodus), having a product owner and running operations as a delivery team is critical.  Cloud system agility can be completely blocked by a "waterfall" operations group.

<table>
  <tr>
    <td>7.1</td>
    <td>Operations staff responsible for supporting production and other customer-facing environments are included as stakeholders in every phase of the release process.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.2</td>
    <td>New infrastructure is deployed iteratively in the same manner as code.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.3</td>
    <td>Infrastructure spin up and spin down is code-driven.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.4</td>
    <td>All environments are under the auspices of version control.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.5</td>
    <td>Operations follows Agile/Lean/comparable best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.6</td>
    <td>Monitoring and alerting is seamless between container, orchestration, cloud and non-cloud systems.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.7</td>
    <td>Cloud utilization and efficiency is actively monitored and reported on to financial stakeholders.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.8</td>
    <td>Production change management is enforced programmatically.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.9</td>
    <td>Cloud quota management is reviewed on a regular cadence to ensure limits do not prevent deployments.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.10</td>
    <td>Production environments leverage cloud best practices for redundancy and high availability.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.11</td>
    <td>There is a strong and regularly reinforced line of communication between operations and software engineering.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.12</td>
    <td>Manual operations on production assets is strictly limited or completely obviated by automation.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.13</td>
    <td>All routine tasks are automated.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.14</td>
    <td>Operations engineers have significant, current, relevant experience managing infrastructure, applications and system dependencies in the cloud.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.15</td>
    <td>Operations leadership advocates for and promotes use of containerization.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.16</td>
    <td>The operations organization leverages DevOps best practices.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.17</td>
    <td>Operations staff are included in project and program inceptions.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.18</td>
    <td>Technical operations is fully represented in Enterprise Architecture.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.19</td>
    <td>Operational requirements are clearly communicated to all project and program stakeholders.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.20</td>
    <td>Lead time for cloud infrastructure delivery is minimal or ideally trivial.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.21</td>
    <td>Operations staff hold regular retrospectives.</td>
    <td></td>
  </tr>
  <tr>
    <td>7.22</td>
    <td>Operations has a product owner.</td>
    <td></td>
  </tr>
</table>


## 8. Site-Reliability Engineering (SRE) or comparable

Groups responsible for maintaining infrastructure uptime are faced with one of the most challenging aspects of cloud computing since they must rely almost completely on self-service tools, automation, log aggregation, and documentation provided by engineering teams.  Making sense out of service-oriented architectures is not straightforward.  Also, direct access to systems may not be available, so empirical data can be hard or impossible to obtain.  From the organizational perspective, SREs are a radically different group of people than traditional support teams.  They need the engineering, troubleshooting, and testing skill sets.  They must have a thorough understanding of the entire technical landscape, as well as how all the pieces fit together to provide any given application full functionality.

<table>
  <tr>
    <td>8.1</td>
    <td>SREs receive actionable support documentation from software engineering and operations.</td>
    <td></td>
  </tr>
  <tr>
    <td>8.2</td>
    <td>SRE teams have clear supportability requirements for newly-crafted software or architecturally-changed existing applications.</td>
    <td></td>
  </tr>
  <tr>
    <td>8.3</td>
    <td>SREs are fluent in supporting and troubleshooting cloud environments.</td>
    <td></td>
  </tr>
  <tr>
    <td>8.4</td>
    <td>SRE is represented in project and program inceptions.</td>
    <td></td>
  </tr>
  <tr>
    <td>8.5</td>
    <td>SREs have a proven track record of appropriate issue and outage escalation.</td>
    <td></td>
  </tr>
</table>


## 9. Incident Response and Escalation

Troubleshooting microservices, containerized applications and massive orchestration environments is a completely new world for many engineers.  Even developers who construct the applications and services may not understand how to properly diagnose and troubleshoot errors.  As such, it's critical path for everyone involved in the process to be adequately trained, informed on changes, and part of the full deployment lifecycle.  It's not good enough to simply hand off a "run book" to operations or reliability engineers.  There is a tremendous learning curve, and it is measured in minutes of downtime. 

<table>
  <tr>
    <td>9.1</td>
    <td>The incident response and escalation procedure for cloud applications is documented and fully understood by all actors in the process.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.2</td>
    <td>Service Level Agreements and Operational Level Agreements underlie the incident management process such that uptime is bound to the lowest uptime dependency -1.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.3</td>
    <td>Production support is shared across the entire engineering organization.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.4</td>
    <td>Self-service and automation are key tools in the incident resolution process.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.5</td>
    <td>System uptime is calculated against the 90th percentile or better.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.6</td>
    <td>Disaster recovery and business continuity programs are documented and fully tested on a regular cadence.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.7</td>
    <td>Failover strategies include multi-cloud implementations.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.8</td>
    <td>Product teams and customer relationship/account managers are included as part of the incident resolution process.</td>
    <td></td>
  </tr>
  <tr>
    <td>9.9</td>
    <td>Retrospectives are held after every top-severity service disruption.</td>
    <td></td>
  </tr>
</table>


## 10. Security

Security should never be an afterthought in a cloud-native environment.  With the agility of rapid iteration also comes the near constant introduction of vulnerabilities.  Every system, process and design decision must put security front and center.  Also, the working relationship between the security and engineering organizations must be extremely strong and collegial.  When tension exists between these groups, it is very disruptive.  It's also crucial for security to be involved in product decisions since most meaningful applications are data-driven, and data is the dominion of security engineering.

<table>
  <tr>
    <td>10.1</td>
    <td>Cloud hosts are hardened according to applicable regulatory best practices, guidelines and requirements.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.2</td>
    <td>Access controls are delegated and maintained through a centralized identity management system.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.3</td>
    <td>Role-based access control defines a least-privilege model for individuals, systems, orchestration and applications.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.4</td>
    <td>Securing systems in cloud environments is well understood by software engineers.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.5</td>
    <td>Securing systems in cloud environments is well understood by operations engineers.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.6</td>
    <td>Containerized applications are scanned for vulnerabilities as part of the release process.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.7</td>
    <td>Security scanning is automated and run at a regular cadence.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.8</td>
    <td>Patching of systems, container base images and orchestration components is automated as much as possible within the constraints of service level agreements.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.9</td>
    <td>Orchestration environments are regularly assessed for vulnerabilities independent of release cadences.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.10</td>
    <td>Security engineers are part of the initial project/program inception.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.11</td>
    <td>Security leadership is a key stakeholder in the release process.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.12</td>
    <td>CI/CD pipelines are considered secure by the security organization.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.13</td>
    <td>The production infrastructure mirrors applicable design recommendations from the cloud provider.</td>
    <td></td>
  </tr>
  <tr>
    <td>10.14</td>
    <td>Container hosts have locked down the container runtime to least privilege.</td>
    <td></td>
  </tr>
</table>


## 11. Compliance

No matter the industry, regulatory compliance will play a part in how systems are designed and maintained, as well as how data flows through.  Having a strong partnership between auditors and delivery teams will make success in the cloud much easier.  Successful organizations do not fight compliance, but instead embrace it.

<table>
  <tr>
    <td>11.1</td>
    <td>The cloud implementation is considered regulatorily compliant by the appropriate auditing agency, department or third party.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.2</td>
    <td>The regulatory framework applied to production infrastructure has explicit accommodation for containerized and cloud environments.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.3</td>
    <td>Production cloud environments are fully compliant with corresponding regulations.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.4</td>
    <td>All cloud environments provide full audit trails for regulatorily-covered actions.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.5</td>
    <td>Compliance monitoring is programmatic and accounts for ephemeral workloads and systems.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.6</td>
    <td>There is a strong partnership between engineering and auditors.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.7</td>
    <td>Compliance is not a burden for daily operations.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.8</td>
    <td>Compliance overhead for new applications and services is minimal due to automated controls.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.9</td>
    <td>There is an efficient and well-understood remediation process for findings.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.10</td>
    <td>New controls needed are not instituted on a one-off basis, but instead programmatically and systemically.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.11</td>
    <td>Engineering is proactive in determining compliance for new applications, services and systems.</td>
    <td></td>
  </tr>
  <tr>
    <td>11.12</td>
    <td>Container orchestration as a strategy is well-understood by auditors.</td>
    <td></td>
  </tr>
</table>


## 12. Other parts of the business

A cloud-native organization extends to every corner of the business.  Talent acquisition and retention is a major concern, as is the landscape around open source software in general.  Sales and marketing organizations can use the cloud as a key differentiator.

<table>
  <tr>
    <td>12.1</td>
    <td>Recruiters understand the specific skill sets necessary to staff a cloud-centric engineering organization.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.2</td>
    <td>The business understands the value proposition of Agile/Lean/comparable practices and is seeking ways to expand them.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.3</td>
    <td>Compensation for engineering staff is in line with the market.  </td>
    <td></td>
  </tr>
  <tr>
    <td>12.4</td>
    <td>Incentives for engineers include remote work, skills enrichment and flex time.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.5</td>
    <td>Engineers are encouraged to work on open source and community projects.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.6</td>
    <td>Decision-making is as distributed as possible.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.7</td>
    <td>All retrospectives are conducted with a discovery mindset not for blame or admonishment. </td>
    <td></td>
  </tr>
  <tr>
    <td>12.8</td>
    <td>Kaizen (the spirit of continuous improvement) is part of every process.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.9</td>
    <td>Sales teams understand the competitive advantage of cloud-native application delivery and use it in pitches.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.10</td>
    <td>Marketing teams understand the competitive advantage of cloud-native application delivery and use it in marketing campaigns.</td>
    <td></td>
  </tr>
  <tr>
    <td>12.11</td>
    <td>Legal staff understand the challenges and opportunities associated with creating and maintaining open source software.</td>
    <td></td>
  </tr>
</table>
