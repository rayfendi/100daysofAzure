## Manage Azure Active Directory Objects

## Introduction

I'm currently performing a tenant audit for an organization. I will be using Windows OS to perform this task. I'm going to navigate to Azure Active Directorhy to manage users and groups, perform bulk user updates, manage devices, and configure self-service password reset.

## Prerequisite

An Azure Premium P1 license and administrator permissions to create users and groups, manage devices and updates, and configure sspr.

## Instructions

Navigate to [https://aad.portal.azure.com](https://aad.portal.azure.com) and log in with your administrator account. On the portal homepage, click **Azure Active Directory**, select **Users**, then select **New user** for user accounts in your organization.

In the **Identity** section of the wizard, fill out the following information for new user:

- Enter the user name for the verified domain
- Enter the name of the user

In the **Password** section of the wizard, fill out the following information for new user:

- Create the password or auto-generate password to share with user

Skip down to the bottom of the page and select **Create**.

Overview of user account creation:<br/>
![Basic User account settings](./img/Create-an-user-account-in-Azure-AD.png)

Navigate to [https://aad.portal.azure.com](https://aad.portal.azure.com) and log in with your administrator account. On the portal homepage, click **Azure Active Directory**, select **Users**, then select **Invite user** for guest accounts for non-employees.

In the **Identity** section of the wizard, fill out the following information for guest user:

- Enter the email address

Skip down to the bottom of the page and select **Create**.


