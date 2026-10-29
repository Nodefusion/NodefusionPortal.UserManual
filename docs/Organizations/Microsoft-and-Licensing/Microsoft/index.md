---
sidebar_position: 1
---

# Microsoft

The Microsoft page lists the Microsoft cloud tenants of your organization and the subscriptions in each of them. Everyone with the Read level or higher can view it. Adding tenants and subscriptions and changing subscriptions requires the Manage level or Full access (see [Access levels](../../Organization/Permissions.md#access-levels)).

:::note
Microsoft data can take a few minutes to load, and a change in a Microsoft subscription can take up to 1 hour to show up here.
:::

To avoid loading the same data again and again, the portal keeps loaded data on your computer for 5 minutes. When cached data is shown, a line "Showing cached data, loaded ..." appears at the top of the page; select **Refresh** in that line to load fresh data.

## Add a Microsoft tenant

With the Manage level, the **Add a Microsoft tenant** card at the top of the page opens the [New Microsoft tenant](Microsoft-Tenant-Create.md) form.

## Tenants

Each tenant is shown as a card, one below another. Only one tenant is open at a time, and opening a tenant closes the others. Click a closed tenant, or its arrow, to open it; click the open one to close it. The first tenant is open by default. If your organization has only one tenant, it is always open. **Add subscription** on a closed tenant becomes available once the tenant is opened.

The card header shows the tenant name, the organization name (when it differs), the tenant domain and, with the Manage level, the status of the Microsoft Customer Agreement:

- **Microsoft Customer Agreement accepted.**
- **Microsoft Customer Agreement expired**: a message explains that the agreement expired and was not directly signed by the customer. Follow the link to the Microsoft 365 Admin Center and accept the new agreement there.

With the Manage level, **Add subscription** in the header opens the [Add subscription](Microsoft-Subscription-Add.md) page for that tenant.

## Subscription tabs

An open tenant has four tabs. **Online services** is shown by default.

### Azure

Shows only whether the customer has an active Azure Plan.

### Marketplace

Marketplace subscriptions are not listed on this page.

### Online services

A table of the subscriptions of the tenant. Search by subscription name or ID, sort by a column (by default the table is sorted by status) and move between pages.

| Column | Description |
|---|---|
| Subscription | Subscription name, with the offer name below it when it differs. |
| Quantity | Number of licences. |
| Term | Monthly or Annual. |
| Billing cycle | How the subscription is billed. |
| Renewal | Renews on, Ends on or Ended on, with the date. |
| Status | Subscription status. |

What a click on a row opens depends on the subscription:

- Most subscriptions open their own page with the subscription settings (nickname, licences and renewal), see [Microsoft Subscription Edit](Microsoft-Subscription-Edit.md).
- Some, older subscriptions open only the small **Change quantity** dialog (Manage level). Enter a higher number of licences and select **Send quantity change request**. A lower number is not accepted: the field turns red and the button stays disabled. The request is sent to Nodefusion and is not carried out immediately; the current quantity stays until then.
- Other rows cannot be clicked.

### Software

A table with the columns **Product** and **Quantity**. It has the same search, sorting and paging as Online services and is read-only.

See [Getting Started](../../../index.md) for how lists and tables work in general.

## Notifications

- After you send a quantity change request, a message tells you that it was sent. The quantity is not changed yet: the current quantity stays until Nodefusion handles the request.
- If an action fails, an error message is shown. The dialog stays open with your input.
