---
title: Managing engagement users
description: Microsoft Collaborate enables users from organizations to control the adding/removing of users for the organization.  During onboarding, Engagement Owners can assign individuals from an organization Power User permissions.  Power Users can only manage their own organization’s users. 
author: mattwojo
ms.author: mattwoj
ms.date: 09/01/2017
keywords: engagements, adding users, removing users, managing users, Collaborate security, Collaborate permissions Microsoft Connect, SysDev Bug, Dev Center bugs
---

# Managing engagement users

MS Collaborate *Engagement Owners* can add *Power Users* to an engagement, enabling the *Power Users* to manage users for the specific organization. If you are a *Power User*, you can add and remove users for your organization.

> [!NOTE]
> If your organization uses Azure Active Directory (AAD) in Dev Center, you need to onboard the users to Dev Center in your AAD account.

## How to add/remove users

1. Navigate to the Engagement in which you want to add or remove users and click “Edit Engagement” to open the management page. Note that you can only change permissions for users in your organization as a *Power User*.  All other tabs will be read only.

2. Click on the **Permissions** tab and select the **Group** that you want to manage.
	a. Participants can interact with the engagement artifacts (feedback, packages).
	b. *Power Users* can add or remove users.
	c. Note that *Power Users* need to be explicitly added as *Participants* if the *Power User* needs to access the feedback and content for the engagement.

3.	Click the **Add User** icon in the **Members** section to launch the **Add a User** page.

![Add a User](images/membership-tab.png)

4. In the **Add a User** dialog, search for the user(s) you would like to add. Select the users you want to add to the engagement. You can also use **Select All**.
	a. Note that you can only search for users in your own organization.
	b. If the users are not appearing in the search, it is probably that the user has not been added to your organization’s Azure Active Directory in Dev Center.
	c. It is possible that your organization has more than one Organization account (seller Id) in Dev Center.  Be sure you are adding the appropriate organization to the engagement and that the appropriate users are in the organization.

![Add a User](images/add-a-user.png)

5.	To remove a user, select the user in the Members list and click the minus icon.
 
 ![Remove a User](images/remove-a-user.png)

6.	Confirm that you want to remove the user, and the user will no longer be in the list.

