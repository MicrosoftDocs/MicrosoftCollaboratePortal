---
title: Working with Feedback work items
description: Microsoft Collaborate Feedback items can be bugs, feature requests or any task associated with an engagement. Feedback forms can be customized based on each engagement. 
author: ikhapova
ms.author: ikhapova
ms.date: 12/12/2017
keywords: feedback, engagements, work items, bugs, feature requests, Collaborate permissions, Microsoft Connect, SysDev Bug, Dev Center bugs 
---

# Feedback

## Overview
The [Feedback Hub](https://support.microsoft.com/en-us/help/4021566/windows-10-send-feedback-to-microsoft-with-feedback-hub-app) is a common mechanism for submitting bugs, issues and suggestions to Microsoft.  For organizations that are collaborating with Microsoft, MS Collaborate provides additional functionality that enables organizations and users to collaborate on feedback work items. Feedback can be configured in different ways to enable the functionality needed to support each specific collaboration.  

The MS Collaborate Feedback "work items" are typically bugs and feature requests that you submit to Microsoft, but the work items can be any kind of data that can be shared in a form (such as surveys, incidents, etc.). Each MS Collaborate Engagement Owner defines the feedback forms and how the data is synced to an internal Microsoft team engineering system (such as VSTS). Engagement Owners also configure routing to internal systems to ensure your feedback gets to the right feature teams.

In addition to using the MS Collaborate portal, some co-engineering partner organizations choose to integrate the MS Collaborate system into their own internal engineering system behind their firewall. This enables the partner organization's engineers to work in their own system while sharing data with Microsoft engineers, but does require additional work by the organization to onboard to MS Collaborate.

In the MS Collaborate portal, each feedback work item is associated with a single engagement to ensure only the right users and systems have access to the work item. Engagements can be between a Microsoft organization and one other organization (a single organization engagement) or the engagement can be between multiple organizations (multi-party engagements) - for example, a Microsoft organization plus an OEM, an ODM, and an IHV partner working on a specific device.  For more information on engagements, see [Programs and Engagements](intro-to-mscollaborate.md#programs-and-engagements).

- In **single-party engagements**, only the specific Microsoft organization and the one named organization can see the feedback work item(s) associated with the engagement. Both organization users can create new and collaborate on existing work items in the engagement. No other organizations or users not associated with the engagement can see the work item. 

- In **multi-party engagements**, all organizations named in the engagement can see and edit the same shared work item(s).  No other organizations or users not associated with the engagement can see the work item.

- In **any organization engagements**, users are added as individuals and not as organizations. This engagement style is typically used for incoming feedback only.   

### Legal Agreement 

When you onboard to MS Collaborate, you accept the terms of use covering the feedback for the engagements you belong to. You can always review default terms here:  MS Collaborate [Terms of Use](https://go.microsoft.com/fwlink/?linkid=849107).

In collaboration engagements, a legal agreement must exist between the parties in order for them to collaborate. You may be asked to accept a legal agreement or terms of use before you access the engagement for the first time.  As a member of the engagement, you will be able to see the other organizations participating in the collaboration. Users can assign the bug to a specific organization to indicate the “partner on point.”  However, users will only see the names of other users in their organization.  Other organizations will not have access to the users list.

### Universal Partner ID

The Universal Partner ID is an ID provided by the MS Collaborate feedback system and is shared with all users who have access to the work item. This ID is the ID within the MS Collaborate system and is not the specific ID of any feature team engineering system. This new universal ID facilitates multi-party collaborations so there is one common ID used by all parties.

Your engagement owner may decide to also include additional fields showing the specific ID in the engineering system (for example, a VSTS ID). 

## View, Vote and Comment

By default, the most recent feedback from engagements you belong to is shown on the MS Collaborate **Overview** page. 

To view feedback in the **All Feedback** page:
1. From the Dashboard, click on the feedback icon or select **Feedback** menu item in the left navigation. This takes you to the **All Feedback** page.
2. Click on any field to open the work item.

To view feedback from an **Engagement's Feedback** page:
1. Open engagement overview page.
2. Scroll to the feedback section and select one of the following:
 - Select the Work Item Type link to see all work items of that type
 - Select one of the queries to view work items specific to the query

### How to vote on feedback

1.  Open overview page for the engagement that feedback belongs to
2.  Scroll to the feedback section and click on **Work Item Type** link to see all work items of that type
3.  Click on one of the voting icons ![voting](images/voting.png) in the left column

or

3.  Open work item from list
4.  Click on one of the voting icons ![voting](images/voting.png) 

You can change your vote any time.

> [!NOTE]
> **Prerequisites**: Engagement must have commenting configured for the work item. This step is performed by engagement owner.

### How to comment on feedback
1. Open overview page for the engagement that feedback belongs to
2. Scroll to the feedback section and click on **Work Item Type** link to see all work items of that type
3. Open work item from the list and scroll to the bottom of the page
4. Enter comment into the **Post Comment** section and click **Submit Comment** button.

> You cannot modify or remove submitted comments.

> [!NOTE]
> **Prerequisites**: Engagement must have commenting configured for the work item. This step is performed by engagement owner.

## Manage

### How to submit new feedback

When you want to submit new feedback, you first select an engagement to associate with the feedback. Each work item must be associated with only one engagement because the engagement and work item type determine which form to use and which organization in Microsoft to sync the feedback to.

1. Choose one of the multiple ways to create new feedback:
- From the **MS Collaborate Dashboard**, click “Add New” under the Feedback item.
- From the **All Feedback** list page, select “Submit New Feedback".
- From an **Engagement** page, select "New" next to the specific work item type.

2. Select the appropriate Engagement for the work item.

	![Select an Engagement window](images/select-engagement.png)

3. The “Submit Feedback” page will appear. Complete the required fields and click “Save”.

	![Submit feedback window](images/submit-feedback.png)

> Fields on the **Submit Feedback** page are dependent on the Engagement selected. Engagements can customize the feedback forms as needed.
 
4. Clicking **Save** will take you to the **Feedback List** view. Work items submitted will appear on this page. 

### How to update feedback

1. Open a work item from any of the **Feedback List** pages. The **Edit Feedback** page will appear. You can edit any available fields depending on the state of the work item and the rules established for the engagement.

2. Saving the work item will sync changes for all organizations in the Engagement.

### How to assign feedback to others

When you are working with feedback work items in MS Collaborate, you can assign a work item to specific users in your organization, to a Microsoft feature team or division, or to another organization who is part of a multi-party engagement.

When you log into MS Collaborate, the system knows which organization you belong to.  This enables the feedback forms to populate user information for your organization.

New work items that are available for your organization to triage and assign typically have Assigned to = Active.  Note: engagement owners can customize the forms, so the exact functionality depends on how your engagement owner configured the forms.

When you select a people-based drop-down, you will see the name of the users in your organizations and of the other organization name(s).  Note that any named organizations can see the work items.

A work item assigned to you means it is your responsible to take action on the work item.

**To assign a work item to Microsoft**, select the Microsoft organization in the Assigned to (or Partner on Point) field.

## Search

On the [All Feedback page](//developer.microsoft.com/dashboard/collaborate/feedback/bugs) in the MS Collaborate portal, you can see all work items for the engagements you have access to.  You can filter the page for specific feedback in the following ways:
-	Sort individual columns in the feedback table.
- Select specific Engagements.
-	Filter by Title.
-	Filter by work item type.

	![Feedback search window](images/feedback-search.png)

### How to create and save queries

There are a few kinds of queries that can be saved with an Engagement. You can open the Engagement to see the Feedback work item types and the queries available.

- **My Queries** are created by you and are visible only to you. This is a private query.
- **Shared Queries** are created by participant users in the Engagement. This query is visible to all users in the Engagement.
- **Pre-Defined Queries** are created by the *Engagement Owner* and are available to all in the Engagement. This query is available to all users but is only editable by the *Engagement Owner*.

To create queries, you must be within the context of a specific engagement.  

1. Navigate to an Engagement and click on one of the options within the Engagement page to get to the list of feedback that you want in the query.

	 ![Feedback query window](images/create-feedback-query.png)

2. Click the **Advanced Filter** icon to see the fields that you can use to define the query. 

	![Feedback Advanced Filter window](images/feedback-advanced-filter.png)

3. Click **Run** to return the desired query results, you can click **Save As** to add the query.

	![Feedback Save Query window](images/feedback-query-save.png)

4. To **Edit** an existing query, navigate to the query, click the **Advanced Filter** icon and then click **Save As** to save the query as a new query.

### How to find feedback submitted by you

1. Navigate to an Engagement and click on one of the options within the Engagement page to get to the list of feedback that you want in the query.

2. Click the **Advanced Filter** icon to see the fields that you can use to define the query.

3. Click the '**+**' button to add new filter. Select **CreatedBy** from list of available fields.

4. Type **@user** in the textbox.

5. Click **Run** to return the desired query results.

![Feedback Created by Me](images/feedback-created-by-me.png)

## Export

### How to export feedback to Excel

After filtering to identify the work items that you want to export, you can export the table to Excel by clicking the export arrow.

![Export to Excel arrow icon](images/export-to-excel.png)


