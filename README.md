# MTF
Computes the MTF from an input slit image using the slanted edge method and fits to raw data.
Input slit image in this example:

![slit h 038ms 40w 25 575 centre f-1800_rgbcal2_crop](https://user-images.githubusercontent.com/30912225/39661528-cb57f530-504a-11e8-8c28-71a1d29431b9.jpg)

Output is as follows:

![figure_1](https://user-images.githubusercontent.com/30912225/39661536-ed70c2dc-504a-11e8-88a6-b3bf1b24389b.png)

How to run the code:

In Spyder write:
PDS_Compute_MTF('slit H 038ms 40W 25.575 centre f-1800_RGBcal2_crop.tif', roi)

Where:

roi = [157,202,355,537]

roi = np.asarray(roi)
