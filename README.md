# Statistical Analysis
This repo shows a statistical analysis done between [a studnet algorithm](https://github.com/youssefattia98/Research-Track-I-1) and [the professor algorithm](https://github.com/CarmineD8/python_simulator/tree/rt2).
The robot simulation have a lot of aspects to be noticed but here the following aspects will be compared:  

 1. Lap speed.
 2. Times near to gold.
 3. Laps completed and not completed.
 
 First of all, each code was run for 30 complete laps with screen record on to be able to connect data. All the data collected can be found in the excel file in this repo. After the data was collected the following testes was done. Please note that all test runs where in the same conditions and same PC to make sure that they are as near as possible as the simulation is CPU speed dependent, that means running the same code on different PC will output a different lap speed and so on.   

## 1.Lap speed:
For these data a **parametric test** must be held and T-test was chosen for its simplicity.  

Firstly, lets set the hypothesis:
![Untitled](https://user-images.githubusercontent.com/69837845/170802269-fa019cf5-b7e8-4325-bb72-6ee22fe5a9d5.png)  

Secondly, lets list the data obtained:
![Untitled](https://user-images.githubusercontent.com/69837845/170801087-2ecba3ae-b8b5-45d1-a470-7b66da0e86bc.png)
next step is to calculate The pooled, estimated variance of the sampling distribution of the difference as following:
![Untitled](https://user-images.githubusercontent.com/69837845/170801643-cb13e7fe-5837-4a5f-bd7c-53db518b4a8c.png)  
Calculating the estimated SE of the sampling distribution of the difference equal to 6.968670998 
and the the t is calculated to be found as: 11.96306537
