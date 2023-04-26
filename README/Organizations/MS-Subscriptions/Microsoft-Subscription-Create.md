## Microsoft Subscription Create

:warning:**_NOTE:_**  
_Keep in mind that loading these pages can take some time due to possible numerous queries accessing Microsoft Partner specific APIs. _

The page contains three tabs each showing different types of MS Subscriptions the user can request to be created.

### Online Services

The tab consists of two parts.
The first part is a search textbox that searches MS Subscriptions by their Name or Id.
The second part shows a DataGrid that lists all the MS Subscriptions that can be requested. The DataGrid row for the chosen MS Subscription needs to be filled and the request sent to begin the create operation.
The DataGrid has enabled pagination and shows 10 rows inside the page. It has five columns. 

The first column is Product. The property cannot be edited.
The second column is Sku. Thie property can be edited. It is a select component where the user chooses one of the options provided. This property can be seen after the user clicks the Get details button for the specific row.
The third column is Term Duration. This property can be seen and edited but only after the Sku has been chosen. Then the application loads appropriate term duration based on the sku and display them in select component.
The fourth column is Quantity. It is a number input field that can be seen and edited only after the Sku has been chosen.
The fifth column is Action. It contains two buttons. The first button is Get Details that when clicked displayed the details for the specific product inside the same row.
After the action is finished a new button is displayed. The Create button sends a request to create a new subscription for the user.

### Perpetual Software

The tab consists of two parts.
The first part is a search textbox that searches MS Subscriptions by their Name or Id.
The second part shows a DataGrid that lists all the MS Subscriptions that can be requested. The DataGrid row for the chosen MS Subscription needs to be filled and the request sent to begin the creation operation.
The DataGrid has enabled pagination and shows 10 rows inside the page. It has four columns.

The first column is Product. The property cannot be edited.
The second column is Sku. Thie property can be edited. It is a select component where the user chooses one of the options provided. This property can be seen after the user clicks the Get details button for the specific row.
The third column is Quantity. It is a number input field that can be seen and edited only after the Sku has been chosen.
The fourth column is Action. It contains two buttons. The first button is Get Details that when clicked displays the details for the specific product inside the same row.
After the action is finished a new button is displayed. The Create button sends a request to create a new subscription for the user.

### Software Subscription

The tab consists of two parts.
The first part is a search textbox that searches MS Subscriptions by their Name or Id.
The second part shows a DataGrid that lists all the MS Subscriptions that can be requested. The DataGrid row for the chosen MS Subscription needs to be filled and the request sent to begin the creation operation.
The DataGrid has enabled pagination and shows 10 rows inside the page. It has five columns. 

The first column is Product. The property cannot be edited.
The second column is Sku. Thie property can be edited. It is a select component where the user chooses one of the options provided. This property can be seen after the user clicks the Get details button for the specific row.
The third column is Term Duration. This property can be seen and edited but only after the Sku has been chosen. Then the application loads appropriate term duration based on the sku and displays them in select component.
The fourth column is Quantity. It is a number input field that can be seen and edited only after the Sku has been chosen.
The fifth column is Action. It contains two buttons. The first button is Get Details that when clicked displays the details for the specific product inside the same row.
After the action is finished a new button is displayed. The Create button sends a request to create a new subscription for the user.