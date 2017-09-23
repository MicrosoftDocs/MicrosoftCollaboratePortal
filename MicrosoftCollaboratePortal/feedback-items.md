---
title: Working with Feedback work items
description: Microsoft Collaborate Feedback items can be bugs, feature requests or any task associated with an engagement. Feedback forms can be customized based on each engagement. 
author: mattwojo
ms.author: mattwoj
ms.date: 09/01/2017
keywords: feedback, engagements, work items, bugs, feature requests, Collaborate permissions, Microsoft Connect, SysDev Bug, Dev Center bugs 
---

# Working with Feedback Work Items

The Feedback Hub is a common mechanism for submitting bugs, issue and suggestions to Microsoft.  For organiations that are collaborating with Microsoft, MS Collaborate provides additional functionality that enables organizations and users to collaborate on feedback work items.

Feedback work items are typically bugs and feature requests, but can be any data that can be shared in a form. Each engagement can define its own custom forms and the data is synced to internal Microsoft team engineering systems (such as VSTS). 

In addition to using the MS Collaborate portal, some organizations choose to integrate the MS Collaborate system into their own internal engineering system behind their firewall. This type of integration is available to co-engineering partners.

In the MS Collaborate portal, each feedback work item is associated with a single engagement. Engagements can be between a Microsoft organization and one other organization (a single organization) or the engagement can be between multiple organizations (multi-party engagements) - for example, a Microsoft organization pluz an OEM, an ODM, and an IHV partner working on a specific device.  For more information on engagements, see [Programs and Engagements](intro-to-mscollaborate.md/#programs-and-engagements).

- In **single-party engagements**, only the specific Microsoft organization and the second named organization can see the feedback work item(s) associated with the engagement. No other organizations or users not associated with the engagement can see the work item. The Microsoft organization can create and assign a bug to the organization in the engagement.  Both organization users can collaborate on all work items in the engagement.

- In **multi-party engagements**, all organizations named in the engagement can see and edit the same shared work item(s).  No other organizations or users not associated with the engagement can see the work item.

- In **any organization engagements**, users are added as individuals and not as organizations. This engagement style is typically for incoming feedback only.  Users can submit feedback and can only see and edit the feedback they submitted.  

- In **social media style engagements**, all users in the engagement can see all the work items, but users can only upvote (+1) and comment on the work item.  Comments can be public or private.

## Assigning Feedback Work Items



### The Universal Partner ID 

The Universal Partner ID is an ID provided by the feedback system and shared with all users of the work item.  This facilitates multi-party collaborations in which there is one common ID used by all parties.

### Legal agreement for collaboration

In collaboration engagements, a legal agreement exists between the parties in order for them to collaborate. You may be asked to accept a legal agreement when you access the engagement for the first time.  As a member of the engagement, you will be able to see the other organizations participating in the collaboration. Users can assign the bug to a specific organization to indicate the “partner on point.”

## How to view Feedback items

By default, the most recent feedback from engagements you belong to is shown on the MS Collaborate **Overview** page. 

To view feedback in the **All Feedback** page:
1.	From the Dashboard, select the **Show All** link or click **Feedback** in the left navigation.
2.	This takes you to the **All Feedback** page.
3.	Click on items in a row to open the work item.

### Search for specific feedback

On the [All Feedback page](//developer.microsoft.com/dashboard/collaborate/feedback/bugs), you can filter for specific feedback in the following ways:
1.	Sort individual columns in the feedback table.
2.	Select specific Engagements.
3.	Filter by Title.
4.	Filter by work item type.

![Feedback search window](images/feedback-search.png)

## How to create and save queries for work items

There are a few kinds of queries that can be saved with an Engagement. You can open the Engagement to see the Feedback work item types and the queries available.

- **My Queries** are created by you and are visible only to you. This is a private query.
- **Shared Queries** are created by participant users in the Engagement. This query is visible to all users in the Engagement.
- **Pre-Defined Queries** are created by the *Engagement Owner* and are available to all in the Engagement. This query is available to all users but is only editable by the *Engagement Owner*.

To create queries, you must be within the context of a specific Engagement.  

1. Navigate to an Engagement and click on one of the options within the Engagement page to get to the list of feedback that you want in the query.

![Feedback query window](images/create-feedback-query.png)

2. Click the **Advanced Filter** icon to see the fields that you can use to define the query. 

![Feedback Advanced Filter window](images/feedback-advanced-filter.png)

3. Click **Run** to return the desired query results, you can click **Save As** to add the query.

![Feedback Save Query window](images/feedback-query-save.png)

4. To **Edit** an existing query, navigate to the query, click the **Advanced Filter** icon and then click **Save As** to save the query as a new query.

## How to submit new feedback work items (e.g. bugs, feature requests, etc.)

All feedback work items must be associated with a specific Engagement. A work item can only be in one Engagement at a time. The Engagement determines not only who can see/edit the work item, but also determines the forms and fields available. When creating new feedback, you will need to select the appropriate Engagement.

1. Choose one of the multiple ways to create new feedback:
- From the **MS Collaborate Dashboard**, click “Add New” under the Feedback item.
- From the **All Feedback** list page, select “Submit New Feedback".
- From an **Engagement** page, select "New" next to the specific work item type.

2. Select the appropriate Engagement for the work item.

![Select an Engagement window](images/select-engagement.png)

3. The “Submit Feedback” page will appear. Complete the required fields and click “Save”.

![Submit feedback window](images/submit-feedback.png)

> [!NOTE]
> Fields on the **Submit Feedback** page are dependent on the Engagement selected. Engagements can customize the feedback forms as needed.
 
4.	Clicking “Save” will take you to the **Feedback List** view. Work items submitted will appear on this page. 

## How to Edit Feedback Work Items

1. Open a work item from any of the **Feedback List** pages. The **Edit Feedback** page will appear. You can edit any available fields depending on the state of the work item and the rules established for the engagement.

2. Saving the work item will sync changes for all organizations in the Engagement.

## How to export feedback to Excel

After filtering to identify the work items that you want to export, you can export the table to Excel by clicking the export arrow.

![Export to Excel arrow icon](images/export-to-excel.png)
