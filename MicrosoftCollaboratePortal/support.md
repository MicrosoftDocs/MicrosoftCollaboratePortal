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



## Issues with accessing Collaborate
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
There is a good chance this is happening because your corporate email address is linked to a personal MSA (LiveID), which was a common practice with Microsoft Connect accounts. This practice is no longer supported by Microsoft and could lead to various issues. Please see [this blog post](https://cloudblogs.microsoft.com/enterprisemobility/2016/09/15/cleaning-up-the-azure-ad-and-microsoft-account-overlap/) for more details.

#### Fixes/Workarounds




