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

## The account signup process

> [!NOTE]
> In some cases, the screens and fields you see when registering for an account may vary slightly from what is outlined below. The basic information and process will be the same.

1.  Navigate to the [https://aka.ms/collaborate](https://aka.ms/collaborate) page. The system will automatically redirect you to the Collaborate registration page.
2.  If you're not already signed in with a Microsoft account, sign in now, or create a new Microsoft account. The Microsoft account you use here will be what you use to sign in to your developer account.
3.  Select the country/region in which you live, or where your business is located. You won't be able to change this later.
4.  Select your account type (individual or company). You won't be able to change this later, so be sure to choose the right type of account.
5.  Enter the **publisher display name** that you wish to use (50 characters or fewer). Select this carefully, as this name will be used when you interact with Collaborate (download content, submit feedback and etc.). For company accounts, be sure to use your organization's registered business name or trade name. Note that if you enter a name that someone else has already selected, or if it appears that someone else has the rights to use that name, we will not allow you to use that name. 

  > [!NOTE]
  > Make sure you have the rights to use the name you enter here. If someone else has trademarked or copyrighted the name you picked, your account could be closed. See the [App Developer Agreement](https://msdn.microsoft.com/library/windows/apps/Hh694058) for more info. If someone else is using a publisher display name for which you hold the trademark or other legal right, [contact Microsoft](http://go.microsoft.com/fwlink/p/?LinkId=233777).    

6.  Enter the contact info you want to use for your account.

  > [!NOTE]
  > We'll use this info to contact you about account-related matters. For example, you'll receive an email confirmation message after you complete your registration. After that, we'll send messages when we pay you, or if you need to fix something with your account. We may also send informational emails as described above, unless you opt out of receiving non-transactional emails.

   If you are registering as a company, you'll also need to enter the name, email address, and phone number of the person who will approve your company's account.

7.  Review your account info and confirm that everything is correct. Then, read and accept the terms and conditions of the [Collaborate Agreement](https://go.microsoft.com/fwlink/?linkid=849107). Check the box to indicate you have read and accepted these terms.

8.  Click **Finish** to confirm your registration.  

## Additional guidelines for company accounts

When creating a company account, we suggest that you follow these guidelines, especially if more than one person needs to access the account by using the Microsoft account that opened the account. 

> [!IMPORTANT]
> To allow multiple users to access your Dev Center account, we recommend using Azure Active Directory to assign roles to individual users. Each user can then access the Dev Center account by signing in with their individual Azure AD credentials. For more info, see [Manage account users](manage-account-users.md).

-   Create your Microsoft account using an email address that doesn't already belong to you or another individual, such as MyCompany_DevCenter@outlook.com. You may not be able to use an email address at your company's domain, especially if your company already uses Azure AD.
-   Limit access to this Microsoft account to the smallest possible number of users.
-   Set up a corporate email distribution list that includes everyone who needs to access the developer account, and add this email address to your security info. This allows all of the employees on the list to receive security codes when needed. If setting up a distribution list is not feasible, the owner of the individual email account will need to be available to access and share the security code when prompted (such as when new security info is added to the account, or when it is accessed from a new device).
-   Add a company phone number that does not require an extension and is accessible to key team members.
-   In general, have developers use trusted devices to log in to your company's developer account. All key team members should have access to these trusted devices. This will reduce the need for security codes to be sent when accessing the account. There is a limit to the number of codes that can be generated per account, per week.
-   If you need to allow access to the account from a non-trusted PC, limit that access to a maximum of five developers. Ideally, these developers should access the account from machines that share the same geographical and network location.
-   Frequently review your company’s security info at [https://account.live.com/proofs/Manage](http://go.microsoft.com/fwlink/p/?LinkID=266648) to make sure it's all current.

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
If you have been invited to join Dev Center account, you need to accept the invitation before you can access Collaborate portal. If you see an error message similar to shown below, it means that you have two accounts with Microsoft using the same email address. 

> You have been invited to access ... application as ... .<br> 
> However, we are not able to create this work or school account because ... is a domain that is federated with your on-premises AD.<br> 
> Please contact your admin to ensure you are properly configured in your on-premises AD and you can re-attempt to accept this invite.<br>

The information below is intended to give you enough info to unblock yourself.
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
