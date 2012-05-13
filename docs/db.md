DataBase
========

User information:
-----------------

* Nickname (public)
* Id
* Name (private, shared)
* Surname (private, shared)
* email (private, shared)
* Location: Country, city, postal code (private, shared)
* List of items to share
* List of borrowed items
* QR: Contains the nickname and id

Item information:
-----------------

* Name
* Id
* Type: Book, film (DVD & Bluray), CD, Videogame (PS3, XBOX, Wii, etc)
* Description (include other useful information: author for book or composer for CD)
* Pic
* Status: To share, borrowed
* Owner id
* QR: Contains the name, id and owner id

Sharing information:
--------------------

* Id lender
* Id borrower
* Id item
* State
* Date borrowed
* Date returned

Statistics (calculated from database):
--------------------------------------

User:
* Number of items
* Number of current borrowed items
* Average borrowing time

Items:
* Number of times borrowed
* Avegare borrowing time
