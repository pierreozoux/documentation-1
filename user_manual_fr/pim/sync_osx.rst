========================
Synchroniser avec macOS
========================

Installer vos comptes
-------------------

Dans les étapes suivantes vous allez ajouter les ressources de votre serveur pour **CalDAV** (Agenda) 
et **CardDAV** (Contacts) à votre Nextcloud.

1. Ouvrir **system preferences** de votre ordinateur macOS

2. Aller à **Internet Accounts**

.. figure:: ./images/macos_1.png

3. Cliquer sur **Add Other Account...** et sur **CalDAV Account** pour l'agenda ou
**CardDAV Account** pour les contacts.

.. figure:: ./images/macos_2.png

.. note:: Vous ne pouvez pas installer Agenda et Contacts sur le même compte. Vous devez les configurer dans **des comptes distincts"".
4. Selectionner **Advanced** comme type de compte et renseignez vos identifiants:

   **Username**: Votre nom d'utilisateur Nextcloud ou adresse mail
   **Password**: Votre mot de passe d'application (`App-password/token <https://docs.nextcloud.com/server/stable/user_manual/session_management.html#managing-devices>`_)
   **Server Address**: l'URL de votre serveur Nextcloud (p.e. https://cloud.example.com)
   **Server Path:** /remote.php/dav/principals/users/[votre nom d'utilisateur]
   **Port:** 443
   **Use SSL:** Yes

.. figure:: ./images/macos_3.png

5. Cliquer sur **Sign In**.

**For CalDAV (Calendar):** You can now select, with which applications you want
to use this resource. In the most cases, this will be the "Calendar" application,
sometimes you may also want to use it for your **Tasks and reminders**.

.. figure:: ./images/macos_4.png

Troubleshooting
---------------

- macOS does **not** support syncing CalDAV/CardDAV over non-encrypted **http://**
  connections. Make sure you have https:// enabled and configured on server- and
  client-side.

- **Self-signed certificates** need to be properly set up in the macOS keychain.
