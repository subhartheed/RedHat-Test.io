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
## Enable Users to connect to the ownCloud Server


## Add a User Account

ownCloud is an enterprise file sharing service for online collaboration and storage. To access this service, the user needs to have their user account which is created and managed by the **admin group**.  
  
The Admin can add/create a new user by the following:
  1. Enter the new user’s **Login Name** and the initial **Password**.
  2. Assign memberships to different **Groups**. This is an optional step.
  3. Click **Create**.      
           
![Add User](https://github.com/subhartheed/RedHat-Test.io/blob/main/docs/newuser.png.PNG"Add User")

## Connecting to the Owncloud Server using a Desktop or Mobile Client
The **ownCloud Desktop Synchronization Client** is used for synchronizing files with the desktop computer. As a user, you can download the latest version of the ownCloud Desktop Synchronization Client from the [ownCloud download page](https://owncloud.org/download/), and can run on various platforms like Microsoft Windows, Mac OS X, and variants of Linux distributions.  

ownCloud Desktop Synchronization Client enables the user to:

