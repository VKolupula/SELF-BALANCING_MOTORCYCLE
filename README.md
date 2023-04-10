# SELF-BALANCING_MOTORCYCLE
motorcycle that self balances and maneuvers by itself using a flywheel.


https://user-images.githubusercontent.com/120835150/231008325-13a7538e-d94a-4093-bc1e-7502d3afbf74.mp4

![rotation-axis](https://user-images.githubusercontent.com/120835150/231000733-dda93a85-8555-4d9f-8190-baf93146fa40.jpg)

#### The problem of balancing the motorcycle can be considered as a problem of controlling an inverted pendulum.

#### Assumptions:

The motorcycle is only free to move about the wheel-ground axis, which is an imaginary line that connects the points on the rear and front wheels where they touch the ground,

The motorcycle wheels’ thickness is negligible,

Friction between all the moving objects is negligible.

#### state-space format

![state vector](https://user-images.githubusercontent.com/120835150/231003639-05ec4749-4dea-4d8b-be68-265e32c27a2e.PNG)

### Preprocessing Sensor Measurements

![processing_sensor_data](https://user-images.githubusercontent.com/120835150/231004140-2b16956a-dc40-43ed-8f68-4888e58382cc.PNG)

### Safety Logic

![safety_control](https://user-images.githubusercontent.com/120835150/231004287-1e6b9093-be0d-490b-a44a-cf9f92edafb8.PNG)

### Feedback Control

![SBMC](https://user-images.githubusercontent.com/120835150/231001154-4bffa07e-e75f-488c-bc8c-c4b8b9b70736.PNG)

![Digital_controller](https://user-images.githubusercontent.com/120835150/231001224-1ca87bc9-00c8-45f7-b1e3-d439754dd84d.PNG)

#### Feed back gains

![Feed_back_gains](https://user-images.githubusercontent.com/120835150/231004642-9d40116b-8813-47e8-b445-02e0bb4a691d.PNG)

### Control and Visualizing data

![dashboard](https://user-images.githubusercontent.com/120835150/231004805-cebfb299-6c61-442c-a326-b9d9f4c5fc17.PNG)

![data_inspector_matlab](https://user-images.githubusercontent.com/120835150/231004774-045e9e76-59be-4a36-983a-4e4a5f277826.png)

https://user-images.githubusercontent.com/120835150/231008927-47021f47-1242-49f2-bfec-d05cf3036818.mp4
