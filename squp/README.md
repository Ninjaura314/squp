
SquarespaceUploader
===================

Takes data from a json file (formatted as indicated) and uploads the item to Squarespace

Language: Python 3.7

This program, as the description states, takes a specifically formatted python file database and uploads each entry to the Squarespace interface through the selenium library with Python. As of right now, its most useful purpose is defining the interface for entering data on Squarespace, and using that to input data. An example python file for the data is included as items.json

This program has been designed to do the following:
- Take the data from the json and use it directly
- Waits for inputs to appear or dialogs to dissappear before entering data
- Has the capability to upload text and images stored on the local machine
- Puts functionality for managing orders, inventory, and item updates into an easy to use GUI interface that can be used outside of the browser

## Current Features:
- Updates existing items if and only if new information is found
- Adds new items if and only if they are not already in the database
- Moves items onto the store page/into storage based on the season (since this is meant for a clothing store)
- Item capability: Nearly all Men's clothing types, including pants, shirts, blazers, shorts, etc.

## Usage:
1. To start, download this repository, and make sure that your proper login information and store page(s) information is put into information.py
2. Next, create your database file for accessing, see example_items.json for formatting details
3. Finally, if you need to add new fields, modify the interface.py file between the necessary comments to rename the fields to what you need them to be


*Note: This program was originally designed to upload clothing items, so some fields may not be applicable to your item(s) or store(s).*
*I've documented the code as well as I can, and have put small notes where personal modification would be necessary if your store is not currently compatible with this layout.*
*This includes the automated email sending, see companyemail.txt for the base template I used and make changes as needed.*
*If you have any questions or would like some better explanation/assistance on the process of adapting this program to your store, feel free to contact me either through GitHub or through my email.*
