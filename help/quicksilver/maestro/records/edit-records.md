---
title: Edit records
description: You can edit record information in Adobe Maestro. You must create record types before you can start creating and editing records.
hidefromtoc: yes
hide: yes
recommendations: noDisplay, noCatalog
exl-id: 981b8e44-b548-4f94-bf89-5f5dec3a6166
---
<!--update the metadata with real information when making this avilable in TOC and in the left nav-->

# Edit records

>[!IMPORTANT]
>
>The information in this article refers to Adobe Maestro which is a new offering from Adobe Workfront. 
>
>Currently, Adobe Maestro is part of a beta program which is open to a limited number of customers. You must be a Workfront customer to use Maestro capabilities.
>
>Contact your account representative for more information about joining the beta program for Maestro.
>
>For information, see [Adobe Maestro overview](../maestro-overview.md).

You can edit record information in Adobe Maestro. You must create record types before you can start creating and editing records. 
For information, see [Create record types](../architecture/create-record-types.md).

<!-- mention in here that the fields in the Details view are the same as the ones in the table view -- this article is linked from the Manage record views one to refer to this info-->

## Access requirements

You must have the following access to perform the steps in this article: 

<table style="table-layout:auto">
 <col>
 </col>
 <col>
 </col>
 <tbody>
    <tr>
<tr>
<td>
   <p> Product</p> </td>
   <td>
   <p> Adobe Workfront</p> </td>
  </tr>  
 <td role="rowheader"><p>Adobe Workfront agreement</p></td>
   <td>
<p>Your organization must be enrolled in the Adobe Maestro closed beta program. Contact your account representative to inquire about this new offering. </p>
   </td>
  </tr>
  <tr>
   <td role="rowheader"><p>Adobe Workfront plan</p></td>
   <td>
<p>Any</p>
   </td>
  </tr>
  <tr>
   <td role="rowheader"><p>Adobe Workfront license</p></td>
   <td>
   <p>Any</p> 
  </td>
  </tr>
  
  <tr>
   <td role="rowheader"><p>Access level configurations</p></td>
   <td> <p>There are no access controls for Maestro </p>  
</td>
  </tr>
<tr>
   <td role="rowheader"><p>Permissions</p></td>
   <td> <p>Contribute or higher permissions to a workspace</a> </p>  
   <p>System Administrators have permissions to all workspaces, including the ones they did not create</p>
</td>
  </tr>
<tr>
   <td role="rowheader"><p>Layout template</p></td>
   <td> <p>Your Workfront or group administrator must add the Maestro area in your layout template. For information, see <a href="../access/access-overview.md">Access overview</a>. </p>  
</td>
  </tr>

 </tbody>
</table>

## Considerations about editing records

* You can edit records that you or another user created. <!--will change with access levels-->
* You cannot edit fields that are linked from other records or fields that contain calculations. 
* If the records you display are linked to other records, the new information of the records that you are editing reflects on the linked records. 
* You cannot edit records in bulk. <!--this will probably change-->
* URLs are recognized as links in single-line text field types only when they start with the following: http://, https://, ftp://, or www. . 
* You can use the following Rich Text formatting options when editing a Paragraph-type field:

    * Bold
    * Italic
    * Underline 
    * Add a link
    * Add a bulleted list
    * Add a numbered list

## Edit records

You can edit a record from the following areas:

* [From the Details page of a record](#edit-a-record-from-the-records-details-page)
* [From the table view of a record type](#edit-a-record-from-the-record-type-table-view) 

### Edit a record from the record's Details page

{{step1-to-maestro}}

The workspace that you access last opens. 

1. (Optional) Click the downward-pointing arrow to the right of the workspace name to select the workspace whose records you want to update. 
1. Do one of the following:

    * From a Table view, click the name of a record. 
    * From the Table view, hover over the name of a record, then click the **More** menu ![](assets/more-menu.png), then click **View**

        ![](assets/contextual-menu-for-record-row.png)
    * From a Timeline view, click a record bar. 

    The record **Details** page opens.

1. Click the **More** menu ![](assets/more-menu.png) to the right of the record name, then click **Edit**

    Or

    Click inside any editable field on the Details page to edit the information. 

    ![](assets/more-menu-options-from-record-details-page.png) <!--ensure the options have not changed or been renamed-->

1. Click **Save changes**. <!--logged a bug for this - this needs to be "Save"-->

### Edit a record from the table view of a record type

{#step1-to-maestro}

  The workspace that you accessed last opens. 

1. (Optional) Click the downward-pointing arrow to the right of the workspace name to select the workspace whose records you want to update. 
1. Click a record type card. 

    The record type page opens. 
1. (Conditional) From the **View** drop-down menu in the upper-right corner of the table, select a **Table** view. This should be the default view, unless you viewed the record type in the timeline view when you accessed it last. 

    The records associated with the selected record type display in the table view. 
1. Click inside the row of a record to start editing information about the record inline.

    ![](assets/edit-record-paragraph-field-with-formatting-table-view.png)
1. Press **Enter** on your keyboard or click outside of a row to save your changes. The changes are saved automatically. A Saved indicator displays briefly in the upper-right corner of the table view to show that the changes were saved. 

    >[!NOTE]
    >
    >  You cannot edit information for the following fields, as they are read-only and Workfront updates them automatically: 
    >  
    >  * Linked fields that are created by connecting record types. For more information, see [Connect record types](../architecture/connect-record-types.md).
    >  * Fields of the following types: Created by, Created date, Last modified by, Last Modified date


1. (Optional) Copy one or multiple existing values of a field, then paste them into a field of the same type on another record, then click **Enter** on your keyboard to save your changes. 

    >[!NOTE]
    >
    >Consider the following:   
    >
    >* You cannot copy information from another source, other than a Maestro field of the same type as the field you paste the information in.  
    >
    >* You cannot copy and paste field values in the Details area of a record. This functionality is supported only in the table view of a record type.  
    >* You cannot copy and paste field values for the following field types:   
    >
    >
    >    * Linked fields that are created by connecting record types. You can copy and paste linked record fields. For more information, see [Connect record types](../architecture/connect-record-types.md). 
    >    * Fields of the following types: Created by, Created date, Last modified by, Last Modified date 
    
1. (Optional) Use the following keyboard shortcuts to undo or redo editing or copying and pasting record information: 

    * CTRL + Z (⌘ + Z for Mac) to undo a change 
    * CTRL + Shift + Z (⌘ + Shift + Z for Mac) to redo a change 