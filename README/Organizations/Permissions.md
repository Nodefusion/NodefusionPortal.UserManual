## Permissions

Users can see information regarding organization permissions and manage permissions for other users in the organization.

## Permission List

The Permissions table shows organization permission and the users those permissions are assigned to.
The table columns are:
  - Checkbox (used for selecting one or more rows)
  - Display Name
  - Permission

The Delete button deletes the selected permissions in table. 

:warning:**_NOTE:_**  
_Keep in mind that Delete permission action requires the affected users to refresh the access token (log out - log in)._

## Grant Permission
The Grant Permission form allows a user to request additional permission for himself or another user inside the organization. The request form consists of three fields:

Permission (field options values are: SupportUser, Read, Write, Manage and FullAccess)
Expires on (read-only field, set to current date + 3 days)
Invitation Email (user who will receive permission)
The button Grant Permission is disabled until the user fills in all fields. The user will receive an email with the activation token needed on the Organization Select page.

:warning:**_NOTE:_**  
_Keep in mind that the Invitation email field must be the one which user is (or will be) registered on Nodefusion Portal with. Upon permission activation, it will be checked if the token is generated for the correct user._