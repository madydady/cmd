Working page organization
===========================

The application screen of the TMS/X consists of the following main
elements:

|image0|

-  Logo and horizontal main menu bar at the header;

-  Screen body that usually reflects currently opened table or object
   detail form;

-  Information bar that is located in the footer

The TMS/X main menu
====================

The TMS/X main menu is a horizontal bar at the top of the application
page. The main menu contains top-level items that correspond to separate
application’s sections. The top-level items may contain sub-items that
are opened automatically, when you click the parent menu item. Each
sub-item itself may contain one or few sub-items, etc. (multi-level
hierarchy):

|image1|

The user’s main menu contains the following submenus:

* **TMS/X** – closes currently opened page and returns to the home
   blank page;

* **Capture** – allows users to create a new operation (instruction) of
   selected type. See the section Ошибка: источник перекрёстной ссылки
   не найден below for details;

* **Monitoring** – allows users to monitor base objects and operations
   (such as transactions and messages) registered in the Central node
   system. See the section Ошибка: источник перекрёстной ссылки не
   найден below for details;

* **Dictionary** - displays dictionaries of correspondents, accounts,
   operation types and other accessory data that are used in payment
   preparation and processing. Operators can view, and Administrators
   can manage the dictionaries. See the section Ошибка: источник
   перекрёстной ссылки не найден below for details;

* **Reports** – allows users to view and print custom reports on
   monitoring transactions and user activity. See the section Ошибка:
   источник перекрёстной ссылки не найден below;

* **User tools** (shown as the user name’s icon with a drop down menu
   |image2|) – allows user to login on/off and change their password
   (See the section Ошибка: источник перекрёстной ссылки не найден below
   for details). Also displays the user login information.

   1. Informational bar

The following information is indicated at the bottom of the TMS/X page:

|image3|

-  The workplace registered name;

-  The workplace software current version and copyrights;

-  The name of current period and date of the business day (to see more
   details about a schedule of the day, just click the period name
   hyperlink. The schedule will be displayed in a separate window):

|image4|

-  The signs of active/inactive connection (to see more details, just
   click the sign hyperlink):

    |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1bcb1e9.PNG|

    |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML16d81f2.PNG|

The TMS/X tables
=================

TMS/X table layout
-------------------

The following interface elements present in the TMS/X tables
(dependently on the table data, some of them may be absent in a concrete
table):

|image7|

-  A name of the opened table,

-  The table’s toolbar with the buttons for calling actions, which will
   affect the table or manipulate its record. The toolbar is placed just
   above the table. The number of buttons may be various for specific
   tables (some buttons may absent in some tables). Typical actions are:

    |image8| - refreshes the table data (some tables (Transactions,
    Sustem events, etc.) are refreshed automatically and user can
    refresh other tables manually anytime via pressing the button);

    |image9| - adds a new record into the table (correspondent entry
    form will be opened in a separate window);

    |image10|- pops up a context menu (see the description of its items
    in sections 1.4.2, 1.8 and 1.7 below):

    |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML846440.PNG|

    |image12|- closes the table and returns to the home page of the
    TMS/X.

The row local toolbar with icons of actions, which only affect the
record, may be displayed in the last column of the table:

|image13|

Description of such actions will be given in sections, referred to
concrete tables.

-  Line of table header contains a set of descriptive names of the
   table's columns. You can sort the table's data in both ascending and
   descending order. Use the down-arrow icon, which becomes visible when
   the mouse pointer is over a column name: |image14|. You can also sort
   the table by the column's data by simply clicking on a column header.
   When the table is sorted by the column's data, it is indicated by an
   up-arrow (|image15|) or down-arrow (|image16|) in the column header.

-  The selected line is highlighted with a light grey color in the
   table.

-  When the screen window cannot hold the entire table, the scrollbar(s)
   will be displayed to make table data scrolling available.

-  Use the Search field for fast searching records in large tables. Type
   any fragment of value, which you intend to find among the table
   records, in the field. The table will immediately be filtered, so
   that the records, containing the specified fragment in their columns,
   will only remain:

|image17|

To return to the full table, just clear the Search field.

Displaying/hiding table's columns
----------------------------------

You can display or hide any table column, depending on what information
is more important. Call the table context menu and press the Column
visibility button from there:

|C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLef9a6f.PNG|

A list of the table column’s names will drop down:

|image19|

Click the column names in the list, which are not to be displayed (their
background color will change from blue to white):

|C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLf79a11.PNG|

Selected columns will immediately abandon the table:

|image21|

To return the hidden columns into the table, call the ‘Column
visibility’ option again and click the names of the hidden columns once
more (their background color will change to blue):

|C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLf79a11.PNG| |image23|

Selected columns will immediately appear in the table.

Filters in tables
------------------

You can apply filtering to the data, displayed in the most of the
tables. When the filtering options are available, the filter bar is
placed above the table. To set the filter, click the bar. Fill in the
necessary fields in the pop-up filter dialog box, then press the Filter
button inside:

|image24|

The table will be updated, so that only the records, which meet the
criteria, will remain. If filter field is a list, you can specify any
numbers of possible values from it in some filters:

|image25|

The content of the filter depends on the table’s matter.

Viewing/editing table record details
--------------------------------------

If the row record in the opened table has one or more fields that are
colored in blue, it means that you can view or edit the data from the
record in a separate form by simply clicking the hyperlink:

|image26|

A special multi-tab form with details of the record will pop-up, where
you can view or edit them:

|image27|

Printing table data
--------------------

To print the content of any table, call the table context menu and press
the Print button from there.

The printing page layout and standard printer manager dialog box will be
shown in a separate window. Make settings there and press its own Print
button to send the page to the selected printer.

Copying table data
-------------------

To copy a content of any table into a clipboard, call the table context
menu and press the Copy button from there. The information message will
be shown:

|image28|

Then you can paste the clipboard content into any textual editor or
other application, supporting OLE-technology

Exporting table data
---------------------

To convert the content of any table to the MS Excel file, call the table
context menu and press the Excel button from there:

|C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1e24092.PNG|

Confirm the operation in the pop up message box by pressing the Open or
Save button inside it. The name of the file will be generated
automatically, but you can change it by choosing the Save As option
instead of the Save.

Specify new file name and location and press the Save button in the
pop-up standard dialog box.

The table data will be opened or saved in the correspondent
application’s format:

|C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1f2214f.PNG|

Then you can edit the file by using standard tools of the application
(e.g., in order to prepare a report).

*Note:* I\ *n the case a filtering was applied to the table, the
filtered data will only be exported, but not the whole table.*

.. |image0| image:: media/image1.png
   :width: 7.07153in
   :height: 3.79097in
.. |image1| image:: media/image2.png
   :width: 7.00000in
   :height: 0.25000in
.. |image2| image:: media/image3.png
   :width: 0.47708in
   :height: 0.21875in
.. |image3| image:: media/image4.png
   :width: 6.98958in
   :height: 0.23889in
.. |image4| image:: media/image5.png
   :width: 6.72847in
   :height: 1.41597in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1bcb1e9.PNG| image:: media/image6.png
   :width: 3.09583in
   :height: 0.70903in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML16d81f2.PNG| image:: media/image7.png
   :width: 3.27708in
   :height: 0.74514in
.. |image7| image:: media/image8.png
   :width: 6.50000in
   :height: 3.20833in
.. |image8| image:: media/image9.png
   :width: 0.31250in
   :height: 0.28125in
.. |image9| image:: media/image10.png
   :width: 0.29167in
   :height: 0.26042in
.. |image10| image:: media/image11.png
   :width: 0.29167in
   :height: 0.23958in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML846440.PNG| image:: media/image12.png
   :width: 1.39236in
   :height: 0.95764in
.. |image12| image:: media/image13.png
   :width: 0.29167in
   :height: 0.25000in
.. |image13| image:: media/image14.png
   :width: 6.98958in
   :height: 0.65069in
.. |image14| image:: media/image15.png
   :width: 1.87500in
   :height: 0.30208in
.. |image15| image:: media/image16.png
   :width: 0.30208in
   :height: 0.25000in
.. |image16| image:: media/image17.png
   :width: 0.25000in
   :height: 0.25000in
.. |image17| image:: media/image18.png
   :width: 6.98958in
   :height: 0.78125in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLef9a6f.PNG| image:: media/image19.png
   :width: 1.55625in
   :height: 1.00764in
.. |image19| image:: media/image20.png
   :width: 6.97917in
   :height: 1.79167in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLf79a11.PNG| image:: media/image21.png
   :width: 1.54861in
   :height: 1.60208in
.. |image21| image:: media/image22.png
   :width: 6.72847in
   :height: 1.40486in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTMLf79a11.PNG| image:: media/image23.png
   :width: 1.59167in
   :height: 1.64583in
.. |image23| image:: media/image24.png
   :width: 1.32014in
   :height: 1.51875in
.. |image24| image:: media/image25.png
   :width: 6.50000in
   :height: 2.22083in
.. |image25| image:: media/image26.png
   :width: 2.50972in
   :height: 2.06250in
.. |image26| image:: media/image27.png
   :width: 6.84375in
   :height: 1.85000in
.. |image27| image:: media/image28.png
   :width: 6.98958in
   :height: 3.70000in
.. |image28| image:: media/image29.png
   :width: 6.50000in
   :height: 3.33472in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1e24092.PNG| image:: media/image30.png
   :width: 1.50000in
   :height: 0.93958in
.. |C:\\Users\\sazonov\\AppData\\Local\\Temp\\SNAGHTML1f2214f.PNG| image:: media/image31.png
   :width: 6.69306in
   :height: 2.47153in
