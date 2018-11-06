---
title: Register with MS Collaborate
description: MS Collaborate utilizes the Developer Center Dashboard requiring an individual Microsoft Account (MSA) or an organization with Azure Active Directory set up.
author: ikhapova
ms.author: ikhapova
ms.date: 12/12/2017
keywords: partner access, permissions, register, registration, onboarding, partner feedback, build downloads, downloading specs, bugs, Microsoft Connect, SysDev Bug, Dev Center bugs
---

# Register with Microsoft Collaborate

The Microsoft Collaborate program requires registration. If you already have an account in Partner Center you can use it to enroll in Collaborate. 

## The account signup process

1.  Navigate to the [Partner Center Directory](https://partner.microsoft.com/en-us/dashboard/directory).
2.  If you're not already signed, sign in now using existing account or create a new Microsoft account. 

  > [!NOTE]
  > You can use **Azure AD** or **Microsoft Account** to sign in. You must have global administrator role to register with **Azure AD**. If you do not have the role, you can try to [find global administrator](troubleshooting#how-to-find-global-administrator-for-your-organization) for your organization or sign in using **Microsoft Account**.

3.  Scroll down to **Developer programs** section and click on [Get Started](https://partner.microsoft.com/dashboard/registration/microsoft-insider) link for **Microsoft Collaborate**.

![Get Started](images/PartnerCenterDirectory.png)

  > ![TIP]
  >  If you get an error message **We could not validate your identity as a global administrator** you cannot continue registration. Global administrator of your organization must complete registration. You can try to [find global administrator](troubleshooting#how-to-find-global-administrator-for-your-organization) for your organization or sign out and then sign in again using **Microsoft Account**.
      
4.  Select the country/region in which you live, or where your business is located. You won't be able to change this later.
5.  Select your account type (individual or company). You won't be able to change this later, so be sure to choose the right type of account.
6.  Enter the **publisher display name** that you wish to use (50 characters or fewer). Select this carefully, as this name will be used when you interact with Collaborate (download content, submit feedback and etc.). For company accounts, be sure to use your organization's registered business name or trade name. Note that if you enter a name that someone else has already selected, or if it appears that someone else has the rights to use that name, we will not allow you to use that name. 

  > [!NOTE]
  > Make sure you have the rights to use the name you enter here. If someone else has trademarked or copyrighted the name you picked, your account could be closed. If someone else is using a publisher display name for which you hold the trademark or other legal right, [contact Microsoft](http://go.microsoft.com/fwlink/p/?LinkId=233777).    

7.  Enter the contact info you want to use for your account.

  > [!NOTE]
  > We'll use this info to contact you about account-related matters. For example, you'll receive an email confirmation message after you complete your registration.

   If you are registering as a company, you'll also need to enter the name, email address, and phone number of the person who will approve your company's account.

8.  Review your account info and confirm that everything is correct. Then, read and accept the terms and conditions of the [Collaborate Agreement](https://go.microsoft.com/fwlink/?linkid=849107). Check the box to indicate you have read and accepted these terms.

9.  Click **Finish** to confirm your registration.  

## Additional guidelines for company accounts

When creating a company account, we suggest that you follow these guidelines, especially if more than one person needs to access the account.

> [!IMPORTANT]
> To allow multiple users to access your Dev Center account, we recommend using Azure Active Directory to assign roles to individual users. Each user can then access the Dev Center account by signing in with their individual Azure AD credentials. For more info, see [Manage account users](/windows/uwp/publish/manage-account-users).

-   Create your Microsoft account using an email address that doesn't already belong to you or another individual, such as MyCompany_DevCenter@outlook.com. You may not be able to use an email address at your company's domain, especially if your company already uses Azure AD.
-   If you plan to join Windows program for app development in future and want to reuse your dev center account, then it is recommended that you enroll to Windows program first and then join Microsoft Collaborate. Otherwise you might have to create separate accounts for these programs.
-   Add a company phone number that does not require an extension and is accessible to key team members.

## How to associate your Dev Center account with Azure Active Directory and manage users

You can use Azure Active Directory to add and manage additional users in your Dev Center account. You can define the role or custom permissions that each user should have. 

You must first associate your Dev Center account with your organization's Azure Active Directory to be able to add and manage users. 

This section describes how to do the following:

-   [Associate Azure Active Directory with your Dev Center account](/windows/uwp/publish/associate-azure-ad-with-dev-center)
-   [Add users, groups, and Azure AD applications to your Dev Center account](/windows/uwp/publish/add-users-groups-and-azure-ad-applications)
-   [Set roles and custom permissions for account users](/windows/uwp/publish/set-custom-permissions-for-account-users)

> [!TIP]
> Dev Center leverages Azure Active Directory for multi-user management and roles assignment. If your organization already uses Office 365 or other business services from Microsoft, you already have an AAD. Otherwise, you can create a new AAD tenant from within Dev Center at no additional charge.

## How to log in to the MS Collaborate portal

1. Navigate to MS Collaborate: [https://aka.ms/collaborate](https://aka.ms/collaborate).

2.	You will be asked for credentials to log in. This is your Dev Center account credentials. If you have more than one account, select the appropriate account that you used to sign up for Dev Center. This can be a Microsoft alias account (MSA) or an Active Directory organization account. If you have not logged in before, you will need to enter your password.

3. After logging in, the Microsoft Collaborate dashboard will appear, showing you the engagements, packages, and feedback, you are configured to see. If you are not a member of any programs or engagements, the lists will be blank. You need to be added to an engagement to interact with content or feedback. 

## Next steps

Before you can download content or submit feedback, you need to join an engagement. Some engagements require invitation from Microsoft **Engagement Owner** or **Power User** (when your organization is already added to an engagement). Other engagements are **Open** for users to join.
