# Using Cluster Computer Checkout with the SGC Q: Drive 

Recently, VPTL launched the checkout-cluster program https://cluster-checkout.stanford.edu/ that allows users to use Stanford cluster machines remotely for both macOS and Windows. All that is required for access is a valid Stanford SUNetID.

## GIS-related software on Cluster Checkout machines
These cluster machines include the following  software of interest to spatial data users:

* ArcGIS Desktop
* ArcGIS Pro
* QGIS
* ENVI 
* Google Earth Pro Desktop
* OpenRefine
* IrfanView
* RStudio
* GIMP
* Inkscape 
* More...

## Accessing Cluster Checkout machines

1. If using MacOS to connect, download [Microsoft Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop-10/id1295203466).
1. First, **connect** to [Stanford VPN](https://uit.stanford.edu/service/vpn/).
2. Go to https://cluster-checkout.stanford.edu/ and **use Stanford SSO to login**.
2. Click the **SELECT** button for the Windows Cluster.
3. Review the available software, if needed. Click **NEXT**.
4. Review the policies and details, then click **NEXT**.  

At this point, you will have been randomly assigned  an available Cluster Machine for checkout. Follow the Cluster-Checkout guidance from this point to login to a Windows Machine. 


## Connecting to your SGC 'R: Drive' from a Cluster Checkout machine

1. In the **Windows File Explorer**, click on **This PC** (**do NOT** use ***Internet*** Explorer).
2. Go to the **Computer** tab and click on the **Map Network Drive** button.
3. In the window that opens set the **Drive:** as R:
4. Set the **Folder:** path for the User connection to `\\sul-sgclab\Users\[your SUNet username]`.
5. Check the box for **Reconnect at sign-in** if you would like the drive to automatically connect every time you log on, though that will only work if you reuse the same **Cluster Checkout RDP File**. 
6. Repeat above with **Q:** as the **Drive:** and `\\sul-sgclab\GIS` for the Data and Groups folder connections, if needed.




