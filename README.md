# Smart Parking Solution in Kathmandu

hello again, who does'nt Struggle to find parking in Kathmandu’s busy streets?  We’re working on a smart solution to make parking easier, This includes features such as,

- Find nearest parking spots
- Compare parking prices
- View parking facilities and services
- Real-time availability updates
- Interactive maps and navigation
- high parking securities 
- digital payment options 

## Introduction

A modern web application for finding and managing parking spaces in your area. This system helps users locate the nearest and most affordable parking spots along with detailed information about facilities and services.

## Development

- HTML5
- CSS3
- JavaScript
- Google Maps API (to be integrated)

## Development

This project is under active development. Future updates will include:
- User authentication
- Real-time parking spot availability
- Payment integration
- Mobile app version
- Admin dashboard

## suggested name for brand development includes 
- Parkify - ***my suggestion***
- Bhada Parking – Inspired by "Bhada" (fare), easy for locals to relate to.
- Chhito Park – "Chhito" means fast, making it sound efficient and reliable.
- Sajilo Park – "Sajilo" means easy, making it user-friendly.
- Yatra Park – "Yatra" (journey) signifies travel and convenience.
- Hamro Park 
- Fair box

## Importance of machine learning 
Creating a machine learning model for solving parking problems of Nepal requires steps like collecting relevant datasets, picking suitable models, and doing competition analysis. 

### 1. Training Datasets

To teach your model appropriately, consider the following datasets that can be accessed publicly: 

* PKLot Dataset(***PAPERSWITHCODE.COM***)
   This dataset includes 12,417 images of parking lots as well as 695,899 segmented images of parking spaces, which are marked as filled or unfilled. It is useful in parking space classification tasks because it was captured under different weather conditions in Brazil. Papercitation.  
  
* CNRPark-EXT Dataset(***CNRPARK.IT***)
  This dataset has around 150,00 visually occupancy marked images captured from different weather conditions for variety. 

* CARPK Dataset(***DATASETS.ACTIVELOOP.AI***)
  Contains images from drone surveillance over parking lots containing approximately 90,000 vehicles images with annotations. It is useful in tasks such as vehicle counting and detection. 

* Parking Space Detection Dataset(***KAGGLE.COM***)
  Available on Kaggle, this dataset comes with images of parking spaces as well as their respective bounding box annotations. Useful in both detection and classification problems. 


### 2. Model Selection: 

For vehicle detection and estimation of parking durations, the following methods can also be applied. 

* Object Detection Models: YOLO (You Only Look Once) and Faster R-CNN are good options
  for real time vehicle detection in parking spaces. These models localize and classify vehicles in images or video frames. 

* Convolutional Neural Networks (CNNs): These are very efficient when the task is image classification. They can also be used to check occupancy of parking spaces by looking at images from surveillance cameras. 

* Recurrent Neural Networks (RNNs): For time series data analysis such as time of vehicle arrival and departure to determine the duration of time parked, RNNs or Long Short-Term Memory networks (LSTMs) would be helpful.


### 3. Competitors Offering Real-Time Parking Services:


* IMS Software Pvt. Ltd.(***IMSSOFTWARE.COM.NP***)
  Based in Nepal, IMS offers a Parking Management System featuring automated ticketing, real-time tracking, and reporting for modern parking solutions. 


Additionally, discussions on platforms like Reddit indicate a growing interest in app-based parking solutions in Nepal, suggesting potential market opportunities. 
REDDIT.COM

### 4. Considerations:

- Data Relevance: While the mentioned datasets are valuable, they originate from different countries. Ensure that the data aligns with Nepal's specific parking scenarios or consider collecting local data for more accurate modeling.

- Model Adaptation: Pre-trained models can serve as a starting point, but fine-tuning them with local data will enhance their performance in Nepal's context.

- Regulatory Compliance: Ensure that your data collection and usage comply with local regulations and privacy laws.