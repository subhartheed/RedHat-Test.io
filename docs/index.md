# ownCloud Quickstart Guide

**Welcome to ownCloud** 

ownCloud is an open-source file sync, share and content collaboration software that lets teams work on data easily from anywhere, on any device. ownCloud enable organizations to safely store files and make them available to the relevant employees. It creates a single point of access for all file storage that makes it easy to find information, manage permissions and trace usage.
The ownCloud Virtual File System (VFS) allows users to sync full directory trees without filling up their devices. It syncs virtual files, i.e. metadata about the kind, size and date of a file, only transferring the full file when needed. Its frictionless user experience keeps staff from using unsanctioned and unsafe means of file sharing. Its self-service features empower users and reduce work load for admins.

This quickstart guide addresses the following functionalities:
- [Installation and Configuration of an Owncloud Server](#installation-and-configuration-of-an-owncloud-server)
- [Enable Users to connect to the ownCloud Server](#enable-users-to-connect-to-the-owncloud-server)
- [Add a User Account](#add-a-user-account)
- [Connecting to the Owncloud Server using a Desktop or Mobile Client](#connecting-to-the-owncloud-server-using-a-desktop-or-mobile-client)

## Installation and Configuration of an Owncloud Server 
ownCloud server is available in three editions:

- The free community-supported server. This is the core server for all editions.
- The Standard Subscription for customers who want paid support for the core Server, without Enterprise applications.
- The Enterprise Subscription provides paid support for the Enterprise Edition. This includes the core Server and Enterprise apps.

ownCloud server can be installed using [**Owncloud zip** or **tarball**](https://owncloud.com/download-server/) for production environments. They contain all supported community and enterprise apps. Upgrading to Enterprise only requires a licence key. These packages offer the most customizable installation method for admin users.
As an admin, you can install ownCloud in the following ways:
- [Manual Installation](https://doc.owncloud.com/server/10.6/admin_manual/installation/manual_installation/manual_installation.html)
- [Installation using Docker](https://doc.owncloud.com/server/10.6/admin_manual/installation/docker/)

You can refer the Quick Installation Guides available for installing ownCloud manually. These are ultra-short guides for installing ownCloud on a fresh installation of [Ubuntu 18.04](https://doc.owncloud.com/server/10.6/admin_manual/installation/quick_guides/ubuntu_18_04.html) and [Ubuntu 20.04](https://doc.owncloud.com/server/10.6/admin_manual/installation/quick_guides/ubuntu_20_04.html). Run the commands as outlined in these guides, in your terminal to complete the installation. 

After the installation of ownCloud server, you must configure it as per the guidelines mentioned in the Configuration Guide. The Configuration Guide is broadly divided into the following chapters:
- [Database](https://doc.owncloud.com/server/10.6/admin_manual/configuration/database/)
- [Encryption](https://doc.owncloud.com/server/10.6/admin_manual/configuration/files/encryption/root.html)
- [External Storage](https://doc.owncloud.com/server/10.6/admin_manual/configuration/files/external_storage/)
- [Files and Sharing](https://doc.owncloud.com/server/10.6/admin_manual/configuration/files/)
- [General Topics](https://doc.owncloud.com/server/10.6/admin_manual/configuration/general_topics/)
- [Full Text Search](https://doc.owncloud.com/server/10.6/admin_manual/configuration/search/)
- [Mimetypes Management](https://doc.owncloud.com/server/10.6/admin_manual/configuration/mimetypes/)
- [Server Configuration](https://doc.owncloud.com/server/10.6/admin_manual/configuration/server/)
- [User](https://doc.owncloud.com/server/10.6/admin_manual/configuration/user/)

## Add a User Account

ownCloud is an enterprise file sharing service for online collaboration and storage. To access this service, the user needs to have their user account which is created and managed by the **admin group**.  
  
The Admin can add/create a new user by the following:
  1. Enter the **Login Name** and initial **Password** of the new user.
  2. Assign memberships to different **Groups**. This is an optional step.
  3. Click **Create**.      
           
  ![Add User](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/newuser.png)

The **Login Name** of the user may contain the following:
- Letters (a-z, A-Z)
- Numbers (0-9)
- Dash (-)
- Underscore (_)
- Period (.)
- @ sign

After creating the user, you may fill their Full Name if it is different from the Login Name, or else leave it for the user to complete.
For more information on user configuration and management, refer the [Admin Manual](https://doc.owncloud.com/server/10.6/admin_manual/configuration/user/). 

## Connecting to the Owncloud Server using a Desktop or Mobile Client
As a user, you can connect to the ownCloud Server either through a Desktop or Mobile client once the Admin creates your user account.
For accessing ownCloud Server through a Desktop client, do the following:
1. Open the ownCloud Server on a web browser such as *Edge, IE 11 or latest, Firefox 60 ESR or latest, Chrome 66 or latest, or Safari 10 or latest.
2. Type your username and password.

  ![user login](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/userlogin.png)
  3. Once the user credentials are entered, the ownCloud web interface opens to your **Files** page.

  ![Files Page](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/filespage.png)
  
 You can add, remove, or share files on the **Files** page, based on the access privileges set by you (if you are administering the server) or by your server administrator. 
 For more information, refer [The Web Interface](https://doc.owncloud.com/server/10.6/user_manual/webinterface.html) and [Desktop Client](https://doc.owncloud.com/desktop/2.6/installing.html).

For accessing ownCloud Server through a Mobile client, do the following:
1. Download the ownCloud app from the [app store](https://play.google.com/store/apps/details?id=com.owncloud.android). You can also get your ownCloud Android app by logging onto your ownCloud server from your Android device using a Web browser such as *Chrome*, *Firefox*, or *Dolphin*.

2. The first time that you use the Android app, you will see the **New Features Wizard**. This wizard gives you a quick overview of the new features in the ownCloud Android App.
3. The first time you run your ownCloud Android app, it opens to a configuration screen. Enter your server URL, login name, password, and click **Connect**. You can alos click the eyeball to the right of your password to view your password.

![login](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/android.png)

4. For best security, your ownCloud server should be SSL-enabled so that you can connect via HTTPS. The ownCloud Android App will test your connection as soon as you provide it and tell you if you entered it correctly. If your server has a self-signed SSL certificate, you’ll get a warning that it is not to be trusted. If this happens, click **YES** to accept the certificate and complete your account setup.

![certificate](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/yes.png)

5. You are now ready to use the ownCloud Android App. The *All Files* screen is displayed.

![All files](https://raw.githubusercontent.com/subhartheed/RedHat-Test.io/main/docs/main.png)

For more information, refer [Mobile App](https://doc.owncloud.com/android/)

## Enable Users to connect to the ownCloud Server
