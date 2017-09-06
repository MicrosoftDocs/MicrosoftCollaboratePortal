---
title: Intro to Microsoft Collaborate
description: Overview of the Microsoft Collaborate Portal, including features available and conceptual information on how to use the system.  MS Collaborate enables sharing of engineering system work items (bugs, feature requests), distribution of content (builds, documents, specs), and user management, replacing Microsoft Connect and the SysDev Feedback Management portal. 
author: mattwojo
ms.author: mattwoj
ms.date: 09/01/2017
keywords: partner feedback, build downloads, downloading specs, bugs, Microsoft Connect, SysDev Bug, Dev Center bugs
---

# Introduction to Microsoft Collaborate

The Microsoft Collaborate (MS Collaborate) portal provides tools and services to streamline engineering collaboration within the Microsoft ecosystem.

## How does the MS Collaborate work?

MS Collaborate enables:
- Sharing of engineering system work items (bugs, feature requests, etc.);
- Distribution of content (builds, documents, specs);  
- Ability to manage users of the system. 

Available via the [Microsoft Dev Center Dashboard](//developer.microsoft.com/dashboard/apps/overview), the new MS Collaborate portal replaces the Microsoft Connect portal as well as the SysDev Feedback Management portal. Sign-in using your Dev Center credentials, or [register as a developer](//developer.microsoft.com/store/register) if you do not yet have credentials. 

## Programs and Engagements

The MS Collaborate system uses the concept of **Programs** and **Engagements** as the core building block for the system. 

### Engagement Management

Engagement defines which users are enabled to see and interact with specific content or work items. Unless they are part of an engagement, participant users would not see anything related to the engagement.

Engagements are similar to a virtual security group, allowing engagement owners to identify which users can see and work with the artifacts associated with that engagement.

Engagement owners can: 
- create new collaborations in the system, 
- associate users with various roles in the system, and 
- identify the collaboration as a named engagement that will map content or feedback to users.  

In addition, organization admins (Power Users) can self-manage their organization’s users within engagements, including the ability to:

- directly manage users, 
- program landing pages with context for each program, and
- manage user notifications.

### Content Sharing 

Content sharing is used to publish packages of files (documents, binaries, builds, etc.) associated with specific programs or engagements.  Each published package is mapped to an [Engagement](#engagement-management) and is available to the users of that Engagement. With the content sharing feature, publishers can publish and manage content and users can search content specifically available to them.

### Work Item Exchange

The feedback, or Work Item Exchange (WITEX), feature enables data to be shared for work items (bugs, features, etc.) from either the MS Collaborate portal or an organizations’ engineering system to other users or organizations identified in the engagement.

MS Collaborate brings new functionality enabling multiple parties to share the same work items. The WITEX service can connect to different types of engineering systems. Agents exist to make connecting VSTS possible through simple configurations – no code is required. 

External partners can connect WITEX directly to their own engineering system behind their firewall, including the following features: 

- **Feedback forms**: Customized feedback forms  will be available for each engagement to help streamline and simplify the sharing of information.
- **Shared feedback**: Engagements can have traditional 1-1 sharing of feedback forms between two organizations. In addition, they can have feedback forms that are shared between multiple organizations.


### Notifications and invitations

Users will be able to receive notifications when specific actions or events happen within the system.  There will be some default notifications (invitations to new engagements, new downloads, feedback state changes, etc.) that are available to all users.  In future versions, users will be able to subscribe and customize the notifications they receive. 

### Reporting

Reporting from the MS Collaborate portal will be available to program and engagement owners.  Pre-defined reports indicating overall system health and usage statistics will be available, as well as the ability to use Power BI to analyze data. 

## How does MS Collaborate differ from Microsoft Connect? 

Microsoft Connect was launched in July 2005 with millions of users helping to improve the quality and impact the direction of future releases of Microsoft products by providing feedback. Microsoft Connect enabled users to: 
- Find Microsoft products currently accepting community feedback; 
- Participate in feedback programs managed by Microsoft product teams;
- Download and test beta products;
- Submit bugs and suggestions for future releases;
- Vote, comment, and validate other people’s feedback.

MS Collaborate will replace Microsoft Connect, including a different look and new functionality. 

| Connect concept | MS Collaborate portal |
| ------- | -------- | --------- |
| Sites | N/A |
| Programs | Programs |
| Security groups | Engagements (define users and permissions) |
| Downloads | Packages (collections of files) |
| Feedback | Feedback (bugs, features, and other work items) |
| Program Admin (PA) | Program Owner |
| Product keys | N/A - handled by Microsoft Store |
| Surveys | N/A - may be added in the future |

### New concepts in MS Collaborate

When migrating from MS Connect to MS Collaborate, it is important to understand how programs and engagements work, and how they are used to drive user access to content and feedback.

- *Organizations*: MS Collaborate integrates with Azure Active Directory system used in Dev Center, which enables MS Collaborate to have a concept of organizations or companies; users are members of organizations using a corporate account or they are individuals with an MSA (single sign-on Microsoft account).
- *Engagement Owner (EO)*: Administrator for the engagement, able to edit the engagement, modify users; inherits all other user role powers for the engagement (publishing, configuration feedback, etc.).
- *Content Manager*: Able to publish and edit packages for an engagement or program.
- Program and engagement names are visible to the participant users.  Be sure to use names that can be shared with the users. 
   
