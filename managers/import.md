### Import multiple items

> _Available for: [Managers](/managers/manager.md) and [Administrators](/admins/admin.md)_

On the [Recommendations](/visitors/recommendations.md), [Actions](/visitors/actions.md), [SDG Targets](/visitors/sdg-targets.md), and [Indicator](/visitors/indicators.md) list views you will, once authorised, find an 'Import' button (circled in screenshot below ) to start adding multiple items at once - a time-efficient way to add new items:

![](/assets/m-action-import.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

> When importing it is only possible to import actual item attributes (for recommendations this would be Title, Reference, Accepted Status and Accepted Response) but not any associations (e.g. thematic clusters, human rights body and cycle, etc.) that will have to be set up manually.

#### Batch Import Screen

![](/assets/m-batch-import.png)
_Screenshot from demo site ([demo.impactoss.org](https://demo.impactoss.org)) - all content for demo purposes only_

For all items the batch import screen (pictured above) allows you to
1. Download a CSV template that specifies all the available fields that you can import (specfic to each iotem type). If the template structure is not used then the batch import will not work. To start you should download the template, open it in Excel, copy and paste their data into this file and then save it using an appropriate file name, and most importantly using the **correct encoding option: CSV UTF-8 (comma-delimited)**. It is also important to keep the first row as this identifies the fields - please remove however the 2nd row that only provides additional information for each field type
2. Once saved use the 'select file' button and upload the file from your computer. The application will first analyse your file and inform you about the number of items found. Then once you click 'Import ...' (not pictured) the application will try to create each item one by one, raising any errors it may encounter in the process.

> Note: the batch import feature will set the publication status to "Draft" - you will still have to make them public once you have reviewed and linked them