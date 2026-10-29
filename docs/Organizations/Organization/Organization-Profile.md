---
sidebar_position: 2
---

# Organization profile

The page shows the organization details and, in three tabs, its contacts, billing services and group membership. It is available to Full access, Manage and Read. Only Full access and Manage can change anything, see [Access levels](Permissions.md#access-levels).

## Organization

The top card shows the name, address, VAT ID and Organization ID. It is read-only: to change these details, create a case with **New case** (see [Create a case](../Support/Cases/Case-Create.md)).

## Contacts

These are the active contacts linked to the organization (account). They are the people you can choose as the primary contact on a case and as the authorized contact on a Shop request.

The table shows name (with a **Coordinator** mark), email, work phone and mobile phone.

- **Edit** (pencil) opens the **Edit contact** dialog with First name, Last name, Email, Work phone, Mobile phone and the **Coordinator** switch. **Save** applies the change immediately.
- **Delete** (bin) asks for confirmation. **Send delete request** sends a request to Nodefusion. The contact is not removed immediately: it stays listed with the mark **Delete requested**.

## Billing

Invoices for each billing service go to its bill-to email. The table shows Billing service, Business unit and Bill-to email.

1. Select **Change** in the row (Manage and Full access only).
2. Enter the new email and select **Send bill-to change request**.

The request is sent to Nodefusion and is not carried out immediately, so the current address stays. Meanwhile the row shows "Requested: " with the new address and the mark **Change requested**.

## Membership

Lists the groups the organization belongs to, with a switch for each. Groups marked **Managed by Nodefusion** cannot be changed. When you change a switch, a bar at the bottom shows the number of unsaved changes; select **Save** to apply them or **Discard** to drop them.

## Notifications

- **Save** in **Edit contact**: a message confirms that the contact was saved.
- **Send delete request**: "Delete request sent. Nodefusion will review it." The contact is not removed yet: it stays in the list with the mark **Delete requested** until Nodefusion handles the request.
- **Send bill-to change request**: "Change request sent. Nodefusion will review it." The bill-to email is not changed yet: the current address stays and the requested one is shown below it until Nodefusion handles the request.
- **Save** in Membership: "Membership saved", or "N of M changes saved" if some groups failed; the failed ones stay as unsaved changes.

If an action fails, an error message appears. The dialog or the edited field stays as it is, so you can try again. If the page itself cannot load, it shows an error message with **Try again**. See [Getting Started](../../index.md#messages-and-notifications). This page does not keep a stored copy of its data; reload it to see the latest.
