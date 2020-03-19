User session operations
========================

The login form appears on the screen automatically every time the TMS/X
is started (see the section Ошибка: источник перекрёстной ссылки не
найден). When the user is logged-on, the following session operations
are available from the separate menu that will pop-up, as the user
clicks its name in the TMS/X main menu:

|image0|

The Session menu contains the following items:

-  **Logout** — logs off the user from the TMS/X and suggest new
   session;

-  **Change password** — allows changing user's password (availability
   of the item depends on whether this functionality is provided in the
   current version of the software and cryptography settings).

.. rubric:: Logging out

The process of logging out of the software just invokes the logout
function and redirects you to the login page, where you can enter
credential of another user (e.g., in order to make an authorization of
entered payment).

.. rubric:: Changing own user password

Changing user’s password might be disabled depending on user's
permissions and cryptographic methods that are used in the current
version of the TMS/X.

When this option is able, call the **Session** > **Change password**
menu item. The dialog form will open:

|image1|

To change the password, type in your old password, the new one and
retype the new password once again, in the correspondent fields of the
form. The new password should be complex enough (from a security
viewpoint); otherwise, the TMS/X wouldn't accept it. Then press the
Change button to confirm the action. In the case of mistake, the error
message will be issued:

|image2|

Close the message box and try to fill in the fields of the password
changing form correctly. In case of success, you will immediately be
redirected to the login page. Enter your login and **new** password, as
usual:

|image3|

After successful connection, the TMS/X will inform you about new
password’s validity term:

|image4|

Dictionaries
=============

Call the **Dictionary** item of the main menu to get a list of the TMS/X
dictionary:

|image5|

Choose the necessary item from drop down list. Details of the
dictionaries are described below in correspondent sections.

Correspondents
---------------

Call the **Dictionary > Correspondents** item to open the table of
participants (institutions) registered the in the Central node:

|image6|

The table contains the following columns:

* **ID** – system internal identifier of the correspondent;

* **BIC** – bank identification code (BIC) of the correspondent;

* **Name** – name of the correspondent;

* **Head office** – name of the correspondents’ head office;

* **Code** – internal 6-symbols code of the correspondent (if exists);

* **TIN –** tax identification number of the correspondent (if exists);

* **SWIFT –** a flag (Yes/No) that defines, whether the correspondent is registered in the SWIFT BIC Directory;

* **Type –** code of the correspondent type (the DP – direct participant is default);

* **Modification date** – date and time, when the record was created or last modified.

Currencies
-----------

Call the **Dictionary > Currencies** menu item to open the table with a list and attributes of currencies:

|image7|

The table contains the following columns:

* **Code** – system code of the currency;

* **Name** – system name of the currency;

* **Decimal digits** – number of decimal digits in amount values that
   are expressed in the currency;

Participant accounts
---------------------

Call the **Dictionary > Participant Accounts** item to open the table of
accounts, registered in the in the Central node:

|image8|

The table contains the following columns:

* **ID** – system internal (numeric) identifier of the account;

* **Code** - code of the account;

* **Correspondent** - name of the correspondent of the participant, the
   account is referred to;

* **Type** - a type of the account;

* **Currency** - code of the currency (ISO) of the account;

* **BIC** – bank identification code (BIC) of the participant the
   account belongs to

* **Corr Account** - code of the correspondent account (if exists);

* **Modification date** – date and time, when the record was created or
   last modified.

Priorities
-----------

Call the **Dictionary > Priorities** item to open the table of
priorities that are registered in the in the Central node:

|image9|

The table contains the following columns:

* **Name** – name of the group, the priority is included into;

* **Value –** number of the priority;

* **Modification date** – date and time, when the record was created or
   last modified.

Reject reasons
---------------

Call the **Dictionary > Reject reasons** menu item to open the table
with a list of rejection reasons that are registered in the Central
node:

|image10|

The table contains the following columns:

* **Code** – rejection reason code;

* **Description** – rejection reason description.

Transaction type codes
-----------------------

Call the **Dictionary > Transaction type codes** item to open the table
of priorities that are registered in the Central node:

|image11|

The table contains the following columns:

* **Code** – transaction type code;

* **Name** – transaction type code name;

* **Subsystem** – subsystem (RTGS or ACH) TTC used.

.. Limit types
.. ------------
.. Call the **Dictionary > Limit types** item to open the table of limits
.. that are set in the Central node:
.. |image12|

Positions
----------

Call the **Dictionary > Positions** menu item allows to open the table
of Bank’s accounts to request account reports:

|image13|

The table contains the following columns:

* **Account code** – number of account;

* **Currency** – account currency;

* **Type** – account type.

To get access to account details and related reports and actions click
the blue link of the account code.

|image14|

Following actions with Settlement account available on corresponding
buttons:

* **Get account**– to send request for account report click the button
   and confirm sending;

* **Get customer account** – to send request for balance report click
   the button and confirm sending;

* **Get customer statement** – to send request for statement report
   click the button and confirm sending;

* **Get reservations** – to send limit request click the button and
   confirm sending;

* **Modify reservations** – to send request for set limit click the
   button and confirm sending.

Following actions with Clearing account available on corresponding
buttons on **Position** form:

* **Get Debit Cap** – to send request for the last value of debit cup
   click the button and confirm sending;

* **Set Debit Cap** – to send request for to defining a value of debit
   cup click the button and confirm sending:

* **Get account** – to send request for account report click the button
   and confirm sending.

Select the report in the table and click the ID hyperlink to get access
to the report, message details and related objects. The report
**Details** tab will be opened in a separate window (the message type,
direction and reference will be put into the header of the window):

|image15|

.. |image0| image:: media/image1.png
   :width: 7.00000in
   :height: 0.83333in
.. |image1| image:: media/image2.png
   :width: 4.23958in
   :height: 1.14514in
.. |image2| image:: media/image3.png
   :width: 3.62292in
   :height: 0.40347in
.. |image3| image:: media/image4.png
   :width: 2.60625in
   :height: 2.21667in
.. |image4| image:: media/image5.png
   :width: 3.66181in
   :height: 0.40139in
.. |image5| image:: media/image6.png
   :width: 1.64167in
   :height: 2.20000in
.. |image6| image:: media/image7.png
   :width: 6.98958in
   :height: 1.22014in
.. |image7| image:: media/image8.png
   :width: 6.98958in
   :height: 1.03611in
.. |image8| image:: media/image9.png
   :width: 6.98958in
   :height: 1.30417in
.. |image9| image:: media/image10.png
   :width: 6.98958in
   :height: 1.17986in
.. |image10| image:: media/image11.png
   :width: 6.98958in
   :height: 1.35000in
.. |image11| image:: media/image12.png
   :width: 6.98958in
   :height: 1.21667in
.. |image12| image:: media/image13.png
   :width: 6.98958in
   :height: 0.92639in
.. |image13| image:: media/image14.png
   :width: 6.98958in
   :height: 1.65625in
.. |image14| image:: media/image15.png
   :width: 6.98958in
   :height: 2.10833in
.. |image15| image:: media/image16.png
   :width: 6.72847in
   :height: 2.85208in
