---
title: Working with Feedback work items
description: Microsoft Collaborate Feedback items can be bugs, feature requests or any task associated with an engagement. Feedback forms can be customized based on each engagement. 
author: LinChristie
ms.author: chlin
ms.date: 01/18/2022
---

# Working with feedback work items

The [Feedback Hub](https://support.microsoft.com/en-us/help/4021566/windows-10-send-feedback-to-microsoft-with-feedback-hub-app) is a common mechanism for submitting bugs, issues and suggestions to Microsoft.  For organizations that are collaborating with Microsoft, MS Collaborate provides additional functionality that enables organizations and users to collaborate on feedback work items. Feedback can be configured in different ways to enable the functionality needed to support each specific collaboration.  

The MS Collaborate Feedback "work items" are typically bugs and feature requests that you submit to Microsoft, but the work items can be any kind of data that can be shared in a form (such as surveys, incidents, etc.). Each MS Collaborate Engagement Owner defines the feedback forms and how the data is synced to an internal Microsoft team engineering system (such as VSTS). Engagement Owners also configure routing to internal systems to ensure your feedback gets to the right feature teams.

In addition to using the MS Collaborate portal, some co-engineering partner organizations choose to integrate the MS Collaborate system into their own internal engineering system behind their firewall. This enables the partner organization's engineers to work in their own system while sharing data with Microsoft engineers, but does require additional work by the organization to onboard to MS Collaborate.

## Engagement Types

In the MS Collaborate portal, each feedback work item is associated with a single engagement to ensure only the right users and systems have access to the work item. Engagements can be between a Microsoft organization and one other organization (a single organization engagement) or the engagement can be between multiple organizations (multi-party engagements) - for example, a Microsoft organization plus an OEM, an ODM, and an IHV partner working on a specific device.  For more information on engagements, see [Programs and Engagements](intro-to-mscollaborate.md#programs-and-engagements).

- In **single-party engagements**, only the specific Microsoft organization and the one named organization can see the feedback work item(s) associated with the engagement. Both organization users can create new and collaborate on existing work items in the engagement. No other organizations or users not associated with the engagement can see the work item. 

- In **multi-party engagements**, all organizations named in the engagement can see and edit the same shared work item(s).  No other organizations or users not associated with the engagement can see the work item.

- In **any organization engagements**, users are added as individuals and not as organizations. This engagement style is typically used for incoming feedback only.

## Legal Agreement

When you onboard to MS Collaborate, you accept the terms of use covering the feedback for the engagements you belong to. You can always review default terms here:  MS Collaborate [Terms of Use](/collaborate/terms-of-use).

In collaboration engagements, a legal agreement must exist between the parties in order for them to collaborate. You may be asked to accept a legal agreement or terms of use before you access the engagement for the first time.  As a member of the engagement, you will be able to see the other organizations participating in the collaboration. Users can assign the bug to a specific organization to indicate the “partner on point.”  However, users will only see the names of other users in their organization.  Other organizations will not have access to the users list.

## Universal Partner ID

The Universal Partner ID is an ID provided by the MS Collaborate feedback system and is shared with all users who have access to the work item. This ID is the ID within the MS Collaborate system and is not the specific ID of any feature team engineering system. This new universal ID facilitates multi-party collaborations so there is one common ID used by all parties.

> Engagement owner(s) may decide to also include additional fields showing the specific ID in the engineering system (for example, a VSTS ID).
