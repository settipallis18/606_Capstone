# 606_Capstone

## Introduction: 

One of the most disastrous natural occurrences is an earthquake. After an earthquake, gathering information on building damage and other effects allows for efficient recovery. This research identifies cutting-edge data sources for estimating building damage and offers suggestions for more effective data collection. Depending on the questions that these data are to answer, different criteria must be taken into consideration while choosing a certain data source or data gathering method for seismic reconnaissance. Several data sources ought to support one another, confirm gathered data, or systematically assess the damage.  

As evidenced by the recent rise in the number of crowdsourcing and SM platforms used to collect seismic reconnaissance data, this data source is likely to become more and more significant. Between 1902 and 2011, these occurrences were responsible for more than 23 million fatalities in addition to significant physical, social, economic, institutional, cultural, and environmental losses. Fieldwork or ground surveys, omnidirectional imaging (OD), terrestrial laser scanning (TLS), remote sensing (RS), crowdsourcing platforms, social media (SM), and closed-circuit television films are among the current data collection techniques that have been divided into seven categories (CCTV). In order to prepare statistics, calibrate and evaluate engineering models, and detect the design flaws that result in subpar structural performance, earthquake reconnaissance permits the collection of perishable data on building performance.  

Five closely connected topics are involved in damage detection and characterization: structural health monitoring (SHM), condition monitoring (CM), non-destructive evaluation (NDE), statistical process control (SPC), and damage prognosis(DP). In order to understand the characteristics of the earthquake and its impact on the social, economic, institutional, cultural, and environmental dimensions, researchers could thus collect useful data from citizens, avoiding knowledge gaps that would otherwise allow for the spread of rumors and false information. 

As mentioned earlier, one of the most devastating natural disasters, earthquakes occur suddenly and shake the surface of the earth. Buildings and infrastructure are both harmed by earthquakes, which have an impact on daily living. Machine learning can be quite useful for making early predictions about how an earthquake will affect a region, and this necessitates the originality of the work. Six different machine learning classifiers—Artificial Neural Network, Random Tree, CHAID, Discriminant, XGBoost Tree, and TreeAS—were used on six datasets from various regions of India to classify this perception. It has been noted that the occurrence of large earthquakes typically occurs in cycles, with a long aseismic interval—which may continue for decades or even centuries—occurring between two seismic occurrences that follow one another.  

Seismographs can record the movement of the free surface during the seismic period, which only lasts for a few seconds or a few minutes at most. Seismic waves of various sorts caused by earthquakes cause significant disruptions in the area. It has been noted that in seismically active places, absorption levels of deliquescing minerals and the gassy integrant of subsurface water stay practically constant during the seismically passive time. Except for the earthquake dataset from Gujarat, XGBoost performed quite well in each dataset. Artificial Neural Network and Tree-AS both performed well and provided results for applying this model to predict the seismic impact of upcoming earthquakes, together with XGBoost. Random tree and discriminant analysis didn't always work properly. The Indian earthquake can be predicted in large part thanks to machine learning. With the use of earlier seismic datasets, an ML model has been created for detecting the magnitude range. This analysis predicts a magnitude value. Together with the prediction curve fitting between the magnitude and depth of the Andaman & Nicobar dataset, magnitude, and depth are essential features that should be considered if the earthquake occurs. 
<img width="985" alt="Screenshot 2023-03-09 at 6 39 08 PM" src="https://user-images.githubusercontent.com/94401598/224185267-e6d3f237-969d-473a-b44b-a4af06ae58e4.png">



## Methods: 

Below are the data sources we used to collect information and obtained datasets about earthquakes. There are some government sites and organizational sites which are open and free to access. There are no restrictions imposed on these sites or datasets associated with them. 

This is a government site (https://www.usgs.gov/programs/earthquake-hazards) that monitors and reports earthquakes caused in the U.S. This is an activity taken by them as a part of the larger National Earthquake Hazards Reduction Program (NEHRP). This is a four-agency partnership established by congress. 

## Resources:

1) Earthquake Hazards | U.S. Geological Survey. (2023, March 7),  accessed March 09, 2023, <https://www.usgs.gov/programs/earthquake-hazards> 

2) USGS.gov | Science for a changing world. (n.d.).   https://www.usgs.gov/  

3) World Earthquake Data From 1906-2022. (2023, February 27), Kaggle, accessed March 09, 2023,<https://www.kaggle.com/datasets/garrickhague/world-earthquake-data-from-1906-2022?resource=download> 

4) Stanford EArthquake Dataset (STEAD): A Global Data Set of Seismic Signals for AI. (2019). IEEE Journals & Magazine | IEEE Xplore, accessed March 09, 2023,<https://ieeexplore.ieee.org/abstract/document/8871127> 

5) Global catalog of earthquakes  - Humanitarian Data Exchange. (n.d.), accessed March 09, 2023,<https://data.humdata.org/dataset/catalog-of-earthquakes1970-20145>. 

6) Open data soft - Significant Earthquake Database,  accessed March 09, 2023 <https://public.opendatasoft.com/explore/dataset/significant-earthquake-database/table/> 

7) Contreras, D., Wilkinson, S., & James, P. (2021). Earthquake Reconnaissance Data Sources, a Literature Review. Earth, 2(4), 1006–103, accessed March 09, 2023  <https://doi.org/10.3390/earth2040060> 

8) Pankaj C, Tulika C, Papiya D, Amit Gupta, Prasun C, S. Phani, Martin M, Ahmed A.,  Research Square, Experimental analysis of Earthquake Prediction using machine learning classifiers, curve fitting, and neural modeling, (2022 September 01), Accessed March 09, 2023, <https://assets.researchsquare.com/files/rs-1896823/v2/b190f239-8da8-4078-8cb5-0f18c2e17d0a.pdf?c=1663935282> 

 
## Appendices: 

 The prediction of earthquakes is a challenging task that has been the subject of research for many years. While there has been some progress in predicting earthquakes, accurate and reliable earthquake prediction is still not possible with the current state of scientific knowledge. 

AI has the potential to contribute to earthquake prediction by enabling more advanced analysis of data and faster processing of information. Machine learning algorithms, for example, can be used to identify patterns in seismic data that may indicate the likelihood of an earthquake. 

However, it's important to note that predicting earthquakes is a complex problem that involves many factors, including geological and environmental conditions, and it's not yet clear if AI can provide a significant improvement in earthquake prediction accuracy. 

Furthermore, even if AI-based earthquake prediction becomes more accurate, it is not clear how useful such predictions would be in practice. For example, it may be difficult to evacuate people from a region based on a prediction of an earthquake without causing unnecessary disruption and panic. 

In summary, while AI has the potential to contribute to earthquake prediction, it is unlikely to provide a complete solution to this complex problem, and further research is needed to determine the extent to which AI can be used for predicting earthquakes. 

 
 

Predicting earthquakes using machine learning involves training models on large datasets of seismic data to identify patterns and make predictions about future seismic activity. Here are some general steps for predicting earthquakes using machine learning: 

Collect and preprocess seismic data: Seismic data includes measurements of ground motion, such as acceleration, velocity, and displacement, as well as other data such as location, depth, and time. The data should be cleaned and preprocessed to remove noise and artifacts. 

Feature extraction: Relevant features should be extracted from the preprocessed seismic data. These features can include statistical properties of the data, frequency-domain features, and waveform-based features. 

Model selection: Various machine learning models can be used for earthquake prediction, including decision trees, support vector machines, neural networks, and random forests. The choice of model will depend on the characteristics of the data and the specific prediction task. 

Model training: The model is trained on the preprocessed seismic data using a labeled dataset, where the labels indicate the occurrence or non-occurrence of earthquakes. The model is optimized to minimize prediction errors on the training dataset. 

Model evaluation: The trained model is evaluated using a test dataset to assess its performance in making accurate earthquake predictions. Evaluation metrics can include accuracy, precision, recall, and F1 score. 

Model deployment: Once the model is trained and evaluated, it can be deployed to predict earthquakes in real-time. The model can be integrated into an early warning system or used for hazard assessment and risk analysis. 
