DataBase
========

User information:
-----------------

* Id
* Nickname (public)
* Name (private, shared)
* Surname (private, shared)
* email (private, shared)
* Location: Country, city, postal code (private, shared)
* QR: Contains the nickname and id

Item information:
-----------------

* Id
* Name
* Type: Book, film (DVD & Bluray), CD, Videogame (PS3, XBOX, Wii, etc)
* Description (include other useful information: author for book or composer for CD)
* Picture (only the image path)
* Status: To share, reserved, borrowed
* Id owner
* QR: Contains the name, id and owner id

Sharing information:
--------------------

* Id
* Id owner
* Id borrower
* Id item
* State
* Date borrowed
* Date returned

iWant information:
------------------

* Id
* Id item
* Id requester
* Date requested

Feedback information:
---------------------

* Id
* Id author
* Id sharing
* Date
* Description

Statistics (calculated from database):
--------------------------------------

User:
* List of items to share (from item and owner id) - Private
* List of borrowed items (from sharing and owner) - Private
* List of iWant items (from iWant and item) - Private
* Number of items - Public
* Number of current borrowed items - Public
* Average borrowing time - Public
* Number of iWant - Public

Items:
* Number of times borrowed - Public
* Avegare borrowing time - Public
* Number of iWant - Public
