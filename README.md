## Project
CLINOS - AI Tools for Clinical Trials and Procedures

## Website
clinos.us

## Hackathon
https://devpost.com/software/clinos-ai-tools-for-clinical-trials-and-procedures

## Video
https://youtu.be/YXhGLP8knoE

## Teammates
Lalit Patel, Sean Patel, Laxmi Patel, Ruchi Patel

## Inspiration

We have often found some healthcare researchers and other professionals in a dire need for some tools for getting information and processing data. 

## What it does

The clinos.us website offers 5 tools named Chat Bot, Correlations Matrix, Machine Learning, X-ray Classification, and Articles Links.

The Chat Bot page allows you to get your questions answered by Google's Gemini AI or OpenAI's ChatGPT. In the form, if you write your health conditions, eating status, and medicines to be taken together, Gemini can alert you about possible complications from the medicines. If you write your dietary restrictions, health issues, and a food selection available, Gemini can advise you what food you should select. If you write a general question, Gemini can answer it as best as it can. In the right bottom corner, if you click the icon and then submit your question, ChatGPT can answer it as best as it can.

The Correlations Matrix page allows you to do a statistical analysis of your data. You may use the default dataset or feed your own dataset. After you click the Send button, the website's Python back-end provides a statistics of the dataset, a matrix of correlations of the columns of the dataset, and first few records. This tool can be immensely useful for healthcare researchers and practitioners.

The Machine Learning page is regarding supervised machine learning. You may use the default dataset or feed your own datasets for training and test purposes. After you click the Send button, the website's Python back-end provides predictions from the test dataset and a valuation of the model used. If you had selected All for supervised machine learning algorithm, the back-end selects the most suitable algorithm for your training dataset. This tool can be very useful for people in the healthcare field.

The X-ray Classification page classifies X-ray images. Images may be fed from a webcam or from files. The back-end uses a JavaScript with a pre-trained image classification model. It classifies each frame or image as a Normal image, or as an image indicating Pneumonia. This can be a very valuable tool for radiologists for preliminary analyses of X-rays.

The Articles Links page contains a list of articles useful for applications and administrations of clinical trials. The page has clickable links to go to the articles and hoverable links to get descriptions of the articles.

## How we built it

For building this website, we have used Python, Django framework, TensorflowJs, and JavaScript. Page templates use html and css. The website is hosted on a shared hosting.
