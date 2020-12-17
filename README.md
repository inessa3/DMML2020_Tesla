# DMML2020 Group Tesla
## Team: Inessa Khaneeva, Jakob Kampik, Mariem Guebibia )
### _Real or Not? NLP with Disaster Tweets_
In this project we built a Machine Learning model that can predict which tweets are about a real disasters and which are not. <br/>
<br/>

The computational analysis of text in the form of tweets is a typical problem in NLP (natural language processing). NLP is a subfield of linguistics, computer science, and artificial intelligence concerned with the interactions between computers and human language, in particular how to program computers to process and analyze large amounts of natural language data.
[Source](https://en.wikipedia.org/wiki/Natural_language_processing)
<br/>
Our work consists of four notebooks: <br/>
1. EDA <br/>
2. 1st Iteration Basic Data Cleaning and Basic Predictions <br/>
3. 2nd Iteration Advanced Data Cleaning <br/>
4. 3rd Iteration Other Classifiers <br/>
<br/>

## Github structure and how to run our code
Our Github repository is organised as following : 
* Code: In this folder are the Colab notebooks. To run our code you can just open a notebook and run it with Google Colaboratory.
* Data: Here, we stored all the data files that we used along the project.
* Documents: Here, we stored our presentation pdf and our and image of our results
* README.md: This file is the one which your are reading now.
<br/>

## Our approach
It was our approach to move in iterations:
* First, we needed to understand the problem at hand, so we started with EDA (exploratory data analysis). There, we calculated the base rate and visualized the data. 
* Then, we cleaned the data for the first time and made our first predictions. Here, we obtained our best score, which was 0.811 on AI-crowd. 
* Next, made another iteration and tried to clean the data much better to improve the accuracy. But the accuracy actually decreased.
* Finally, in the third iteration, we tried many classifiers to improve the accuracy, but they all led to a decrease in the accuracy.
<br/>
Conclusively, we can say that our first approach (using basic data cleaning and a logistic regression classifier without cross validation obtained the best accuracy. This might be due to the relatively small data set.<br/>
<br/>

## Our results
![alt text](https://github.com/inessa3/DMML2020_Tesla/blob/main/documents/Results.png)

Here, we made a video where we present our work and our results.<br/>
🎥 The link to two parts of the video : <br/>
Part 1: https://youtu.be/_PluzOFW8OU <br/>
Part 2: https://youtu.be/CSc4zcc48yU <br/>
(Youtube somehow did not accept it when we uploaded it as one video, but this worked.)
<br/>

Enjoy!


## Our weekly progress
📍Week 9-15 November:
1.   We got acquainted with each other 
2.   We created slack channel, github repository for further collaboration (all the members are there 👍)
3.   We also created a team on AIcrowd and joined the competition 🏆 

📍Week 16-22 November:
1.   We have started working on the project in Colab 🗃
        *   Download and describe the training dataset (shape, base rate)
        *   Clean the dataset (duplicates etc WRITE MORE LATER)
        *   Build a model with SpaCy
        *   Make our first prediction 🔮
2.   Uploaded our csv file on AIcrowd
        *   Our accuracy was 0.803 and the F1 score 0.803, too. 

📍 Week 23-29 November:
1.   We have continued working on the project in Colab
        *   We tuned the parameters of the classifier and vectorizer
        *   We also proceeded with EDA 📉
2.   Uploaded several csv files on AIcrowd and, finally, upgraded our score
        *   Our accuracy and the F1 was 0.811 🎉
3.   Made a weekly update on Github (+downloaded our first code) and prepared PowerPoint

📍 Week 30-6 December:
1.   We have continued working on the project in Colab
        *   We made additional data cleaning and try to do more predictions.
        *   We tried grid-search to find better parameters (it does not help us to upgrade our score).
        *   We have also worked on ther classifiers, mainly knn and decision trees.
2.   Uploaded several csv files on AIcrowd but our score was not higher than the previous ones 😢
3.   Made a weekly update on Github

📍 Week 7-13 December:
1.   We have continued working on the project in Colab
        *   We tried to clean test data and repeat the predictions we had with the cleaned version but nothing has improved (we submitted that to AIcrowd but did not present it in notebooks).
        *   Later, we have started preparing our final version of notebooks. We took decisions on the structure of the notebooks (we also add the graph of our progress).
2.   We prepared the Power Point presentation for Monday and  started preparing our video.
3.   Made a weekly update on Github

📍 Week 14-20 December:
1.   We finalize all the notebooks we have for this project.
2.   We recorded a video to be posted on Youtube and shared with our classmates.
3.   Made a weekly update on Github.
4.   Made a post with a link to video on Slack.

