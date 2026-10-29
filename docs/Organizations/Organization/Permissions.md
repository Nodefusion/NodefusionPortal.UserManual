---
sidebar_position: 3
---

# Permissions

The page shows who can open the organization in the portal and with which access level. It is available to Full access, Manage and Read. Only Full access can invite users and remove access.

## Users

The table lists each **User** and their **Access level**. Use **Search name** to find a user and the column headers to sort.

The **Access summary** card shows how many users have each level. Select a level to filter the table, or **All users** to show everyone again.

## Invite user

1. Select **Invite user** at the top right of the page. The button is there even when the user list is empty or cannot be loaded.
2. Enter **Email\***. It must be the email the person registers and signs in to the portal with, otherwise the token cannot be activated.
3. Choose **Access level** (the default is Read).
4. Select **Send invitation**.

The person receives an email with an access token, valid for 3 days. They activate it on the organization selection page, see [Activate token](../index.md#activate-token), and must sign in again afterwards.

## Remove access

1. Tick one or more users (the tick box in the header selects all shown users).
2. Select **Remove access** and confirm in the dialog.

Removed users can no longer open the organization and are signed out. At least one Full access user must remain, otherwise **Remove access** is disabled. While access is being removed, the dialog cannot be closed. If removal fails for some users, they stay selected so you can try again.

## Access levels

An access level is set per organization. The same person can have different levels in different organizations.

| Page | Full access | Manage | Write | Read | Support user |
|---|---|---|---|---|---|
| Home | Yes | Yes | Yes (message and New case only) | Yes | Yes (Cases card only) |
| Cases | Yes | Yes | No (can create a case) | Yes | Yes |
| Work Services | Yes | Yes | No | Yes | No |
| Organization profile | Yes | Yes | No | Yes | No |
| Permissions | Yes | Yes | No | Yes | No |
| Shop | Yes | Yes | No | Yes | No |
| Roadmaps | Yes | Yes | No | Yes | No |
| Microsoft | Yes | Yes | No | Yes | No |
| Subscriptions | Yes | Yes | No | Yes | No |
| Domains | Yes | Yes | No | Yes | No |
| Crohoster | Yes | Yes | No | Yes | No |
| Feedback | Yes | Yes | Yes | Yes | No |
| About | Yes | Yes | Yes | Yes | Yes |

Actions limited to higher levels:

- **New case**, comments and status changes on a case: Full access, Manage, Write and Support user (not Read).
- **New request** in the Shop: Full access, Manage and Read.
- Edit and delete contacts, group membership: Full access and Manage.
- Change bill-to email, change subscription quantity, edit subscriptions, add a Microsoft tenant or subscription, request a domain or hosting account: Full access and Manage.
- Invite user, remove access and accept the [customer agreement](../../Customer-Agreement.md): Full access only.

A page that your level does not include is not shown in the menu.

## Notifications and cached data

- **Send invitation**: "Your permission grant request has been processed."
- **Remove access**: "Access removed". If it fails for some users, the dialog says how many were removed.
- If an action fails, an error message appears. The dialog stays open so you can try again.
- The portal keeps the user list on your computer for 5 minutes. The refresh button at the start of the toolbar above the table loads fresh data. See [Getting Started](../../index.md#cached-data).
