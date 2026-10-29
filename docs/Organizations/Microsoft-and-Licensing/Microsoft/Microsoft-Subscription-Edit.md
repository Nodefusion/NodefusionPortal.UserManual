---
sidebar_position: 3
---

# Microsoft Subscription Edit

This page shows and changes one subscription. Open it by selecting the subscription in the Online services tab on the [Microsoft](index.md) page.

The title is the subscription name, with its status, offer name and ID below it. At the top, three cards show **Term**, **Billing cycle** and **Term ends**.

Without the Manage level, the page shows a **View only** message and the fields cannot be changed. If the subscription is not active, a message explains that quantity and renewal cannot be changed.

## Subscription

- `Nickname*`: the name shown in the portal.
- **Licences**: the number of licences. You can only add licences here: the number cannot be lower than the current one. To use fewer licences from the next renewal, use **Licences at renewal** below.

## Renewal

- **Auto-renew**: shows the renewal date. Auto-renew can be turned off, but not turned on again on this page. After it is turned off, a message offers **Open Shop request**, which opens a [purchase request](../Shop/Create-Shop-Item.md) already filled in to renew the subscription for the next term.
- **Change licences or term at renewal**: available while Auto-renew is on. When switched on, it shows **Licences at renewal** and **Term at renewal** (Monthly or Annual). The change takes effect on the renewal date, not immediately.

The **Details** card shows the subscription ID. The page has no option to cancel a subscription.

## Send the change

Select **Send change request** to send your changes, or **Cancel** to go back without changing anything. A change is applied automatically, as soon as the request is sent, when the new number of licences is 20 or fewer, or when it differs by no more than 20 % from the current number. Other changes are sent to Nodefusion for approval: the current values stay until Nodefusion handles the request. If nothing was changed, a message asks you to change at least one field first.

## Notifications

- After sending: "Change request sent. Up to 20 licences or a 20 % change applies automatically; larger changes need approval." You then return to the Microsoft page. A change within the automatic limit is applied right away. A larger change is not applied yet: the current values stay until Nodefusion approves the request.
- Without any change: "Please modify at least one field before saving."
- If sending fails, an error message is shown and the form stays filled in.

## Example scenario

You have 20 licences of a Microsoft 365 subscription with a Monthly term, and you want to reduce them to 15 at the next renewal. Open the subscription, make sure Auto-renew is on, switch on **Change licences or term at renewal**, set **Licences at renewal** to 15 and select **Send change request**. The 20 licences stay until the renewal date, then the subscription renews with 15.
