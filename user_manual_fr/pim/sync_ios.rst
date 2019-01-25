======================
Synchroniser avec iOS
======================

Agenda
--------

#. Ouvrir les paramètres de l'application.
#. Selectionner Mail, Contacts, Calendars.
#. Selectionner Add Account.
#. Selectionner Other comme type de compte.
#. Selectionner Add CalDAV account.
#. Pour le serveur, renseignez ``example.com/remote.php/dav/principals/users/NOM-UTILISATEUR/``
#. Entrez votre nom d'utilisateur et votre mot de passe.
#. Selectioner Next.
#. Si votre serveur ne supporte pas SSL, un avertissement sera affiché.
   Selectioner Continue.
#. Si l'iPhone ne peut pas vérifier les informations du compte, poursuivez comme ceci :

   -  Selectionner OK.
   -  Selectionner paramètres avancés.
   -  Si votre serveur ne supporte pas SSL, assurez vous que SSL est positionné sur OFF.
   -  Changer le port pour 80.
   -  Retournez sur l'information du compte et cliquez sur Save.

Votre agenda sera maintenant visible dans votre application Agenda.


Contacts
--------

#. Open the settings application.
#. Select Mail, Contacts, Calendars.
#. Select Add Account.
#. Select Other as account type.
#. Select Add CardDAV account.
#. For server, type ``example.com/remote.php/dav/principals/users/USERNAME/``
#. Enter your user name and password.
#. Select Next.
#. If your server does not support SSL, a warning will be displayed.
   Select Continue.
#. If the iPhone is unable to verify the account information perform the
   following:

   -  Select OK.
   -  Select advanced settings.
   -  If your server does not support SSL, make sure Use SSL is set to OFF.
   -  Change port to 80.
   -  Go back to account information and hit Save.

You should now find your contacts in the address book of your iPhone.
If it's still not working, have a look at the `Troubleshooting Contacts & Calendar`_
guide.

.. _Troubleshooting Contacts & Calendar: https://docs.nextcloud.org/server/14/admin_manual/issues/index.html#troubleshooting-contacts-calendar
.. TODO ON RELEASE: Update version number above on release
