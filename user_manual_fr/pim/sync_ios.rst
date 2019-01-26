======================
Synchroniser avec iOS
======================

Agenda
--------

#. Ouvrir les paramètres de l'application.
#. Selectionner Mail, Contacts, Calendars.
#. Selectionner Add Account.
#. Selectionner Other comme type de compte.
#. Selectionner le compte Add CalDAV.
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

#. Ouvrir les paramètres de l'application.
#. Selectionner Mail, Contacts, Calendars.
#. Selectionner Add Account.
#. Selectionner Other comme type de compte.
#. Selectionner le compte Add CardDAV.
#. Pour le serveur, renseignez ``example.com/remote.php/dav/principals/users/NOM-UTILISATEUR/``
#. Enter your user name and password.
#. Selectioner Next.
#. Si votre serveur ne supporte pas SSL, un avertissement sera affiché.
   Selectioner Continue.
#. Si l'iPhone ne peut pas vérifier les informations du compte, poursuivez comme ceci :

   -  Selectionner OK.
   -  Selectionner paramètres avancés.
   -  Si votre serveur ne supporte pas SSL, assurez vous que SSL est positionné sur OFF.
   -  Changer le port pour 80.
   -  Retournez sur l'information du compte et cliquez sur Save.


Vous devriez maintenant trouver vos codans le carnet d'adresse de votre iPhone.
Si cela ne fonctionne pas, consultez le guide `Troubleshooting Contacts & Calendar`_.

.. _Troubleshooting Contacts & Calendar: https://docs.nextcloud.org/server/14/admin_manual/issues/index.html#troubleshooting-contacts-calendar
.. TODO ON RELEASE: Update version number above on release
