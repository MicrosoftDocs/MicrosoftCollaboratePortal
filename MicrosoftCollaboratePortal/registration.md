---
title: Register with MS Collaborate
description: MS Collaborate utilizes the Partner Center Dashboard requiring an individual Microsoft Account (MSA) or an organization with Azure Active Directory set up.
author: ikhapova
ms.author: ikhapova
ms.date: 12/12/2017
keywords: partner access, permissions, register, registration, onboarding, partner feedback, build downloads, downloading specs, bugs, Microsoft Connect, SysDev Bug, Partner Center
---

# Registration

Microsoft Collaborate program is offered through Partner Center and requires registration. If you already have an account in Partner Center it is best to use the same account to enroll in Collaborate. 

 > [!IMPORTANT]
 > You can use one of the following accounts to work in Partner Center:
 > * *Microsoft Account* (personal account)
 > * *Azure AD* (organizational account)
 >
 > Only users with *global administrator* role can register using *Azure AD* account. If you do not have this role, you can try to [find global administrator](troubleshooting.md#how-to-find-global-administrator-for-your-organization) for your organization to help you register.
 
## How to register as an individual

1. Navigate to the [Partner Center Directory](https://partner.microsoft.com/en-us/dashboard/directory).
2. If you're not already signed, sign in now using existing account or create new *Microsoft Account*. 
3. Scroll down to **Developer programs** section and click on [Get Started](https://partner.microsoft.com/en-us/dashboard/registration/collaborate) link for **Microsoft Collaborate**. 

   ![Get Started](images/PartnerCenterDirectory.png)

4. The **Get Started** link will take you to the registraion page. 

   ![Account Info](images/RegistrationAccountInfo.png)

   > [!NOTE]
   > If you signed in with the existing Partner Center account the page will contain information from that account. You can modify **Publisher display name** and **Contact info** if needed.
    
   > [!IMPORTANT]
   > The following error indicates that user is signed in with an *Azure AD* account that does not have administrator privileges and registration cannot be completed. 
   > > We could not validate your identity as a global administrator. 
   > 
   > Try to [find global administrator](troubleshooting.md#how-to-find-global-administrator-for-your-organization) for your organization or sign out and sign in again using *Microsoft Account*. 

5. Select the **Account country/region** in which you live, or where your business is located. You won't be able to change this later.
6. Select your **Account type** (individual or company). You won't be able to change this later, so be sure to choose the right type of account.
7. Enter the **Publisher display name** that you wish to use (50 characters or fewer). Select this carefully, as this name will be used when you interact with Collaborate (download content, submit feedback and etc.). For company accounts, be sure to use your organization's registered business name or trade name. Note that if you enter a name that someone else has already selected, or if it appears that someone else has the rights to use that name, we will not allow you to use that name. 

   > [!NOTE]
   > Make sure you have the rights to use the name you enter here. If someone else has trademarked or copyrighted the name you picked, your account could be closed. If someone else is using a publisher display name for which you hold the trademark or other legal right, [contact Microsoft](http://go.microsoft.com/fwlink/p/?LinkId=233777).    

8. Enter the contact info you want to use for your account.

   > [!NOTE]
   > We'll use this info to contact you about account-related matters. For example, you'll receive an email confirmation message after you complete your registration.

   If you are registering as a company, you'll also need to enter the name, email address, and phone number of the person who will approve your company's account.

9. Review your account info and confirm that everything is correct. Then, read and accept the terms and conditions of the [Collaborate Agreement](https://go.microsoft.com/fwlink/?linkid=849107). Check the box to indicate you have read and accepted these terms.

10. Click **Finish** to confirm your registration.  

## How to configure access for multiple users

You can use Azure Active Directory to add and manage additional users in your Partner Center account. 
-   [Associate Azure Active Directory with your Partner Center account](/windows/uwp/publish/associate-azure-ad-with-dev-center)

You must first associate your Partner Center account with your organization's Azure Active Directory to be able to add and manage users. 
-   [Add users, groups, and Azure AD applications to your Partner Center account](/windows/uwp/publish/add-users-groups-and-azure-ad-applications)

You can define the role or custom permissions that each user should have. 
-   [Set roles and custom permissions for account users](/windows/uwp/publish/set-custom-permissions-for-account-users)

> [!TIP]
> Partner Center leverages Azure Active Directory for multi-user management and roles assignment. If your organization already uses Office 365 or other business services from Microsoft, you already have an AAD. Otherwise, you can create a new AAD tenant from within Partner Center at no additional charge.

## How to register as an organization

### Before you begin
To create an account on Partner Center, you’ll need to have on hand the following information. You may want to take a few minutes to gather these items before you get started:

* Global administrator work email. If you're not sure what your company's work account is, see [how to find global administrator](troubleshooting.md#how-to-find-global-administrator-for-your-organization).

* If your company doesn’t have a work account, you can create one during the account creation process.

* Your company’s legal business name, address, and primary contact. We need this information to confirm that your company has an established profile and that you are authorized to act on its behalf.

* Authority to sign legal agreements. Ensure that you are authorized to sign legal agreements on your company's behalf as you’ll be asked to do so during the enrollment process.

* Name and company email of the person you want to act as your primary contact.

### Guidelines
When creating a company account, we suggest that you follow these guidelines, especially if more than one person needs to access the account.

 - Create your Microsoft account using an email address that doesn't already belong to you or another individual, such as *MyCompany_PartnerCenter@outlook.com*. You may not be able to use an email address at your company's domain, especially if your company already uses Azure AD.
 - If you plan to join **Windows** program for app development in future and want to reuse your partner center account, then it is recommended that you enroll to **Windows** program first and then join **Collaborate**. Otherwise you might have to create separate accounts for these programs.
 - Add a company phone number that does not require an extension and is accessible to key team members.


## How to access the Collaborate portal

1. Navigate to MS Collaborate: [https://aka.ms/collaborate](https://aka.ms/collaborate).

2.	You will be asked for credentials to sign in. This is your Partner Center account credentials. If you have more than one account, select the appropriate account that you used to sign up for Partner Center. This can be a personal (Microsoft Account) or work (Azure Active Directory) account. 

3. Once you are signed in, the Collaborate dashboard will appear, showing you the engagements, packages, and feedback, you are configured to see. 

   > [!NOTE]
   > If you are not a member of any programs or engagements, the lists will be blank. You need to join or request access an engagement to interact with content or feedback. 

## Next steps

Before you can download content or submit feedback, you need to join an engagement. Some engagements require an invitation from **Engagement Owner** or **Power User** (when your organization is already added to an engagement). Other engagements are **Open** for users to join.
