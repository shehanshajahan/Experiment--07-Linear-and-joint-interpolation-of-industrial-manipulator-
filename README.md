# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-
## Name : Shehan Shajahan
## Date : 15-04-2024
## Register Number : 212223240154
## Department : Artificial Intelligence and Machine Learning
### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
![image](https://github.com/shehanshajahan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139317389/c0996aac-7314-402c-ab1a-baa5079e8440)
![image](https://github.com/shehanshajahan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139317389/b8eb5b73-3e89-4c12-852d-edf033b0111b)


### Robot movements 
![image](https://github.com/shehanshajahan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139317389/35608e44-fcee-4a51-aff3-cd53d8e6c2f0)
![image](https://github.com/shehanshajahan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/139317389/1b01cfba-fe37-44be-af78-80dbc4305575)
![Uploading image.png…]()


### Results:  
A program is developed for understanding linear and joint interpolation of industrial manipulator and is ran sucessfully.
