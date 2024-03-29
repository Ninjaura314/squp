# GUI Guide

This project was made with the first implementation of the 
InventoryGui.pyw file as an example of a fully functional GUI interface 
for this code.

An overview of the pages is as follows:

## [Orders Page](./orders-page)

The first thing a user sees on startup, this page navigates the most 
commonly used part of the Squarespace Interface, the Orders page

## [Database Page](./database-page)

As the name suggests, this page shows the entire inventory of the store 
from the json file provided.

## [Updates Page](./updates-page)

This page shows the items that have changed and need updates (Note: 
slightly bugged, registers items with different color orders, but not 
important enough to fix yet)

## Inventory Management Page

This page actually consists of 3 sub-pages, each with its own 
distinct purpose:

### [Show/Hide Online Items](./inventory/show-hide)

As the name implies, this page exists to show and hide currently 
uploaded items on the front-facing store. In other words, this changes
what is shown on the front end.

### [Upload Offline Items](./inventory/upload-offline)

This page takes items stored on a local computer and uploads them to the
ecommerce page. This should be offline to ensure the content is correct
before displaying on the front end.

### [Stock Management](./inventory/stock-management)

This page allows for changing stock values, including limited to 
unlimited and vice versa, as well as specific value changes.

## [Create Edit Page](./create-edit)

This page does exactly as its name implies, it allows the user to 
create new items or update existing items in this interface, which has
all fields consolidated, and updates those items automatically in the 
ecommerce interface.

## [Menus](./menus)

A description of all of the menus in the menu bar of the application.
