---
sidebar_position: 2
---

# Subscriptions

The Subscriptions page lists the services billed to your organization. It is available with the Read level or higher. It has two tabs, each with the number of items in its name.

Both tabs have a search field (name, product or vendor number) and can be sorted by column. By default the subscriptions with the latest end date are shown first. See [Getting Started](../../index.md) for how lists work in general.

## Subscriptions

Subscriptions you can change. The columns are **Name**, **Product**, **Quantity**, **Start date** and **End date**.

With the Manage level, each row has a **Change** button (on small screens **Change quantity**) that opens a dialog showing the current quantity and a **New quantity** field. Select **Send quantity change request** to send it; the button is disabled while the quantity is unchanged.

The change is sent to Nodefusion and is not carried out immediately. The current quantity stays until Nodefusion applies it, and the row shows **Change requested**.

## Other subscriptions

Subscriptions you can see but not change here. The columns are **Name**, **Product**, **Quantity**, **Start date**, **End date** and **Vendor number**. This tab is read-only.

To avoid loading the same data again and again, the portal keeps loaded data on your computer for 5 minutes. When cached data is shown, a line "Showing cached data, loaded ..." appears at the top of the page; select **Refresh** in that line to load fresh data.

## Notifications

After you send a quantity change request, the message "Change request sent. Nodefusion will review it." is shown. The quantity is not changed yet: the current quantity stays and the row shows **Change requested** until Nodefusion handles the request. If sending fails, an error message is shown and the dialog stays open with your input.
