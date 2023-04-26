## MS Subscriptions

MS Subscriptions works with Microsoft Subscriptions and Microsoft Cloud Tenants.

It has four pages. One displays existing MS Subscriptions, another allows users to create Microsoft Cloud Tenant, the third allows editing an existing NCE MS Subscription and the last allows creating new MS Subscriptions.

:warning:**_NOTE:_**  

Keep in mind that loading these pages can take some time due to numerous possible queries accessing Microsoft Partner specific APIs.

## MS Subscriptions

The MS Subscription page displays existing Microsoft Subscriptions that belong to the user and has a button at the top to create additional Microsoft Cloud Tenants.
Below the button is the information about Microsoft Subscriptions that belong to the user.

The information about subscriptions is divided by Microsoft Tenant. (if there are multiple tenants tied to your organization)
Information regarding subscriptions inside the tenant can be divided into three sub-parts.
The Tenant information regarding subscription is displayed vertically, one below the other.

### Microsoft Customer Agreement

The first part gives information regarding Microsoft Customer Agreement. Every user working with Cloud Tenant subscriptions needs to accept the Microsoft Customer Agreement.

When the agreement is not accepted to the user, a dialog screen will be displayed that will block the page until the customer agreement is accepted.

The dialog button will contain a form with five fields.
All the fields are required and must be filled.
First Name, Last Name, Phone, Email and Agreement Date.
Agreement date field cannot be set to a future date.

When all fields are set, the user can press the Save button and save the agreement.
The MS Subscription page will then be enabled, and the dialog screen will disappear.
Instead of the dialog screen, the user will see who gave the agreement in his organization and when it was agreed.

### Create Subscription

The second part consists of a single button "New Subscription" that opens a new page where the user can request new MS Subscriptions.

### MS Subscription Information

The third part gives information regarding MS Subscriptions.

It consists of four tabs. Each tab shows information for different MS Subscription types that belong to the user.

#### Azure

The Azure tab currently does not show information about Azure subscriptions that belong to the user.

#### Marketplace

The Marketplace tab currently does not show information about marketplace subscriptions that belong to the user.

#### Online Services

The Online Service tab shows MS Subscriptions that are of Billing Type License.

The tab has two parts.
The first part is the search text field that can search MS Subscriptions inside the DataGrid checking the values of the Friendly Name property.
The second part is The MS Subscription DataGrid. The DataGrid allows editing properties inside rows. DataGrid has pagination enabled and shows 10 rows per page.

DataGrid has seven columns:
- Friendly Name - This property cannot be edited inside DataGrid. It contains a link if the MS Subscription has additional editing options and will redirect the user to another page where he can make further changes to the MS Subscription.
- Offer Name - The property cannot be edited.
- Auto Renewal - The column uses a Checkbox component that the user can edit.
- Status - The property cannot be edited.
- Quantity - This property can be edited.
- Billing Cycle - The property cannot be edited.
- Action - It contains the Update button that will save the changes the user makes inside the row.

#### Software

The Software tab shows MS Subscriptions that are Entitlements.

The tab has two parts.
The first part is the search text field that can search MS Subscriptions inside the DataGrid checking the values of the Friendly Name property.
The second part is The MS Subscription DataGrid. DataGrid has pagination enabled and shows 10 rows per page.

DataGrid has two columns:
- Friendly Name
- Quantity