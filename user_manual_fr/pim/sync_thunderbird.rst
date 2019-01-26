==============================
Synchroniser avec Thunderbird
==============================

Contacts
--------

Si vous êtes nouveau avec Nextcloud et Cardbook, voici ce dont vous avez besoin dans les moindres détails pour que tout fonctionne:

- `Thunderbird <https://www.thunderbird.net/>`_ pour votre système si l'application n'est pas déjà installée (Linux)
- `CardBook <https://addons.thunderbird.net/en-US/thunderbird/addon/cardbook/>`_ (une extension pour gérer les contacts dans  Thunderbird)

Après avoir installé CardBook et Thunderbird, opérez de cette façon:

1. En bas à gauche de l'écran des contacts dans Nextcloud, cliquez sur le bouton suivant:

.. image:: ../images/contacts_link.png

ce qui va afficher une URL ressemblant à celle-ci:
https://cloud.nextcloud.com/remote.php/dav/addressbooks/users/daniel/Thunderbird/

2. Cardbook se trouve en haut à droite de Thunderbird:

.. image:: ../images/cardbook_icon.png

3. Dans l'extension Cardbook de Thunderbird :

   -  "Adressbook > New Adressbook **Remote** > Next
   -  Rensignez vos informations de connection

.. image:: ../images/new_addressbook.png

4. Validez vos paramètres et cliquez sur Next, choississez alors le nom de votre carnet d'adresse et cliquez sur Next à nouveau.

.. image:: ../images/addressbook_name.png

5. Une fois installé, synchronisez votre carnet d'adresse en cliquant sur "Synchronize" dans le coin en haut à gauche de CardBook.
Vous allez voir votre carnet d'adresse rempli par nextcloud !

.. image:: ../images/synchronize_cardbook.png

Le reste des détails d'utilisation de Cardbook sont laissés au lecteur...

Agenda
--------

- `Thunderbird <https://www.thunderbird.net/>`_ pour votre système si l'application n'est pas déjà installée (Linux)
- `Lightning <https://addons.mozilla.org/en-US/thunderbird/addon/lightning/>`_ (une extension pour gérer les agendas dans  Thunderbird)

Après avoir installé Lighning et Thunderbird opérez de cette façon:

1. Allez dans vous agenda Nextcloud et cliquuez sur le menu "..." pour l'agenda que vous voulez synchroniser. Cela va vous afficher l'URL qui ressemble à ceci:
https://cloud.nextcloud.com/remote.php/dav/calendars/daniel/personal/

2. Go to the calendar view in Thunderbird and right click in the calendar menu to the left (where the names of the calendars are) to add a **New Calendar**.

3. Choose **On the network**

.. image:: ../images/new_calendar.png

4. Choose **CalDAV** and fill in the missing information:

.. image:: ../images/CalDAV_calendar.png

The rest of the details of dealing with Thunderbird Calendar are left to the reader...
