---
slug: /
sidebar_position: 1
---

# Nodefusion Portal User Manual

## Getting Started

You can visit Nodefusion Portal at URL: [https://portal.nodefusion.com](https://portal.nodefusion.com)

### Log in

Select **Log in** at the top right of the page. You can sign in with an existing account provider such as a Google account or a Microsoft account (personal, or work or school Microsoft 365).

After you sign in, you stay on the page you opened. If you have access to more than one organization, [choose the organization](Organizations/index.md) you want to work in.

### Preview version

There is a Public Preview version on a different URL: [https://portal-preview.nodefusion.com](https://portal-preview.nodefusion.com)

## What you see on the screen

### Top bar

- **Nodefusion logo**: takes you to the organization selection page.
- **Organization name**: shows the organization you are working in. Select it to open the **Organizations** menu with all your organizations and your access level in each of them. An organization that has not accepted the latest Nodefusion Customer Agreement is marked **Customer agreement required**; opening it shows the [customer agreement](Customer-Agreement.md). **All organizations** at the bottom takes you to the organization selection page. If you choose another organization, you stay on the same page in that organization. Pages that show a single item, such as one case, return to their list.
- **Bell**: the notifications of your current visit, see [Messages and notifications](#messages-and-notifications).
- **Your name**: opens your profile with your email, the current organization with your access level, the theme and **Sign out**. The theme can be **System** (follows your device settings), **Dark** or **Light**. The choice is remembered in your browser.

### Menu on the left

The menu is grouped like the sections of this manual:

- **Organization**: Home, Organization profile, Permissions
- **Support**: Cases, Work Services, Roadmaps
- **Microsoft & licensing**: Microsoft, Subscriptions, Shop
- **Hosting**: Domains, Crohoster
- **Feedback** and **About** at the bottom

You only see the pages your [access level](Organizations/Organization/Permissions.md#access-levels) allows. Use **Collapse menu** or **Expand menu** at the bottom of the menu to switch between the full menu and a narrow menu with icons. Until you choose an organization (or while it has not accepted the customer agreement), the menu only offers **Select organization** and **About**.

### Bottom of the page

The bottom line shows a link to the **User manual** and a link to **About**. The portal and API versions are shown on the About page.

## Lists and tables

Most pages show a list of items in a table.

- The number of items is shown above the table, for example "12 requests".
- Use the search field to find items. Some pages also have filters, for example the Cases page.
- The button for creating a new item (for example **New case**) is on the right above the table.
- Select a column title to sort by that column. Select it again to reverse the order.
- Below the table you can choose **Rows per page** (10, 25 or 50) and move between pages.

## Forms

- Required fields are marked with `*`.
- If you submit a form with missing or invalid data, a summary appears at the top, for example "Fix 2 fields to continue." Select a field name in the summary to jump to that field.
- The buttons that submit or cancel a form are in a bar at the bottom of the page, above the bottom line.
- Some actions are not carried out immediately. The portal sends them to Nodefusion as a request. The page tells you so, and the current value stays as it was until Nodefusion has handled the request.

## Messages and notifications

After you save, send or change something, a short message appears at the bottom of the page, for example "Comment sent to support". If something goes wrong, an error message appears instead and stays a little longer. You can close it with the X.

The **bell** in the top bar keeps these messages for your current visit, newest first. A number on the bell shows how many there are. A new notification only changes the number; it does not open the list. In the list you can:

- select **Show details** to see the technical message and the Correlation ID,
- select **Copy for support** to copy these details and send them to Nodefusion support,
- select the X (**Dismiss**) to remove one notification, or **Clear all** to remove all.

If a page, card or tab cannot be loaded, a message appears in its place:

- **You don't have access to this.** Your access level does not allow it. Ask a user with Full access in your organization.
- **Not found.** The item may have been removed.
- **Too many requests.** Wait a moment and select **Try again**.
- **Something went wrong.** Select **Try again**. If it keeps happening, select **Copy for support** and send the text, including the Correlation ID, to Nodefusion support.

If a form or dialog cannot be submitted because of an error, it stays as you filled it in, so you can submit it again. Each page describes the messages it shows in its **Notifications** section.

## Cached data

To make pages open quickly, the portal saves the data it has loaded on your computer for 5 minutes. When you open the page again within that time, it is shown straight away instead of being loaded again. A line at the top of the page then says "Showing cached data" and when it was loaded.

Select **Refresh** in that line (or the refresh button at the start of the toolbar above a table) to load fresh data. The saved data is also cleared when you reload the page or sign out, and after you change data in the portal.

## Phones and tablets

The portal also works on phones and tablets. On a tablet the menu is narrow and shows only icons. On a phone, open the menu with the menu button at the top left; it closes when you choose a page. Tables are shown as lists of cards, and **Sort by** replaces the clickable column titles.

## New version of the portal

When a newer version of the portal is available, a message appears with a countdown of 5 seconds. The page then reloads by itself, or immediately if you select **Reload now**. While it reloads, an "Updating" screen is shown.
