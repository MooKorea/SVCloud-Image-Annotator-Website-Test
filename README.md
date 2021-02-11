## Getting Started with SVCloud Image Annotator (SVCA)
{:.no_toc}

### Table of Contents
{:.no_toc}

* TOC
{:toc}

### Connecting to the Server 

![First Screen](images/1_Intro.png)

First, open the menu and select "Connect to Server":

![Menu](images/2_Menu_unconnected.png)
![Connecting](images/3_connecting.png)

A browser window will open and ask you to login to Google.  After login this window can be closed.  

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Creating a Workgroup  

After connecting, the workgroup selection popup will appear.
 
![Workgroup](images/4_workgroup_1.png)

The dropdown menu lists all workgroups to which your username has access.   

To begin, create a new workgroup; or, choose a workgroup and press the 'Select' button.

![Workgroup](images/4_workgroup_2.png)

To create a new workgroup, type a new workgroup name into the selection field and press 'Configure'.

![Workgroup](images/4_workgroup_3.png)

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Configuring a Workgroup

The workgroup configuration window will open, allowing you to add users and editable annotations to your new workgroup.  

You are automatically a group admin in your new workgroup (you can change this, but you might not be able to change it back!).  

![Workgroup](images/4_workgroup_5_labels.png)

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Creating Annotations

Annotations come in four types: boolean, numeric, text, and category.  

The first three are straightforward: boolean annotations are yes/no, numeric annotations accept any number value, and text annotations accept any text input.  

![Workgroup](images/4_workgroup_6.png)

Annotation categories are annotations with a restricted subset of options, similar to a menu or dropdown.  

You can add any number of values to an annotation category.  Users can either select any number of options, or you can choose to restrict the selection to a single value.

![Workgroup](images/4_workgroup_7.png)

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Loading Image Files

After selecting or creating your workgroup, SVCA will return to the ready screen.  However, the ready message has changed and new menu options are now available:

![Menu2](images/5_menu_connected.png)

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Uploading Annotations from a Manifest File

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Show/Hide Samples and SVs

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Support / Contact

Having trouble with SVCA?  Please contact us at help@genvisis.org for assistance.  
If possible, please attach the most recent log file to your email.  

Logs are located:
 - on Windows computers at `%LocalAppData%/sv-image-annotator/app/logs/`  
    (this location can be changed in the `File` menu)

<div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>

### Changelog

#### v2.6.3   (02/11/2021)
 - Allow loading images from TAR archives
 - Ignore missing values (e.g.: '.', '-', 'NA', etc) in manifest files
 - Add tooltip to upload GUI reset button
 - Report program version at startup and check against remote version
 - Show data upload error code in pop-up
 - Fix text field width for text annotations
 - Fix upload GUI progress monitoring when (up)loading large manifest files
 - Fix Show/Hide for SVs
 - Reduce excess redraws

#### v2.6.2  (02/07/2021)  
 - Fix bugs in validation using BED files 
 
#### v2.6.1  (02/01/2021)  
 - Fix visual spacing in right-click menu and add manifest file format mouseover info
 - Parse CN# in image file name (instead of DUP/DEL/etc)

#### v2.6.0   (06/05/2020)  
 - Add icon to all windows
 - Add sample/sv delete
 - Add hide by annotation menu
 - Update menu labels and structure
 - Update delete dialog message
 
 <div style="text-align: right; font-size: 10px"><a href="#">Back to top</a></div>
