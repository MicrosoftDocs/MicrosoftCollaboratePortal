---
title: Intro to Microsoft Collaborate
description: Overview of the Microsoft Collaborate Portal, including features available and conceptual information on how to use the system.  MS Collaborate enables sharing of engineering system work items (bugs, feature requests), distribution of content (builds, documents, specs), and user management, replacing Microsoft Connect and the SysDev Feedback Management portal. 
author: chriskleinke
ms.author: chriskl
ms.date: 09/01/2017
keywords: partner feedback, build downloads, downloading specs, bugs, Microsoft Connect, SysDev Bug, Partner Center bugs
---

# Introduction to Microsoft Collaborate

The Microsoft Collaborate (MS Collaborate) portal provides tools and services to streamline engineering collaboration within the Microsoft ecosystem.  

MS Collaborate enables:
- Sharing of engineering system work items (bugs, feature requests, etc.);
- Distribution of content (builds, documents, tools, specs);  
- Ability to manage users of the system. 

Available via the [Microsoft Partner Center Dashboard](https://partner.microsoft.com/dashboard/collaborate), the new MS Collaborate portal provides a single location using a single set of credentials to see your work items and content.  This new system replaces the Microsoft Connect portal as well as the SysDev Feedback Management portal. 

You can access MS Collaborate using the friendly link:  [https://aka.ms/collaborate](https://aka.ms/collaborate).

Sign-in using your Partner Center credentials, as either an individual or as a member of a company or organization.  Before using MS Collaborate, you will need to register for Partner Center. For more information, see [Register with Microsoft Collaborate](registration.md).

## Programs and Engagements

The MS Collaborate system uses the concept of **Programs** and **Engagements** as the core building blocks for the system. Programs provide structure and facilitate managing engagements. Engagements have only one parent program and they inherit feedback forms, queries, and publishing templates defined at the program level.  Engagements can be customized and they define sets of users who can interact with content and feedback associated with the engagement. Program Owners are Microsoft users who have permissions to:
- define program metadata, including Program Landing pages
- define default feedback forms
- define publishing templates to facilitate publishing packages to multiple engagements
- identify Engagement Managers who have permissions to create Engagements under the program.

When you log into MS Collaborate, you will see the programs and engagements you belong to. It is possible that you are a member of only one engagement or of many engagements within a program.  The functionality you see in MS Collaborate also depends on your role within each engagement. Participant users can download content and submit/edit feedback.  If you have administrative permissions, you will also see icons to edit items you are given permission to view and edit.  You can be a partcipant in one engagement and a power user in another.

For more information, see [Programs and Engagements](programs.md)

### Engagement Management

An engagement defines which users are enabled to see and interact with specific content or work items associated with that engagement. Unless a user is a member of an engagement, the users does not see anything related to the engagement.

Engagements are similar to a virtual security group, allowing engagement owners to identify which users can see and work with the artifacts associated with that engagement.  There are a few different types of engagements determined by the kinds and number of organizations/users within the engagement:
- collaboration between a single company/organization and a single Microsoft organization,
- collaboration between multiple named organizations (e.g., Microsoft team 1 users, company A users, and company B users), and
- collaboration with users from any organizations.

Each engagement is associated with either the default MS Collaborate [Terms of Use](https://go.microsoft.com/fwlink/?linkid=849107) or an appropriate custom legal agreement between the parties in the engagement. Participant users should visit the engagement page and see the description and agreement that applies to each specific engagement.  For more information about seeing the legal agreement for an engagement, see [How to view your Engagements](view-engagements.md).

Engagement owners are Microsoft users who manage the engagement in MS Collaborate.  Users with Engagement Owner permissions can: 
- create new collaborations in the system as a named engagement that will map content or feedback to users, 
- associate users with various roles in the system (including adding organization admins as Power Users,
- manage feedback forms for the engagement, and 
- publish content to the engagement users.

Organization admins (Power Users) can self-manage their organization’s users within an engagement, including the ability to:
- add or remove organization user accounts as participant users in an engagement, and
- add or remove other organization Power Users.

For information, see [Managing organization users](managing-org-users.md).

### Content Sharing 

Content sharing is accomplished by publishing "packages" of files (documents, binaries, builds, tools, etc.) in MS Collaborate.  Content Publishers can target all engagements within a program or specific engagements when publishing a package so it is available to the users of targeted engagements. When published, packages are associated with engagements, descriptions, and keywords to facilitate finding the right packages easily.  Within MS Collaborate, participant users can search for and download files within a package.  

MS Collaborate also provides a Distribution Manager to facilitate downloading of large or multi-file packages.  The Distribution Manager is a ClickOnce client app that can be accessed from within the MS Collaborate Package Download pages.  

For more information, see [Working with Package Downloads](package-downloads.md).

### Feedback Work Item Exchange

The feedback, or Work Item Exchange, system within MS Collaborate enables the sharing of feedback work items (bugs, features, etc.) within the MS Collaborate portal or via an API directly to an organizations’ engineering system.  Each work item is associated with one engagement, which determines which users or organizations are permissions to see and interact with the work item. 

Each program and/or engagement can determine how each feedback form will be shared and which fields will be available - the decisions and configuration are the responsibility of the engagement owner.  In addition, engagement owners can further customize each feedback form to help facilitate and simplify the process for sharing work items. Depending on how the engagement is configured, work items can be created by either participant users for Microsoft to address or by Microsoft users for partner organizations to address.  Feedback forms can also be enabled to share attachments to the feedback form.

The MS Collaborate Feedback pages provide views of all your feedback items, advanced search to identify specific feedback, and the ability to save and share queries.  New in MS Collaborate is the ability to have shared queries available to all users within an engagement or program.  These queries can be configured to match queries used by Microsoft users to facilitate having the same list of bugs for review.

MS Collaborate also brings new functionality enabling multiple parties to share the same work item. If the engagement contains multiple parties, all members of the engagement can see, edit, and collaborate on the same work items.  Multi-party feedback collaboration does require appropriate legal agreements between the parties.

Because of the new multi-party sharing functionality, MS Collaborate introduces a new Universal ID that makes it possible for all parties to be using the same ID when referring to work items.  Specific engagements can be configured to also share additional fields to help the members of an engagement collaborate, for example, an engagement owner can choose to also include a field showing the specific internal Microsoft system ID.

The MS Collaborate portal can be used to collaborate on feedback work items. The Work Item Exchange service can also connect to different types of engineering systems. Agents exist to make connecting VSTS instances possible through simple configurations – no code is required.  Partner organizations can connect WITEX directly to their own engineering system behind their firewall, including the following features: 
- Feedback forms: Customized feedback forms will be available for each engagement to help streamline and simplify the sharing of information.
- Shared feedback: Engagements can have traditional 1-1 sharing of feedback forms between two organizations. In addition, they can have feedback forms that are shared between multiple organizations.

For more information, see [Working with Feedback work items](feedback-items.md).

### Notifications and invitations

Users will be able to receive notifications when specific actions or events happen within the system.  There will be default notifications (invitations to new engagements, new packages available for download, feedback work items that change state, etc.) that are available to all users.  In future versions, users will be able to subscribe and customize the notifications they receive. 

To receive notifications, each user must ensure an appropriate email address is provided in the Notications section on Partner Center.  MS Collaborate uses your Partner Center account information for notifications and permissions within the system.

### Reporting and Analytics

Reporting from the MS Collaborate portal will be available to users.  The reports available is determined by your membership role within engagements.  Pre-defined reports indicating overall system health and usage statistics will be available, as well as the ability to use Power BI to analyze data. 

## How does MS Collaborate differ from Microsoft Connect? 

Microsoft Connect was launched in July 2005 and has been used by millions of users to provide feedback and to download content. Microsoft Connect enabled users to: 
- Find Microsoft products currently accepting community feedback; 
- Participate in feedback programs managed by Microsoft product teams;
- Download and test beta products;
- Submit bugs and suggestions for future releases;
- Vote, comment, and validate other people’s feedback.

MS Collaborate replaces Microsoft Connect, including a different look and new functionality to facilitate collaboration. 

| Connect concept | MS Collaborate portal concept |
| ------- | -------- |
| Sites | N/A |
| Programs | Programs |
| Security groups | Engagements (define users and permissions) |
| Downloads | Packages (collections of files) |
| Feedback | Feedback (bugs, features, and other work items) |
| Program Admin (PA) | Program Owner and Engagement Owners|
| Product keys | N/A - no longer available |

### New concepts in MS Collaborate

When migrating from MS Connect to MS Collaborate, it is important to understand how programs and engagements work, and how they are used to drive user access to and collaboration on content and feedback.  

- *Organizations*: MS Collaborate integrates with the Account Management System in Partner Center, which uses both Microsoft Accounts (MSAs) and Azure Active Directory.  By adding Active Directory, MS Collaborate can take advantage of Partner Center's concept of organizations or companies; users are members of organizations using a corporate account or they are individuals with an MSA (single sign-on Microsoft account).
- *Engagement Owner*: Administrator for the engagement, able to configure the engagement, modify users; inherits all other user role powers for the engagement (publishing, configuration of feedback, etc.).
- *Content Manager*: Able to publish and edit packages for an engagement or program.
- Program and engagement names are visible to all users.  Engagements with defined organiations or companies clearly identify the organizations who have permissions for the engagement on the engagement page.  The legal agreement for the engagement is also available to all users who are members of the engagement.

When migrating from the older system to the new Partner Center-based MS Collaborate, the biggest change is migrating user accounts to Partner Center.  Partner Center identifies a "Partner Center Admin" who is responsible for managing the Partner Center accounts for the company.  You will need to know who your admin is and whether your company uses Active Directory or not.  
   
