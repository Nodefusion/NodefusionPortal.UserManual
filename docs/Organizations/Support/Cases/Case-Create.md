---
sidebar_position: 1
---

# New case

Use the New case form to ask Nodefusion support for help. Open it with **New case** on the [Cases](index.md) page or on Home. Creating a case needs the access level Full access, Manage, Write or Support user.

Fields marked with `*` are required. If a field is missing or invalid, a summary of the errors appears at the top of the form and next to the fields.

## No active work service

If your organization has no active work service, the form is replaced by the message **You don't have an active work service**. A case cannot be created until you purchase and activate Nodefusion Managed IT Service. The message links to the service description and to a purchase request in the Shop.

## Before you start

The card next to the form offers three links:

- **MSP User Manual**: self-service guides for onboarding, offboarding and productivity.
- **Purchase request in Shop**: for sales, subscription renewals, pricing and similar questions.
- **TeamViewer QuickSupport**: download it if support needs to connect to your computer.

## Topic

- **Work service\***: the first work service is preselected. Choose another if your organization has several.
- **Subject\***: no subject is preselected. Subjects are grouped under headings that cannot be chosen, and a subject without a group stands among them by its name. Use **Other** when nothing else fits. Some subjects open a guided form in the Details card.

## Severity\*

Choose how strongly the problem affects your business:

- **C Important** (default)
- **B Urgent**
- **A Critical**

Choosing **A Critical** opens the dialog **Confirm critical severity**. Critical means Nodefusion works around the clock until the case is solved and you must be reachable the whole time. Select **Yes, I'm available** to confirm, or **Cancel** to keep the previous severity.

## Contact

- **Primary contact email\***: exactly one address, prefilled with your email. Replace it if someone else should handle the case. Tip: you can use a contact saved in [Organization Profile](../../Organization/Organization-Profile.md#contacts).
- **Phone number**: the number support can call. It is prefilled with the prefix `+ 385 9`; replace it with your number.
- **Additional CC emails**: optional. Separate several addresses with a semicolon (`;`) or a comma (`,`).
- **Preferred contact method\***: **Email** (default) or **Phone**.
- **Consent to call recording\***: active only when the contact method is **Phone**. Choose **Yes** or **No**. With **Email**, the consent is sent as No.

## Details

The Details card appears after you choose a subject. Its fields depend on the subject. If you change the subject to one with a different form, the fields of the form are cleared.

### Other subjects

All subjects without a guided form (including **Other**) use this form:

- **Title\*** and **Description\***: at least 2 characters each.
- **Attachments**: optional. Drag files into the area or select it to browse. You can add up to 3 files, 3 MB each. A file that is too large or over the limit is listed with an error and is not sent.

### User onboarding

- **First Name**, **Last Name**
- **Display Name\*** and **Username\***: at least 3 characters each
- **Office Phone**, **Mobile Phone**, **Department**, **Company**, **Office Location**
- **Street Address**, **City**, **State**, **Postal Code**
- **Country\***: default `HR`
- **License Group\***: default `Default`
- **Employee Id**, **Employee Type** (default `Employee`), **Manager**
- **Employee Hire Date**: default today
- **First Day of Work\***: default today
- **Note**

### User offboarding

- **Username\***: at least 3 characters
- **Mailbox Full access members**
- **Last Day of Work\***: default today
- **Allow receiving new email messages to mailbox until\***: default yesterday
- **Consent to retire/wipe all company data and operating system on user device(s)**: selected by default
- **Note**

### Credential reset

- **Username\***: at least 3 characters
- **Reset password**
- **Require re-register Multi-factor authentication**

### Device onboarding

- **Part Number**, **Serial Number**, **Primary Username**
- **OS**: Windows (default), iOS, Android, macOS or Linux
- **Note**

### Device offboarding

- **Device Hostname\***
- **Consent to erase all data and operating system reinstall on a device**: selected by default
- **Note**

## Create the case

The bar at the bottom of the page shows the chosen severity and subject. Select **Create case** to send the case, or **Cancel** to leave without saving.

What happens next depends on the subject:

- **User onboarding, User offboarding and Credential reset**: you stay on the form and the fields of the guided form are cleared. Work service, subject, severity and contact stay as they were, so you can quickly create the next similar case.
- **All other subjects**: the [details of the new case](Case-Details.md) open.

## Notifications

After the case is created, a success message appears. The case list updates by itself. If creating the case fails, an error message appears. The form stays filled in, so you can correct it and select **Create case** again. See [Messages and notifications](../../../index.md#messages-and-notifications) in Getting Started.
