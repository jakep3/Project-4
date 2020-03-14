
Link to Jupyter Notebook on GitHub:

https://github.com/jakep3/Project-4/blob/master/Project_4_Philpott_Hydrophone.ipynb

Jake Philpott

BME 450

3/13/2020

                                        Project 4: Hydrophone Assignment

__PROBLEM STATEMENT__ 

The purpose of this project was to evaluate Hydrophone data from the OOI Broadband Hydrophone website and discover the effects of wind and rain on underwater noise. There were two sites of interest:
  1.	Oregon Shelf Cabled Benthic Experiment Package
  2.	Oregon Offshore Cabled Benthic Experiment Package

___PART 1:___
From Project 2, four time periods were to be identified and the corresponsding Power Spectral Density (PSD) vs Frequency plots were to be created. The four time periods of interest were as follows for both sites. 
  1. When it does not rain and it is not windy
  2. When it does not rain and it is windy
  3. When it rains and it is not windy
  4. When it rains and it is windy
  
After creating the eight plots, the following questions were to be answered:
  1. What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.
  2. Which one has the highest impact? Rain or wind? 
  3. What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?

___PART 2:___

The following tasks were to be performed and questions answered. 

  1. Find a short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram.
  2. Find a short time period that there is an airgun noise in recorded data and plot its spectrogram.
  3. Find a short time period that there is an earthquake or a volcano eruption in recorded data and plot its spectrogram.
  4. Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve?

__BACKGROUND__ 

Hydrophones do this...

Hydrophone data is available at this website : https://oceanobservatories.org/instrument-series/hydbba/

This is the Wenz curve from Ocean Noise Slides ... 

![](12.JPG)

Power spectral density of a signal uses this equation ... 

![](13.JPG)
![](14.JPG)

Project 2 link is here and is where times came from : https://github.com/jakep3/Project-2-

__SOLUTION__

Solution involved evaluating the data from Project 2 to determine the specific times that the four weather conditions were met. Then form the OOI Website, the corresponding Hydrophone data was able to be found and linked to Jupyter notebook for evaluation. 

The code involved can be seen in the link in the begining of the report. 
Once the plots were made, the questions of interest for the project were able to be answered through plot analysis. 


__RESULTS__


___PART 1 RESULTS___

The following are the PSD vs Frequency plots (Figures 1 - 8) for the four time periods, for both sites, that were identified in Project 2.   

![](1.JPG)
__Figure 1:__  When it does not rain and it is not windy, at the Oregon Shelf site. 

 
 ![](2.JPG)
__Figure 2:__ When it does not rain and it is windy, at the Oregon Shelf site. 


![](3.JPG)
__Figure 3:__ When it rains and it is not windy, at the Oregon Shelf site. 


![](4.JPG)
__Figure 4:__ When it rains and it is windy, at the Oregon Shelf site. 


![](5.JPG)
__Figure 5:__ When it does not rain and it is not windy, at the Oregon Offshore site. 


![](6.JPG)
__Figure 6:__ When it does not rain and it is windy, at the Oregon Offshore site. 


![](7.JPG)
__Figure 7:__ When it rains and it is not windy, at the Oregon Offshore site. 


![](8.JPG)
__Figure 8:__ When it rains and it is windy, at the Oregon Offshore site. 



Refering to the previous plots, the questions were answered as follows: 

 1. What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.
    
 2. Which one has the highest impact? Rain or wind? 
    
 3. What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?
    


___PART 2 RESULTS___

The following are the results from part 2 of the project. 

  1. There is a marine mammal vocalization recorded on the RS01SLBS device on October 6th 2017. The spectrogram of the recorded data can be seen in Figure 9. 
    
   ![](9.JPG)
    
__Figure 9:__ Spectrogram for a short period of time that there is marine mammal vocalization. 


  2. There is airgun noise at the Asial Seabase RS03AXBS site on August 1st 2019. The spectrogram of the recorded data can be seen in Figure 10. 
    
  ![](10b.JPG)
    
__Figure 10:__ Spectrogram for a short period of time that there is airgun noise. 


  3. There was earthquake/volcano eruption activity at the Axial seamount CE04OSBP site on April 15th 1017. The spectrogram of the recorded data can be seen in Figure 11.
    
  ![](11.JPG)
    
__Figure 11:__ Spectrogram for a short period of time that there is an earthquake or volcano eruption. 
 




4.  For Figure 9, the bandwidth for the marine mammal vocalization ranges from roughly 20 Hz to 5000+ Hz. This is consistent with  what is shown in the Wenz Curve, under Biologics. Biologics is the category that marine life noise is under and ranges from 10 Hz to 100000 Hz. For Figure 10, the bandwidth of the airguns appear to range from 0 Hz to 14000+ Hz every 15 seconds, and every 2 seconds they range from 6000 Hz to 14000+ Hz. Airguns produce their sound waves by making bubbles underwater. This is consistent with the Wenz Curve, under the category of Bubbles and Spray (Surface Agitation) and has a range of 100 Hz to roughly 100000 Hz.  For Figure 11, the bandwidth for the earthquake/volcano eruption is roughly 1 Hz to 100 Hz, with the most intense sound at from 20 Hz to 50 Hz. This is consistent with what is shown in the Wenz curve, under the category Earthquakes and Explosions, which range from 1 Hz to 100 Hz.

   
__CONCLUSIONS__ 

 
__REFERENCES__
