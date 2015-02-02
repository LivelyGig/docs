# LivelyGig

_Decentralized Task Management and Employment Protocol_

Author: Ed Eykholt  
v0.1   
2014-02-01  

There is a healthy marketplace for solutions to match up employers' requirements for digitally delivered content with available talented individuals who create and deliver solutions. For example, Freelance.com's 2013 revenue was 44.7 M€, and there are several similar sites for gigs. These service providers can enjoy healthy commissions, yielding up to a 10% profit margin. There is even more upside in this market as the network effect of increased adoption takes hold, especially with a new solution that will take advantage of the latest technology for distributed applications and payments.

Let's first look at the primary players in this ecosystem. Prospective employees using this type of service often want to freelance for various reasons and to get fairly paid for interesting work. These individuals accumulate reputations for their ability to deliver content and that justify their rates. On the employer side, the need for part-time work is often part of a larger project. An employer's momentum is sometimes slowed when they can't quickly find great talent, especially when trying to find someone they can trust with an abstract task, someone with the ability to clarify and make progress in spite of ambiguities. Employers can accomplish more when they can draw from a large reputation-based talent pool. Projects can also be accelerated with a practical task management solution and connected ecosystem that supports delegation of tasks.

The LivelyGig protocol will provide for peer-to-peer digital job boards and task management systems that leverage Bitcoin's technology and foster a new employment ecosystem. LivelyGig supports the right to work without an intermediary.

While there exist many excellent software solutions for managing tasks and for job sourcing, there is still an opportunity to leverage the latest technology and deliver even better solutions. With the emergence of digital currencies, technology access tokens, blockchain technology, peer-to-peer networks, and smart contracts, there is an opportunity to create a new platform for a digital job ecosystem that is global in scale. A new solution can better align the interests of employers and employees (including full time, contractors, and freelancers), with no intermediary friction.

LivelyGig is a proposed solution that at its heart is an open-source task management protocol that provides standard task-management workflow contracts via its peer-to-peer nodes and clients, including a client UI, websites, and solutions built atop of its APIs. LivelyGig will provide uniquely integrated features to provide talent sourcing, delegated work, immediate bitcoin payment for completed work, and an immutable audit trail of those processes.

LivelyGig's open API will enable integration with existing project management, task management, and job search solutions, increasing each of these solution's value proposition. These systems collectively will create a bitcoin-centric ecosystem for jobs large and small. In addition, work, deliverables, payments, and auditability can be made public at the option of the employer, which provides needed transparency in the case of non-profit, government, and government-sponsored organizations. Optionally, information can be exchanged between an employee and employer as required for compliance to government regulations. Hourly based rates or fixed-price payment agreements can be pegged to non-bitcoin currencies.

# Example Usage

Pam, a project manager, needs to have her company's web site updated to be better formatted for smartphones. However, she doesn't have ready access to the needed skills within her organization. She registers with and logs on to the LivelyGig web site. She creates a project definition with a task to update the web site. She sets the target budget, terms, required skills, and timeframe for the task and chooses to advertise the job.

On a LivelyGig-enabled freelance web site, a software developer Andrey who has the matching skills sees the advertisement, opens up a conversation with Pam, and they negotiate a clarification to the task along with payment terms. Andrey and Pam finalize their agreement using LivelyGig, which records a smart contract. As part of the agreement Pam and Andrey put some of the bitcoin payment into escrow via the LivelyGig protocol.

Andrey, who has been reviewing his progress with Pam, delivers the final updated web site and indicates completion on the LivelyGig web or client UI. Pam receives notification and approves the delivery. The LivelyGig protocol co-signs the pending payment transaction in escrow, and this action provides bitcoin payment immediately to Andrey. LivelyGig provides both Pam and Andrey with reputation points as part of the task completion, which helps in their ability to more readily secure future work with less escrow requirement, especially for large tasks.

LivelyGig doesn't share any details about Pam's project unless she chooses. Pam's and Andrey's identities, locations, and other data are kept private, unless they choose or require each other to share those details.

Many other options are available to project managers like Pam and talent like Andrey for how they choose to work together. These options include the amount of escrow required and a contract expiration date that if exceeded would trigger a refund of escrow.

# General Use Cases

Many projects can benefit from an integrated environment that helps project teams find the optimal contract and freelance talent needed to complete a set of deliverables. The description of a deliverable might range from vague epics, to detailed specifications that have independently verifiable solutions, to very simple tasks. We'll refer to any unit of required work as a task.

Once defined, a task can be immediately assigned to an existing full-time project team member or can be offered to contractors or freelancers. Task agreements can be initiated by a project manager via a talent search or by a resource once a task has been offered and advertised.

For each employer-employee relationship, LivelyGig records the equivalent of an employment agreement, or a "gig", which sets the context and defaults for the employee's tasks. LivelyGig's task workflow and use of payments in bitcoin ensure efficiency and fairness.

LivelyGig's solution scales from a simple task-assignment tracking that can be maintained completely via LivelyGig's web or client UI, to a complex project plan managed by an integrated best-in-class project management system.

User participants in the ecosystem include project managers, full-time project participants (pre-defined resource pools), contracting firms, contractors, staffing firms, and freelancers.

Access to the LivelyGig protocol is via its web UI, client UI, or via any number of integrated 3rd party solutions leveraging LivelyGig's protocol via its API.

Projects can run as publicly or privately as desired. In any case, a hash-based proof-of-process audit trail is created. The audit trail is especially appealing for government, government-sponsored, and non-profit projects, since this will increase accountability through transparency.

# Ecosystem

The extended LivelyGig ecosystem, with integration partners, includes the following:

- The LivelyGig protocol provides smart contracts for tasks and interfaces to it. The protocol enforces the contract's terms and workflow. Upon task delivery and acceptance, LivelyGig handles payment transactions and reputation crediting.
- Project managers create tasks that can be outsourced (defining work, posting jobs, advertising, sourcing contractor or independent freelance talent, managing agreements).
- Project Management solutions integrate with the LivelyGig protocol to provide traditional and agile project management processes that leverage the ecosystem.
- Contractors and talented resources offer their skills and availability, search for gigs, apply for work, complete tasks, and get paid.
- Job sites integrate with the LivelyGig protocol to offer their community members access to the LivelyGig ecosystem, perhaps without members even knowing about this connection.

Importantly, existing solution providers in project management, task management, job boards, and contracting firms can participate in this ecosystem quickly by integrating with the LivelyGig API, even without necessarily exposing the bitcoin or distributed application aspects of LivelyGig to their users.

LivelyGig will appeal most to a niche of the large job board marketplace – to those participants who are receptive to bitcoin or other crypto-tokens. This niche may be small initially, but will have immediate appeal to those living in areas whose local economies are not-so-great and to those who are early adopters of bitcoin. This niche is expected to grow into mainstream. The existing demand and supply for digitally delivered content are both very large; LivelyGig will help connect these parties in a direct and efficient way.

# Conceptual Information Model

The following types of objects are managed by the LivelyGig protocol:

- User (and specialized roles including employer and employee)
- User Profile (including skills, reputation, and cryptographic addresses)
- Project
- Project policy (optional rules to be enforced for all users, tasks, transactions)
- This is an employment and working agreement, e.g., between a project manager and a software developer. This agreement will include policy options on how the parties intend to interact on all tasks.
- Task – specific work to be performed.
- Task Dependency – prerequisite and sub-tasks that may block this task.
- Task Offer
- Task Bounty Offer
- Task Assignment – agreement to complete the task, including smart contract options. From a structural model perspective, LivelyGig will associate the task assignment with a gig.
- Task Deliverable – optionally, this can point to a provable deliverable.
- Task Transactions – these include partially signed transactions for escrow.
- Task Bounty Reward

# Task Status and Lifecycle

A task has a number of states tracked explicitly and derived implicitly based on relationships to other objects. These states include:

- New / Draft
- Offered
- Assigned (i.e., offer accepted)
-- Pending
   -- Blocked by dependent tasks (other than sub-tasks)
   -- Blocked by waiting on expected pre-signed transactions ("escrow")
   -- Blocked by resource availability
- In Work
- Delivered
- Accepted
- Completed
- Canceled

A task's state transitions will be managed by the protocol, based on events among the employer, employee, and the protocol, including:

- New -> Offered. The employer makes a private or public offer for a task.
- Offered -> Pending. An employee agrees to complete a task
* Pending -> In Work. The protocol determines the employee is not blocked by other tasks and any agreed upon start date has passed.
- In Work -> Delivered. The employee has completed the work and provided proof of publication. Optionally, the employee may be required to indemnify the employer from risks related to copyright or even major flaws (bugs). The employee may be asked to provide a warranty of quality.
- Delivered -> Accepted. The employer has reviewed the work and accepted it.

Other state transitions and new relationships are also supported, e.g.:

- Employer creates additional dependencies
- Employee creates sub-tasks (subdividing and/or delegating the work)
- Sub-tasks are accepted or canceled

# Value Generation Models

The LivelyGig team is considering several models to cover development and operational costs, including the following non-exclusive options:

1. Charge participants a fixed or percentage fee for bitcoin transactions managed and sent via escrow. This approach is assumed in this whitepaper, but might not be essential.
2. Charge participants (especially applications) for use of site for certain interactions with a digital technology-access token called dibs.
3. Charge advertisers. 

# Escrow of Pending Payments

As an option, any task can be enabled for payment in bitcoin. However, the LivelyGig protocol will never have custodial control of bitcoin. Escrow pay-in may be required from the employee and/or employer, depending on applicability of various policies of LivelyGig, employer, or employee. Escrow via the LivelyGig protocol may use an existing smart contract service or may use a new services that would be implemented by LivelyGig as a partially signed bitcoin transactions. Existing smart service projects are under consideration and include Trustatom, Codius, Omni, and Ethereum.

The LivelyGig escrow flow and implementation under consideration could utilize 2-of-2 multi-signature addresses created per task with a user's and LivelyGig's hierarchical deterministic multi-signature (HDM) addresses, with the user pre-signing transactions as follows:

- Funded by Employer:
  - Pay the Employee for work and pay LivelyGig commission. This is the normal escrow that LivelyGig will co-sign when work is accepted.
  - Refund to Employer. LivelyGig will co-sign this under certain circumstances, such as when the employee's task deadline has passed.

- Funded by Employee:
  - Refund to Employee. This is the normal escrow refund that LivelyGig will co-sign when the work (task delivery) is accepted.
  - Pay the Employer and pay LivelyGig commission. LivelyGig will co-sign this under certain circumstances, such as the employee's deadline has passed or they choose to cancel/renege.

Additional escrow creation and payment workflows can be supported for high-value and complex tasks:

The employer and employee can place additional bitcoins into escrow at certain points of the workflow:

- when a resource accepts an offer and there is an agreement to perform the work
- at the start of the work, when all task prerequisites have been met and after the resource committed availability
- incentives can be added by the task assigner for faster delivery (based on duration or schedule acceleration parameters)

The protocol signs pending payment transactions from escrow to employee when normal criteria are met:

- at the start of the work
- at intervals agreed upon up-front, for progress payments
- as agreed on for demonstrated progress (for "time and materials" type of work)
- at the final delivery of the work
- at the acceptance of the delivery

The protocol signs payment transactions to release escrow back to the employer under some conditions, as options:

- if employee cancels the agreement early
- if employee fails to deliver after an elapsed duration once the task started
- if employee fails to meet deadline date
- if employer rejects delivery

The protocol signs payment transactions to release escrow to both parties under certain conditions:

- if both parties agree to cancel the task
- if the task's prerequisite tasks were not satisfied after an expiration date (must start by date)

# Integration with Existing Project Management Solutions

Integrators can leverage LivelyGig's API to create synergy with best-in-class project management solutions, which already support traditional and agile project management techniques, e.g.:

- Tasks (work packages, epics, user stories, scenarios, etc.)
- Work breakdown structure
- Dependencies
- Work effort, duration
- Schedule
- Critical path
- Cost

# Task Offer, Talent Match, and Employment Agreement

- When working with LivelyGig, a project team can search for and select talent from among a highly skilled global community of software developers and other digital content producers.
- A task can be advertised (generally or very targeted) and made visible to potential employees.
- For a given task, there can be a single resource assignment or a contest-with-bounty, depending on the needs of the project and employer.
- The gig employment agreement and task assignment agreements can be made and priced via a process of negotiation, auction, fixed-price, or other means. 

# Task Completion, Delivery

- Depending on project policies, the entire delivery can be made privately (email, Gdrive, Dropbox, etc.) or may need to be provably accessible in an immutable repository such as GitHub or Storj, in which case the employee would provide the pointers.
- LivelyGig will record proof of process in Factom. Minimally, this is a hash of the delivery artifacts, and this process creates a provable audit trail.

# User-Behavior Rewards

The system rewards each of the contributors that provide utility to the LivelyGig system:

- Employers, including project managers, find qualified and affordable worldwide talent for tasks, quickly, and with ability to monitor progress, and provide incentives for faster delivery. They enjoy trouble-free payments. These payments are transparent and can be non-anonymous, if required and agreed to up-front by the parties.
- Employees, including skilled full-time and freelance talent are able to find interesting and rewarding gigs that match their skills. They receive quick payment and their reputation builds.
- Talent sourcing sites and contract management organizations can integrate with LivelyGig to supply additional work opportunities to their community members in a way that can provide a commission.
- Project management application owners can add value of talent resourcing to existing platform.

# Business Model and Integration Partners

Instead of building a complete ecosystem from scratch, LivelyGig will likely leverage the momentum and marketing already in place: 1) for matching jobs and employees, especially freelancers; and 2) for task management.

LivelyGig will focus its efforts on building the platform and protocol to manage gigs (employment agreements), task workflow, smart contracts, and payments. LivelyGig will provide the API to enable integrations to be written, with: 1) Job-seeking solutions on the market, including Freelance.com, Fiverr, oDesk/Elance, Bountysource, GigCoin, Coinality, and Mechanical Turk; and with 2) task management solutions, including Trello, Slack, Asana, and Jira.

In order to expand the appeal of LivelyGig to organizations who are careful to comply with laws and regulations, enhanced user registration and an integration with a payroll company such as BitWage can provide the data necessary for compliance.

# Technology

LivelyGig will be implemented as a decentralized application protocol, following the guidance outlined by in "The General Theory of Decentralized Applications, DApps" by David Johnston et al. This includes:

- pen-source
- perates autonomously, with no entity controlling the majority of its tokens
- data and records of operation cryptographically stored in a public, decentralized block chain
- contribution from users rewarded by payment in the application's tokens
- may adapt its protocol in response to proposed improvements and market feedback but all changes must be decided by majority consensus of its users.
- protocol has its own usage tokens (dibs). The protocol will also leverage bitcoin and potentially other crypto-currencies or smart properties.

The LivelyGig team is currently exploring a few distributed application and smart contract software stacks, including Ethereum, Omni, and Eris Industries.

Data will be stored in a distributed manner, currently being considered as follows:

- In Storj:
 - Project definition
 - Tasks and dependencies on other tasks
 - Minimal project plan information needed by LivelyGig protocol
 - User registration (minimally, a bitcoin address)
 - Skills and reputation
- On Omni, Bitcoin blockchain, or new sidechain
 - Contracts for work
 - Payment
- In Storj (data) and Factom (hash / audit trail)
 - Hash of details above
 - Escrow details
 - Proof of publication for work completion

# Dibs Technology Access Token

Certain LivelyGig transactions will require a token called dibs. Transactions in the protocol requiring tokens may include:

- Employer creates a project
- Employee candidate user posts a talent profile with capabilities
- Employer search for available talent
- Employer or employees update task state, workflow transitions – Offer, Assign/Accept, Complete, Cancel
- Employees enhance their reputation

# Dibs Crowd Sale

The Dibs smart property will likely be created during a crowd sale and utilized as follows:

- Crowd sale
 - Creates dibs tokens that provide participants rights to access the protocol
 - Issued on Omni, Counterparty, or a new sidechain, with potential funding via Lighthouse
 - Raises bitcoins to fund platform development and run servers
 - Additional considerations are in Swarm's Crowdsale Handbook. 
- Supports participants in the LivelyGig ecosystem: early investors, developers, and server operators.
- Development mechanism – Ten percent of dibs total tokens generated through fund-raising will be set aside for development of the LivelyGig protocol.
- Some percentage of sale proceeds will be controlled by the LivelyGig Foundation.
- Dibs can be bought and sold via Omni

# LivelyGig Foundation

This would have the primary charter of supporting the initial development, infrastructure, and maintenance of these. Such a foundation would ideally make decisions in a decentralized manner, using a "proof of stake" voting mechanism for any major decision as defined by its bylaws. LivelyGig protocol development will continue to operate under an open-source model.

# Summary

The LivelyGig protocol, along with integrations to other software solutions, provides project teams and talent an employment marketplace and a set of rules for managing work on tasks – small to large. LivelyGig enables smart contracts and incentives that are aligned with a project's economics. A project run with LivelyGig assures an appropriate level of transparency, creates a provable audit trail, and concludes a task workflow with an immediate payment.

LivelyGig's ecosystem (including the protocol, its users, and integrated applications) will encourage a qualified supply of satisfied talent and a demand for that talent that together delivers digital products with unprecedented speed, quality, and participant profitability.
