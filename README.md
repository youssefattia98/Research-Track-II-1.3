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
Comparing the t to the T-table:  
![Untitled](https://user-images.githubusercontent.com/69837845/170802417-89172849-dcc3-4cad-933a-9a3c8f9feaeb.png)  
**Therefore, the null hypothesis is neglected and it is said that the professor code is faster.**

## 2.Times near to gold:  
For these data a **parametric test** must be held and T-test was chosen for its simplicity as the prvious example, the calculations can be found in the excel file. But lets set the hypothesis as follwing:  
![Untitled](https://user-images.githubusercontent.com/69837845/170802269-fa019cf5-b7e8-4325-bb72-6ee22fe5a9d5.png)  
Furtheremore, the t calculated is found to be: 2.177881632  
**Therefore, the null hypothesis is not neglectable and it is said that both algorithms perform similarly.**  

## 3.Laps completed and not completed:  
This test is really crucial as it is what actually defines which algorithm is better and which is not, as from this test it can be said the robot completed it mission or not.  
First of all, it was noted that the professor’s algorithm had to be re-runed for 4 times during the 30 laps trial as it either entered in an infit loop or went in the wrong direction. on the other hand the stundet's algortithm was able to complete the 30 laps non-stop without hitting any golden token or changing the direction.  

The video bellow shows the professor algorithm after hitting a golden token and going in the wrong direction:  


https://user-images.githubusercontent.com/69837845/170803967-377d50b6-385d-4a4e-8835-cc79afaa36de.mp4  


The data collected is as follows:  
![Untitled](https://user-images.githubusercontent.com/69837845/170803240-a742f729-6d4f-481c-9b6d-68fbd1de41b4.png)  
A **Chi test** is choosen for this type of data as it is **non-parametric test** is needed  
lets set the hypothesis as follows:  
![170802269-fa019cf5-b7e8-4325-bb72-6ee22fe5a9d5](https://user-images.githubusercontent.com/69837845/170803465-4aaccf52-09f9-4b24-b3f8-1c6b9264592f.png)  
Now lets calculate x squared:  
![Untitled](https://user-images.githubusercontent.com/69837845/170803506-b26f106a-8d21-4d54-844c-dc4f8f37fd18.png)  
looking at the table:  
![Untitled](https://user-images.githubusercontent.com/69837845/170803635-f504bd39-ae0e-4108-9a48-59196b1f8871.png)  
**Therefore, the null hypothesis is neglectable and it is said that student algorithm performs better.**

## Conclusion:
In conclusion and from the previous test done, it is said the the student algorithm is better as it can achive the main goal then the professor algorithm, even if the professor algorithm can complete its laps faster yet this was not the main goal of the robot. 
