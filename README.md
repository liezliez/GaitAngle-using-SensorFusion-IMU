# GaitAngle-using-SensorFusion-IMU 
This Program will calculate the Gait Angle of knee flexion from the subject using sensor fusion inertial measurement unit by utilizing accelerometer and gyroscope from smartphone.

# How it works
This program calculate raw data from the accelerometer and gyroscope sensor using knee flexion angular velocity formula.

for Accelerometer  
![Accel](https://user-images.githubusercontent.com/42132479/116361055-bf821c00-a82a-11eb-911b-0818e8d3edae.PNG)  
for Gyroscope  
![gyro](https://user-images.githubusercontent.com/42132479/116361082-c577fd00-a82a-11eb-9f21-dfae82ec67e4.PNG)  

then by using complementary filter alogrithm method we would get the Gait Angle Result which i represent in this project using plot table  

complementary filter algorithm    
![complementaryPNG](https://user-images.githubusercontent.com/42132479/116361416-299ac100-a82b-11eb-9335-b457363a405c.PNG)  

# Getting the Dataset
![image](https://user-images.githubusercontent.com/42132479/116361790-8dbd8500-a82b-11eb-9843-a7a46a6a4991.png)  
For getting the raw dataset, i'm using Phypox App on smartphone https://phyphox.org/  
By using this app, we can get a Linear Accelerometer and Gyroscope dataset using our smartphone as IMU.  
which we tied to our leg around our thigh (look image for ilustration)

![phypox](https://user-images.githubusercontent.com/42132479/116362856-b6924a00-a82c-11eb-80b1-138074ff8132.PNG)  
Import the data, the result will be on .xls format

# The Result
Gait Angle Plot  
![image](https://user-images.githubusercontent.com/42132479/116363149-07a23e00-a82d-11eb-9861-71cb8342b0a5.png)
