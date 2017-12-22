---
title: Register with MS Collaborate
description: MS Collaborate utilizes the Developer Center Dashboard requiring an individual Microsoft Account (MSA) or an organization with Azure Active Directory set up.
author: ikhapova
ms.author: ikhapova
ms.date: 12/12/2017
keywords: partner access, permissions, register, registration, onboarding, partner feedback, build downloads, downloading specs, bugs, Microsoft Connect, SysDev Bug, Dev Center bugs
---

# Register with Microsoft Collaborate

The Microsoft Collaborate (MS Collaborate) portal is embedded into the Microsoft Dev Center Dashboard. You can use your Dev Center account to log in and interact with MS Collaborate.  Before you can download content or submit feedback, you need to be invited to an MS Collaborate engagement. This can be done by either your Microsoft engagement owner, or by your company "Organization Admin" if your organization is already added to an Engagement.

Microsoft Collaborate is available at [https://aka.ms/collaborate](https://aka.ms/collaborate).

## How to register with Microsoft Developer Center

There are two ways to register with Dev Center: 
1. as an individual using a Microsoft Account (MSA), or
2. as a member of an organization with Azure Active Directory set up.  

Using Azure Active Directory is the preferred method for organizations collaborating with Microsoft.  If the organization is already set up in Dev Center, MS Collaborate simply uses the existing accounts.  

If your organization has not yet been onboarded to Dev Center, or for additional help, see the following articles:
- [Opening a developer account](//docs.microsoft.com/en-us/windows/uwp/publish/opening-a-developer-account)
- [Creating a company account](//docs.microsoft.com/en-us/windows/uwp/publish/opening-a-developer-account#additional-guidelines-for-company-accounts)

## How to log in to the MS Collaborate portal

1. Navigate to MS Collaborate: [https://developer.microsoft.com/en-us/dashboard/collaborate/](https://developer.microsoft.com/en-us/dashboard/collaborate/)

2.	You will be asked for credentials to log in. This is your Dev Center account credentials. If you have more than one account, select the appropriate account that you used to sign up for Dev Center. This can be a Microsoft alias account (MSA) or an Active Directory organization account. If you have not logged in before, you will need to enter your password.

3. After logging in, the Microsoft Collaborate dashboard will appear, showing you the engagements, packages, and feedback you are configured to see. If you are not a member of any programs or engagements, the lists will be blank. You need to be added to Engagements to interact with content or feedback. 

## How to associate your Dev Center account with Azure Active Directory and find your admin for company users

If your organization uses corporate accounts to log onto Dev Center, you will need to contact your Dev Center admin and have that person add you to the appropriate Azure Active Directory (AAD) seller ID for your company. However, before an admin can [add and manage account users](//docs.microsoft.com/en-us/windows/uwp/publish/add-users-groups-and-azure-ad-applications), you must first connect your AAD and personal Dev Center accounts. Follow the instructions in this article:
- [Associate Azure Active Directory with your Dev Center account](//docs.microsoft.com/en-us/windows/uwp/publish/associate-azure-ad-with-dev-center).

>[!NOTE]
>Dev Center leverages Azure Active Directory for multi-user management and roles assignment. If your organization already uses Office 365 or other business services from Microsoft, you already have AAD. Otherwise, you can create a new AAD tenant from within Dev Center at no additional charge.


## Troubleshooting registration issues

There are several issues that can cause difficulty signing-in.
### Invitations
If you received an email invitation to join Dev Center account, you need to accept the invitation before you can access Collaborate portal. The information below is intended to give you enough info to unblock yourself.

> You have been invited to access ... application as ... . However, we are not able to create this work or school account because ... is a domain that is federated with your on-premises AD. Please contact your admin to ensure you are properly configured in your on-premises AD and you can re-attempt to accept this invite.

Microsoft now is limiting usage of personal Microsoft accounts linked to a work/school email address, when the email domain is configured in Azure AD. If users have configured their work accounts as sign-in names for Microsoft account MSA then they would be prevented from accessing Collaborate Portal. In this scenario, users will have to rename their personal Microsoft account, by following [these steps](http://windows.microsoft.com/en-US/Windows/rename-personal-microsoft-account/):

1. Sign in to the [Your Info page](https://account.microsoft.com/profile) of your Microsoft account.
2. Select **Manage how you sign in to Microsoft**.
3. Look under the **Account alias** section.
  * If you already have a personal email address listed there, you can skip this step.
  * If your work or school email address is the only one listed, enter your personal email address, or get a new one from Microsoft, and select **Add email** or **Add phone number**.
 4. If your personal email address does not have **(primary alias)** listed next to it, select **Make primary** to set it as your primary alias.
 5. Select **Remove** next to your work email address to remove it from your account.

Going forward, you’ll sign in to your personal Microsoft account with your personal email address. You might need to sign in again to some apps and Windows devices.

Once completed proceed with accepting the Collaborate invitations that are send from [Microsoft Invitations](mailto:invites@microsoft.com) alias.  More information about blocking the ability to create a new personal Microsoft using a work/school email address is available in this [article](https://cloudblogs.microsoft.com/enterprisemobility/2016/09/15/cleaning-up-the-azure-ad-and-microsoft-account-overlap/).
