# NLP-Techniques-StanceDetection

## Objective :

Fake news is defined as a “made up story with an intention to deceive, geared towards getting clicks”. Stance Detection is one of the factors influencing fake news detection. It is not practical for humans to fact check every piece of information produced by the media. Hence, the goal of this project is to use natural language processing (NLP) techniques to automate stance detection to determine the quality of the news source. It considers what other organizations write about the same headline. A body of the text is claimed to agree, disagree, discuss, or be unrelated to a headline.

Technical Skills: Jupyter Notebook, Google Collab, Python, NLP, Nltk, TF-IDF, Cosine Similarity, Data-Cleaning, Machine Learning Classification Models, ROC Curves

## Dataset(s) :

From the FakeChallenge.org a dataset has been provided which consists of a headline and a body of text. This body of
text may be from a different article. The output of the system will be the stance of the body of text related to the title. 

Two csvs that I have used to implement the system are:

“Train_bodies.csv”: Contains Body ID and Body Text - no of records : 2532

“Train_stances.csv”: Contains Headline, Body ID and Stance - no of records : 49972

## List of Files :
1. Refer to the pdf document "NLTK_Basics.pdf" to get to know basic terminologies in NLTK world

2. Refer to the research paper "Research_Paper_AlternusVera.pdf" showcasing 4 different factors influencing fake news detection including stance detection. This research paper is combined work in a team of 4

3. Refer to the YouTube video link below to get a quick tour:

	https://youtu.be/5H8WUdT_10c

## Comaprison of Algorithms

![alt text](http://i.imgur.com/Q5JQjfD.png)

<b> I achieved best accuracy of 89.88% as compared to other less performing models with just 43% accuracy score</b>

## ROC Curve

![alt text](http://i.imgur.com/olhBJmW.png)


Thank You,

Vidhi Shah

