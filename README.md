# Visualizing-Highway-Sensor-Data-
UNLV Smart Cities REU 2021 Visualizing Highway Sensor Data Dashboard Code
Current look of the dashboard:
![image](https://user-images.githubusercontent.com/88454497/132273921-3456a96a-36a3-49e1-b03b-8f1a04968ddc.png)
![image](https://user-images.githubusercontent.com/88454497/132273981-af4a3165-c339-49b8-be8c-aef59bc95571.png)
The format of the dashboard was updated and the dropdown for the sensors was added.
I believe the esri map just had to be updated and thus the issue should be fixed now.

To run:
Start by running the MQTT to CSV Code first in jupyter notebook which reads the information as it comes in from MQTT and reformats it to a csv file 'getdata7.csv' in my code.
The written csv file can be found on the jupyter notebook homepage. Following this run the Dashboard Code (I did this in a text file in jupyter notebook which must be titled _.py file)
In the command prompt panel serve _.py to run the dashboard.
