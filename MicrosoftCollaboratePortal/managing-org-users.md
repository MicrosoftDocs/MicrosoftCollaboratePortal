---
title: Managing engagement users
description: Microsoft Collaborate enables users from organizations to control the adding/removing of users for the organization.  During onboarding, Engagement Owners can assign individuals from an organization Power User permissions.  Power Users can only manage their own organization’s users. 
author: ikhapova
ms.author: ikhapova
ms.date: 12/12/2017
keywords: engagements, adding users, removing users, managing users, Collaborate security, Collaborate permissions, Microsoft Connect, SysDev Bug, Dev Center bugs
---

# Managing Users in MS Collaborate

The Microsoft Collaborate system uses **Engagements** to define the permissions/roles for the portal.  Very simply, if you are a participant of the engagement, you see the engagement metadata, content and feedback associated with the engagement.  The additional permissions within the engagement are defined as roles.  If you are added to a role, you can edit specific aspects of the program/engagement.  If you are not a member of the engagement, you do not see the engagement or any of its artifacts.

At this time, only Microsoft users can manage programs and engagements.  Non-Microsoft users can be Participants and Power Users.

MS Collaborate has the following membership roles:

Role | Scope of permissions | Description
---------------- | ------------------- | ---------------------------------
**Participants** | Engagement | Users of the content and feedback associated with the engagement. Able to view engagement information and the Program landing page the engagement is part of.  Able to download content.  Able to view, edit feedback work items associated with the engagement.
**Power User** | Engagement | Organization admins who are able to manage Participants for their organization.  An organization can have multiple Power Users identified.  Only Program Owners at Microsoft can add Power Users and Power Users can only add Participants.
**Content Publisher** | Engagement or Program | User able to publish content packages to be downloaded by participants.  Program-level Content Publishers can publish to all engagements under the Program.  Engagement-level Content Publishers can only publish the specific engagement.  
**Engagement Owner** | Engagement | Microsoft users able to manage the engagement, including engaement metadata, membership, feedback forms, and publishing templates.  Engagement owners also inherit all other role permissions within the engagement, such as package publishing and participant user permissions.  
**Engagement Manager** | Engagement  | Microsoft users with permission to create engagements under a program.  Users in this role inherit Engagement Owner permissions within all engagements under the program.  Program owners can add/remove users from this role for the program.
**Program Owner** | Program | Microsoft users who can manage all aspects of the program and all engagements under the program.  


## Managing User Memberships

Your Microsoft engagement owner(s) will set up the engagements in MS Collaborate and users will be invited to participate in the engagement.

Adding users to an engagement requires that each user be registered in the Dev Center with either an individual or company Dev Center account.  If the user is a member of a company or organization, the Dev Center admin needs to add the new users to the Dev Center company account before they can be added to an MS Collaborate engagement. If the company or organization does not yet exist in Dev Center, then a company representative needs to create a new company account in Dev Center and identify an organization admin who can add other users to the Dev Center company account.  

See [Register with Microsoft Collaborate](registration.md) for more information about getting set up to use MS Collaborate.

> [!NOTE]
> MS Collaborate uses the same Dev Center account as other programs in Dev Center.  The company you choose is important if your company or organization will also enroll in Dev Center programs that require bank account or certificate information.  

> If your organization uses Azure Active Directory (AAD) in Dev Center, you need to onboard the users to Dev Center in your AAD account.

> If you belong to multiple Dev Center organizations, you may need to switch your sign in to the organization that is onboarded to the MS Collaborate engagement you want to see.

## How to add users

Once a user is registered in Dev Center, it it easy for the MS Collaborate *Engagement Owner(s)* or organization's *Power User(s)* to a add the user to an engagement.  Engagement Owners can add Power Users for an organization.  Contact the MS Collaborate Engagement Owner to be added as a Power User for your organization.

1. Navigate to the Engagement in which you want to add or remove users and click **Edit Engagement** to open the Engagement management page. As an organization Power User, you can only change membership roles for users in your organization.  All other tabs will be read only.

2. Click on the **Membership** tab and select the **Group** that you want to manage.
	a. Participants can interact with the engagement artifacts (feedback, packages).
	b. Power Users can add or remove users for the organization.
	c. Note that *Power Users* need to be explicitly added as *Participants* if the user also needs access to feedback and content for the engagement.

	![Select a Group](images/Membership-tab.png)

3.	Click the **Add User** icon in the **Members** section and then in the **Search Users** dialog, search to find the user(s) you want to add to the engagement.

4. From the list of users returned by search, select the users you want to add to the engagement. You can also use **Select All**.

	![Add a User](images/add-a-user.png)

5. Choose whether you would like to have an invitation mail sent to the user with a link to the engagement.

Once the user is added to the list, the user can begin accessing the engagement content and feedback.

## Troubleshooting users missing from search

An organization's Power Users can only search for users within their own organization's Dev Center account.  For Engagement Owners, if the engagement has named organizations, the search for users will be limited to users within the named organizations.

If the users are not appearing in the search results for your engagement:
- check whether the user has been added to the organization’s Azure Active Directory (AAD) in Dev Center.  If not, have your organization's Dev Center admin add the user to your AAD and to the MS Collaborate program.
- It is possible that the organization has more than one Dev Center organization account (seller ID) in Dev Center.  Be sure the appropriate organization has been added to the engagement and that the appropriate users are in that organization.  If the organization is incorrect, please contact your Microsoft Engagement Owner.
	
## How to remove users

1.	To remove a user, select the user in the **Members** list and click the delete icon.
 
	![Remove a User](images/remove-a-user.png)

2.	Confirm that you want to remove the user, and the user will no longer be a member of the group.

Note that removing a user from an engagement does not impact the user's account in the Dev Center account system.  The user account will remain available for other engagements and other Dev Center programs.
