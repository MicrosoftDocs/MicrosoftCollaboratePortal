---
title: Support and Troubleshooting
description: How to get support and troubleshoot common issues.
author: mimcco
ms.author: mimcco
ms.date: 02/06/2018
keywords: support, troubeshooting, registration, access, accounts, feedback
---

# How to Get Support and Troubleshoot Common Issues
This page provides instructions on how to get support with Microsoft Collaborate and provides troubleshooting guides for common issues.

## How to Get Support
1. If you are not sure how to do something in Microsoft Collaborate, review the [Documentation and Guidance](https://docs.microsoft.com/en-us/collaborate/) for the area you have questions about.
2. If something is not working the way you expect, check the troubleshooting guides below and see if your issue is included.
3. If you have a question or issue, such as getting access to specific content,  related to the specific program you are participating in, contact the program administrators.
4. If none of the above answers your question or resolves your issue, contact Dev Center Customer Support at https://aka.ms/dcsupport.

# Troubleshooting Guides

## Sign-in Issues

### Microsoft Account Sign-in
If you can't sign in to Microsoft Collaborate website, try these suggestions: 
- make sure that you sign in using your complete email address
- check the status of the Microsoft account service
- make sure that you entered your password correctly. Passwords are case sensitive. If you've forgotten your password, go to the Microsoft account [reset your password](https://account.live.com/password/reset) page.
- make sure that your browser is configured to allow cookies. If your browser doesn’t allow cookies, you can’t sign in with your Microsoft account.
- try clearing your browser's cache, cookies, temporary files, and any other browsing history that is stored. Close your browser, then open a new InPrivate browsing session.


### Browser hangs or shows "page can't be displayed" error when signing in to Dev Center
After going to Dev Center/Collaborate and entering your username and password, you see one of these issues or errors:
- your browser appears to hang or become unresponsive
- you get a "page can't be displayed" error
- you get an error that says "ERR_TOO_MANY_REDIRECTS"
- you get an error that says "Hmm, we can't reach this page."
- you accept an invitation email from Dev Center and you get this message:

    *You have been invited to access ... application as ... .*<br> 
    *However, we are not able to create this work or school account because ... is a domain that is federated with your on-premises AD.*<br> 
    *Please contact your admin to ensure you are properly configured in your on-premises AD and you can re-attempt to accept this invite.*<br>

#### Why this is happening
There is a good chance this is happening because your corporate email address is linked to a personal MSA/Live ID (work and personal accounts share the same name), which was a common practice with Microsoft Connect accounts. This practice is no longer supported by Microsoft and could lead to various issues. Please see [this blog post](https://cloudblogs.microsoft.com/enterprisemobility/2016/09/15/cleaning-up-the-azure-ad-and-microsoft-account-overlap/) for more details.

##### Fixes/Workarounds
The workaround is to rename your personal MSA account. See [this article](https://support.microsoft.com/en-us/help/11545/microsoft-account-rename-your-personal-account) for the detailed steps.


## Distribution Manager
You may receive an error message when you use Distribution Manager. This article contains information to help you troubleshoot these  error messages.

### Cannot Install Application

> Cannot continue.  The application is improperly formatted. <br>
> Contact the application vendor for assistance. <br>

This error indicates that [Microsoft .NET Framework 4.6.1 (x86/x64)](https://www.microsoft.com/en-us/download/details.aspx?id=49981)  required by Distribution Manager is not installed on your computer. All ClickOnce applications require that the correct version of the .NET Framework is installed before they can be run.

Click on the link to install [Microsoft .NET Framework 4.6.1 (x86/x64)](https://www.microsoft.com/en-us/download/details.aspx?id=49981).

### Cannot Launch Application 

> Object reference not set to an instance of an object. <br>

You may receive this error if you recently upraded from an older version of the application.

#### Fixes/Workarounds
The workaround is to delete the click-once application data.


The exact path can be determined by the following steps:
1. Pressing Ctrl + Alt + Del on the keyboard and selecting Task Manager
2. Find Microsoft Collaborate - Distribution Manager
3. Right click and select Open file location from the list of options
4. This should take you to a folder similar to:
> %LOCALAPPDATA%\Apps\2.0\Data\xxxxxxxx.xxx\xxxxxxxx.xxx\dist..tion_xxxxxxxxxxxxxxxx_0000.0000_xxxxxxxxxxxxxxxx\Data
5. Now go to the Data path (%LOCALAPPDATA%\Apps\2.0\Data), and search for a folder with the same name 
> dist..tion_xxxxxxxxxxxxxxxx_0000.0000_xxxxxxxxxxxxxxxx\Data
6.	Delete content of the folder
7.	Restart the application





