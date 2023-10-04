# Speech Emotion Recognition & Data Sonification

Competed by Gustavo Colmenares & Sebastian Bayne as a final project for WBS Coding School’s ‘Data Science’ course. Both have a background in audio and wanted to work with sound data techniques. 

This is a two-part project, firstly building a ‘Speech Emotion Recognition’ model using Deep Learning, and secondly to exploring the possibilities of ‘Data Sonification’. 

The back story is that we work for a fictitious telco company ‘VolaPhone’, and we are given audio data and numerical and categorical data extracted from the Customer Service calls and our mission is to look at ways we can improve customer service KPIs with historical data.  

## Speech Emotion Recognition (SER)

1.	Selecting the audio datasets - used 4 pre recorded set of human emotion - Ravdess, Crema, Tess & Savee Dataset that was found on Kaggle.com.
2.  Data Preparation and Exploration - Exploring the data and analysing the soundwaves and Spectograms. 
3.	Data Augmentation - Added artifacts like noise and time streching to to increase the diversity of the dataset, improving the chances for better predictions.
4.	Feature Extraction - using Zero Crossing Rate, Chroma_stft, MFCC, RMS(root mean square) value and MelSpectogram to convert the audio dataset into an understandable format for modelling. 
5.	Modelling - The data is normalized and splitted for training and testing. By using a CNN (Convolutional Neural Network) model, 61% of accuracy was reached. There is also another notebook with a supposedly 97% of accuracy for further analysis.

## Data Sonification

1.	Call Center Data Exploration - A dataset from a Call Center including emotions that (artificially) were added to it (CCDataExp). 
2.	Data Visualization - Visualizing the AHT (Average Handle Time) and FCR (First Call Resolution) from the Dataset (CCDataViz).
3.	Data Sonification - Sonifying the same AHT and FCR (CCDataSon)
4.	Functions that returns the visualization and sonification of the AHT and FCR from an especific agent, in an especific period of time (AHTfunction and FCRfuction). 

## Data

Here is the complete AudioSet converted in a Dataframe by Feature Extraction techniques, the history_callback from the CNN model trained and the Dataframe of angry calls.

LINKS: 
Motion Charts made in Tableau & Ableton Live

AHT – Agent Handle Time 
https://public.tableau.com/views/Book2_16964089103160/AgentID32400?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

FCR – First Call Resolution %
https://public.tableau.com/app/profile/sebastian.bayne/viz/FCRMotion/Sheet1?publish=yes

Merging sound with Motion Chart using Ableton Live (no audio)
https://youtu.be/U8qZszm0AZQ

Example of finished Visualization & Sonification
https://youtu.be/maDb4j6rqWU

