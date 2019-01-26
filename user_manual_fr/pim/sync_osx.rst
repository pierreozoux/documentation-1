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

.. note:: Vous ne pouvez pas installer Agenda et Contacts sur le même compte. Vous devez les configurer dans **des comptes distincts**.
4. Selectionner **Advanced** comme type de compte et renseignez vos identifiants:

   - **Username**: Votre nom d'utilisateur Nextcloud ou adresse mail
   - **Password**: Votre mot de passe d'application (`App-password/token <https://docs.nextcloud.com/server/stable/user_manual/session_management.html#managing-devices>`_)
   - **Server Address**: l'URL de votre serveur Nextcloud (p.e. https://cloud.example.com)
   - **Server Path:** /remote.php/dav/principals/users/[votre nom d'utilisateur]
   - **Port:** 443
   - **Use SSL:** Yes

.. figure:: ./images/macos_3.png

5. Cliquer sur **Sign In**.

**Pour CalDAV (Agenda):** Vous pouvez maintenant choisir avec quelle application utiliser cette ressource. Dans la pluspart des cas, ce sera l'application "Agenda", parfois vous pourriez aussi vouloir l'utiliser pour vos **"Tâches et rappels"**.

.. figure:: ./images/macos_4.png

Résolution de problèmes
---------------

- macOS **ne supporte pas** la synchronisation CalDAV/CardDAV avec des connections non cryptées **http://**. Assurez vous d'avoir la connection https:// configurée et activée sur votre serveur et votre client.

- **Les certificats autosignés** doivent être correctement configurés dans le porte clé de macOS.
