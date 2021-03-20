# ownCloud Quickstart Guide

**Welcome to ownCloud** 

ownCloud is an open-source file sync, share and content collaboration software that lets teams work on data easily from anywhere, on any device. ownCloud enable organizations to safely store files and make them available to the relevant employees. It creates a single point of access for all file storage that makes it easy to find information, manage permissions and trace usage.
The ownCloud Virtual File System (VFS) allows users to sync full directory trees without filling up their devices. It syncs virtual files, i.e. metadata about the kind, size and date of a file, only transferring the full file when needed. Its frictionless user experience keeps staff from using unsanctioned and unsafe means of file sharing. Its self-service features empower users and reduce work load for admins.

This is a quickstart guide addressing the following functionalities:
- [Installation and Configuration of an Owncloud Server](#installation-and-configuration-of-an-owncloud-server)
- [Connecting Users to the Owncloud Server](#connecting-users-to-the-owncloud-server)
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

### Prerequisites for Adding User Accounts by the Admin Team
1.	Sign in to the _ownCloud server 10.1_ using an _administrator account_.

2.	Once the user administration page is displayed, click on the _username(admin)_.
        A drop-down menu appears with options to enter the following sections: **Personal**, **Users**, **Apps**, **Admin**, **Help**,           and **Log out**.  

       ![3 1](https://user-images.githubusercontent.com/40832072/55606952-67d26d00-5798-11e9-97ea-de0175e91fd2.jpg)  
 
3.	Click on the **Users** item from the drop-down menu. A default table appears displaying basic information about the users whose         accounts have already been created.  

       ![3 2](https://user-images.githubusercontent.com/40832072/55607403-bb918600-5799-11e9-8969-038d7881824a.png)
 
4.	Create groups based on user’s access limitations.    
        To add groups, go to the **Groups** field. Hover over the **_+ add group field_**, enter a name for the group and hit the               **Enter** button.     
    
       ![3 3](https://user-images.githubusercontent.com/40832072/55607638-51c5ac00-579a-11e9-8b03-8dd7dbd918a8.png)      
       
	Now you can start adding users and adding them to specific groups as per defined access	controls.  
  
### Adding or Creating New User Accounts

  - Enter the new user’s **Login Name** and the initial **Password**  
  - (Optional) Assign **Groups** membership       
  - Click the **Create** button         

**Note**: Login names may contain letters (a-z, A-Z), numbers (0-9), dashes (-), underscores (_), periods (.), and at signs (@). ownCloud usernames cannot be changed. These are user’s permanent-owned cloud user IDs. However, user’s **Full Name** can be changed. The admin can also edit the passwords and can change group assignments as and when needed. This is a useful mechanism for delegating some admin chores and also enabling groups to manage themselves.

After creating the user, you may fill in their **Full Name** if it is different from the login name or you can leave it for the user to complete.

![3 4](https://user-images.githubusercontent.com/40832072/55607643-55593300-579a-11e9-9fb9-9e7c47cde307.JPG)           
 
**Note**: Press _Ctrl-R_ to refresh the page. This is done to make sure your new entry is visible.  

> To summarize, the steps involved in creating or adding a new user are entering a name and password and delegating the user to a group. The new user can now log in to the ownCloud server and start collaborating with other users.
          

## Connecting to the Owncloud Server using a Desktop or Mobile Client
The **ownCloud Desktop Synchronization Client** is used for synchronizing files with the desktop computer. As a user, you can download the latest version of the ownCloud Desktop Synchronization Client from the [ownCloud download page](https://owncloud.org/download/), and can run on various platforms like Microsoft Windows, Mac OS X, and variants of Linux distributions.  

ownCloud Desktop Synchronization Client enables the user to:

* Create folders in the home directory and keep the contents of those folders synced with the ownCloud server.   
* Synchronize all the latest files irrespective of their location.  

You can find more advanced usage in the [ownCloud Advanced Usage](https://doc.owncloud.org/desktop/2.2/advancedusage.html) section.  

### Step-by-Step Instructions for Connecting ownCloud Server 

Once you have installed the ownCloud Desktop Synchronization Client on your operating system, follow these steps to connect with your ownCloud server:  
1. Launch the **ownCloud Desktop Client**.  

2. In the ownCloud Connection Wizard dialog box, enter the **IP address** for your server. Click _Next_ to proceed.  

    ![4 1](https://user-images.githubusercontent.com/40832072/55616468-84c66a80-57af-11e9-96b5-2888fe7ac617.png)    
        
3. Enter your **Username** and **Password** and click _Next_.  

    ![4 2](https://user-images.githubusercontent.com/40832072/55616477-8859f180-57af-11e9-9f04-2e8665dd7184.png) 
        
4. Specify whether to synchronization all of your files on the ownCloud server or only selected files. Also, specify a location for        the local files to reside.  

    ![4 3](https://user-images.githubusercontent.com/40832072/55616484-8b54e200-57af-11e9-98c0-06c14d60fd18.png)  
        
5. Click the _Connect_ button. The ownCloud Desktop Synchronization Client will attempt to connect to your ownCloud server. 
   Once connected, you will see two buttons:
    * Open ownCloud in Browser
    * Open Local Folder
            
   Choose the button where you want to synchronize your files. Then click the _Finish_ button, and you are all done.  

   ![4 4](https://user-images.githubusercontent.com/40832072/55616489-8e4fd280-57af-11e9-8b66-7aaabb7d25f5.png)
 



