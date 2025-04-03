Add Parameters to Workbook

**Workbook** parameters can be referred to as the input to conditions that are used to filter query results or to provide input queries. This section helps you to add parameters to a Workbook.

How to Add *Parameters* to a Workbook?

- Navigate to Workbooks

    - Hover on the Workbooks icon on the left navigation bar. It will display the folder-wise view of existing workbooks in the tenant (previously known as cluster).

Create a New Workbook

Click the plus icon at the top right corner of the Workbooks list page to create a new workbook. The following screen is displayed.

Enter and Execute a Query

Enter a query and <u> execute </u> it. The results will be displayed.

Apply Parameters

Parameters will be applied to the query result columns.

Multiple parameters can be added to a single workbook.

Click the Parameters icon on the top right corner of the screen to add parameters to a Workbook.

Define Parameters

The "Add Parameters" bar is added. Click this to define parameters for the Workbook.

Parameter Fields

Field Name

Description

Name

Enter a parameter name for the Workbook. Workbook field value to be parameterized.

Field Type

Indicates the field type. By default, the field type displayed is Text.

Default Value

Enter the parameterized value.

Save the Parameter

Click the Save icon to save the details. The parameter value added will be displayed above the query section of the workbook.

Using Parameters in Queries

Now, you can apply this parameter anywhere in a query in the following format:

AND $columnname=

Example

_fetch * from event where $Stream=FIREWALL AND $EvtLen= limit 1d

The above query will fetch and display only the details as per the value set in the EventLength parameter.

Using Parameters During Signal Investigations

During signal investigations, you can directly send a parameter value on demand and invoke the workbook.

| Field Name    | Description                                         |
|--------------|-----------------------------------------------------|
| **Name**      | Enter a parameter name for the Workbook.           |
| **Field Type** | Indicates the field type. Defaults to **Text**.   |
| **Default Value** | Enter the parameterized value.                 |

<div classname="blue-callout"> Start Your Trail. </div> (iska CSS jayega)