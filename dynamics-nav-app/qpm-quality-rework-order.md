---
title: "Quality Process Management - Quality Rework Order"
author: "Nosheen Mahate"
---

# Quality Rework Order

## Overview
The Quality Rework Order list page shows the Quality Orders that have been assigned for reworking. On the individual Quality Rework Order, the FactBox on the right gives summary information, for example Source ID shows the original Production Order that the lines came from. When a Rework Order is created, it takes it out of the old Lot Number and puts it against a new Lot Number, this can be seen in the Item Ledger Entries. Warehouse Entries will show it being taken out of the original bin and into the Rework Bin, using a Reclass Journal. This stock will then be consumed in a Production Order using the function Reserve Rework Stock. 

## General
### No.
The No. assigned to this Quality Rework Order. This is chosen by what is set up on the Quality Process Management Setup page.

### Document Date
The date the document was created. 

### Status
The current Status of the document. This is set to In Progress when the document is created.

### Source Type
The ID for where this document was created from. This is the Table ID. E.g. When the Quality Order is created from a Production Order, this will be 5405.

### Source Subtype
The Source Type of where the document was created from. E.g. When the Quality Order is created from a Production Order where the Source Type is Item. The Source Subtype will be Item. This corresponds to option 0. 

### Source ID
The No. of the document from where this Quality Order was created. E.g When the Quality Order is created from a Production Order, the Production Order No. with be stored in this field. 

## Page Actions
### Post
This will post the reworked item lines and create ledger entries for the order. The posted reworked item can later be used on a Sales Order or in Production Order.

##Lines
### Item No.
The Item No. to be reworked and quality checked.
### Quantity Passed
The number of items which have already passed the Quality Testing Actions.
### Quantity For Rework
The number of items which are being reworked.
### Quantity Scrapped
The number of items which have been scrapped from this Quality Order.
### Rework Quantity Available
The remaining quantity of the item that needs reworking

## Line Actions
### Rework Defect Codes
ework Defect Code and Quantity of rework for an item. 
### Item Tracking Lines
The Lot No. this item is tracked against.
### Testing Actions
Opens the Quality Order Line Actions page. Search **Quality Order Line Actions** for more. Populate the Result and set the test to Completed to continue with the order.

## See Also
[Quality Process Management Overview](.\qpm-overview.md)
[Using Quality Process Management](.\qpm-using.md)
[Quality Orders](.\qpm-quality-order.md)