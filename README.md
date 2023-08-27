# Salesforce Snippets (Apex/LWC) README

## Introduction

Code snippets for Salesforce (Apex & LWC) directly in VS Code.

This contains the Trigger framework and many quick start for apex classes : Batches, Queuable...

The repository is Open Source, you can [contribute or modify snippets here.](https://github.com/yaacov9/salesforce-snippets--apex-lwc)
### How to use it ?
Simply use the prefix defined in the extension to trigger the snippet

![System debug](images/sysExample.gif)


## Features
### Apex Snippets
| # | Prefix | Description |
|:----------:|:---------|:---------|
| 1  |  sys  |  System.debug |
| 2  |  /d  |  Apex Class description |
| 3  |  /dm  |  Apex method description |
| 4  |  /batch  |  Scheduled Batch Class quick start |
| 5  |  /mock  |  General Mock HTTP Class |
| 6  |  /queueable  |  Queueable Batch Class quick start |
| 7  |  /api  |  HTTP REST Request API |
| 8  |  /RTID  |  Get Record Type Id without SOQL |
| 9  |  /testBatch  |  Test for Scheduled Batch Class quick start |
| 10 |  /MapList  |  Create a Map to List<sObject> Example : Map each Account Id to his Contacts List |
| 11  |  /trigger  |  Trigger Framework quick start |
| 12  |  /formData  |  Form data API quick start |
| 13  |  /fieldsMap  |  Get All fields from sObject |
| 14  |  /GoodJSONWRAPPERRES  |  Return in JSON format |
| 15  |  /Invocable  |  Flow Invocable Apex Method quick start |
| 16  |  /newList  |  Create new List |
| 17  |  /newSet  |  Create new Set |
| 18  |  /newMap  |  Create new Map |
| 19  |  /savepoint  |  Create SavePoint (for Rollbacks)|
| 20  |  /rollback  |  Use Savepoint to rollback |
| 21  |  /MapSOQL  |  Create a Map from a SOQL |
| 22  |  /ListSOQL  |  Create a List from a SOQL |
| 23  |  /SOQL  |  SOQL |
| 24  |  /schedulable  |  Apex Schedulable class quick start |

### JS LWC Snippets
| # | Prefix | Description |
|:----------:|:---------|:---------|
| 1  |  /static  |  import static ressource |
| 2  |  /dlStatic  |  download Static ressource |
| 3  |  /con  |  console.log |
| 4  |  /apexCall  |  Call Apex Method |
| 5  |  /apexImport  |  import Apex Methods |
| 6  |  /ShowToastImport  |  import ShowToastEvent |
| 7  |  /userPermissionImport  |  import Custom Permissions|
| 8  |  /labelImport  | import Custom Labels |
| 9  |  /wireMethod  |  @wire (Apex method) with wired method quick start |
| 10 |  /wireProperty  |  @wire (Apex Method) with wired property quick start |

### HTML LWC Snippets
| # | Prefix | Description |
|:----------:|:---------|:---------|
| 1  |  /spinner  |  Lightning-Spinner |


## Release Notes
### 1.0.1
Updating README
### 1.0.0

Initial release
- 24 Apex code Snippets
- 10 JS code Snippets for LWC
- 1 HTML code Snippets for LWC

---