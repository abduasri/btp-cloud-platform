<!-- loio5456007ac4d04cb98b52b41f8c2d4a71 -->

# Maintain Namespaces

With the Maintain Namespaces App you can now both create new namespaces and install the namespaces in your ABAP system.

When you provision a new system or when you upgrade it, all your namespaces are automatically installed in that system as well. However, you might have created a new namespace after the system has been provisioned and you need it installed in your system before the next system upgrade. This is where the *Maintain Namespaces* app comes in.

The *Maintain Namespaces* app enables you, as a provider, to:

-   create new namespaces
-   see which namespaces are installed in which of your systems
-   install new namespaces in already provisioned systems.



<a name="loio5456007ac4d04cb98b52b41f8c2d4a71__section_umt_xqz_1tb"/>

## Prerequisites

You need to have the “LandscapePortalAdmin” user role assigned to your user account to access this app.



<a name="loio5456007ac4d04cb98b52b41f8c2d4a71__section_n5j_yvf_fvb"/>

## Working in the Maintain Namespaces App



<a name="loio5456007ac4d04cb98b52b41f8c2d4a71__section_fxt_stf_fvb"/>

## Create Namespaces

1.  Log into the Landscape portal from your provider subaccount.

2.  In the 'Systems' section, click on the Maintain Namespaces tile to open the app.
3.  The Namespaces tab shows you the list of your Provider Namespaces and their description ckecked against all existing SAP Provider Namespaces.
4.  To create a new Namespace, click the *Create Namespace* button.
    -   Type in a Namespace name as well as a desciption and check its availability with the *Check* button. Since the namespace is supposed to be globally unique, the check is made against all namespaces available.

    -   If the check has been successful, click the *Create* button.
    -   Find the newly created namespace displayed in the list.

        > ### Note:  
        > Consider the lifetime of these worldwide uniquely existing namespaces. Once created, a namespace cannot be deleted.





<a name="loio5456007ac4d04cb98b52b41f8c2d4a71__section_vzk_yqz_1tb"/>

## Maintain Namespaces

1.  Log into the *Landscape Portal* from your provider subaccount.

2.  In the *Systems* section, click on the *Maintain Namespaces* tile to open the app.

3.  A list of all your systems, including their system number, system ID, description and instance name, is displayed. Select a system to view more details on it.

4.  You can now see more detailed information on the system as well as a list of all your namespaces and whether they are installed in this system \(highlighted in green\) or not \(highlighted in orange\).

5.  Click the *Install Namespaces* button in the top right corner to install all your namespaces in this system.

    Note that the *Install Namespaces* button is only visible if the following is the case:

    -   There are one or more customer namespaces that have not already been installed in the system.
    -   The system in which you want to install namespaces is in lifecycle status *Live*.


> ### Note:  
> All new namespaces will be installed in the system; it is not possible to select only a specific namespace to be installed.

