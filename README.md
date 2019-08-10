# SquarespaceUploader
Takes data from a json file (formatted as indicated) and uploads the item to Squarespace<br>
Language: Python 3.7

This program, as the description states, takes a specifically formatted python file database and uploads each entry to the Squarespace interface through the selenium library with Python. As of right now, its most useful purpose is defining the interface for entering data on Squarespace, and using that to input data. An example python file for the data is included as items.json

This program has been designed to do the following:
<ul>
  <li>Take the data from the json and use it directly</li>
  <li>Waits for inputs to appear or dialogs to dissappear before entering data</li>
  <li>Has the capability to upload text and images stored on the local machine</li>
  <li>Puts functionality for managing orders, inventory, and item updates into an easy to use GUI interface that can be used outside of the browser</li>
</ul>

Current Features:
<ul>
  <li>Updates existing items if and only if new information is found</li>
  <li>Adds new items if and only if they are not already in the database</li>
  <li>Moves items onto the store page/into storage based on the season (since this is meant for a clothing store)</li>
  <li>Item capability: Nearly all Men's clothing types, including pants, shirts, blazers, shorts, etc.</li>
</ul>

Usage:
<ol>
  <li>To start, download this repository, and make sure that your proper login information and store page(s) information is put into information.py</li>
  <li>Next, create your database file for accessing, make sure to put it in the same directory as the other files and to name it items.json, see <a href="https://github.com/mathemagician314/LSL_Scrapers">LSL_Scrapers</a> for my scrapers and how they format data</li>
  <li>Finally, make sure that all of the necessary modules are installed (mainly selenium and appJar), then run and watch the magic happen!</li>
</ol>


*Note: This program was originally designed to upload clothing items, so some fields may not be applicable to your item(s) or store(s). I've documented the code as well as I can, and have put small notes where personal modification would be necessary if your store is not currently compatible with this layout. If you have any questions or would like some better explanation/assistance on the process of adapting this program to your store, feel free to contact me either through GitHub or through my email.*
