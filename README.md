# Data Visualization on Sucidal Rates Dataset

## TABLE OF CONTENTS

1.	Introduction
2.	Data Analysis
3.	Data Visualization
4.	Machine Learning
5.	Conclusion
6.	References


































## INTRODUCTION

Every year close to 800 000 people take their own life and there are many more people who attempt suicide. Every suicide is a tragedy that affects families, communities and entire countries and has long-lasting effects on the people left behind. Suicide occurs throughout the lifespan and was the second leading cause of death among 15–29-year-olds globally in 2016. Suicide does not just occur in high-income countries, but is a global phenomenon in all regions of the world. In fact, over 79% of global suicides occurred in low- and middle-income countries in 2016. Suicide is a serious public health problem; however, suicides are preventable with timely, evidence-based and often low-cost interventions. For national responses to be effective, a comprehensive multispectral suicide prevention strategy is needed. The dataset for the same have been acquired from Kaggle [1]. This compiled dataset pulled from four other datasets linked by time and place, and was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum. The dataset contains the following columns:
•	country
•	year
•	sex
•	age
•	suicides_no
•	population
•	suicides/100k pop
•	country-year
•	HDI for year
•	gdp_for_year ($)
•	gdp_per_capita ($)
•	generation 

The project is basically categorized into 3 sections: Data Analysis, Data Visualization and classification using through Machine Learning. The sections are briefly described below. The tools primarily used are matplotlib and seaborn libraries for data visualization. The machine learning algorithms used in the project are Logisitic Regression, Decision Tree, k- Nearest Neighbour, Support Vector Machine and Random Forest with some feature selection techniques like boruta, Principal Component Analysis and Mutual Information.
















## DATA ANALYSIS

Data Analysis is the process of systematically applying statistical and/or logical techniques to describe and illustrate, condense and recap, and evaluate data. According to Shamoo and Resnik (2003) various analytic procedures “provide a way of drawing inductive inferences from data and distinguishing the signal (the phenomenon of interest) from the noise (statistical fluctuations) present in the data”..
While data analysis in qualitative research can include statistical procedures, many times analysis becomes an ongoing iterative process where data is continuously collected and analyzed almost simultaneously. Indeed, researchers generally analyze for patterns in observations through the entire data collection phase (Savenye, Robinson, 2004). The form of the analysis is determined by the specific qualitative approach taken (field study, ethnography content analysis, oral history, biography, unobtrusive research) and the form of the data (field notes, documents, audiotape, videotape).
An essential component of ensuring data integrity is the accurate and appropriate analysis of research findings. Improper statistical analyses distort scientific findings, mislead casual readers (Shepard, 2002), and may negatively influence the public perception of research. Integrity issues are just as relevant to analysis of non-statistical data as well.
Data Analysis Process consists of the following phases that are iterative in nature −
•	Data Requirements Specification
•	Data Collection
•	Data Processing
•	Data Cleaning
•	Data Analysis
•	Communication

### Data Requirements Specification
The data required for analysis is based on a question or an experiment. Based on the requirements of those directing the analysis, the data necessary as inputs to the analysis is identified (e.g., Population of people). Specific variables regarding a population (e.g., Age and Income) may be specified and obtained. Data may be numerical or categorical.
•	Data Collection
Data Collection is the process of gathering information on targeted variables identified as data requirements. The emphasis is on ensuring accurate and honest collection of data. Data Collection ensures that data gathered is accurate such that the related decisions are valid. Data Collection provides both a baseline to measure and a target to improve.
Data is collected from various sources ranging from organizational databases to the information in web pages. The data thus obtained, may not be structured and may contain irrelevant information. Hence, the collected data is required to be subjected to Data Processing and Data Cleaning.
•	Data Processing
The data that is collected must be processed or organized for analysis. This includes structuring the data as required for the relevant Analysis Tools. For example, the data might have to be placed into rows and columns in a table within a Spreadsheet or Statistical Application. A Data Model might have to be created.
•	Data Cleaning
The processed and organized data may be incomplete, contain duplicates, or contain errors. Data Cleaning is the process of preventing and correcting these errors. There are several types of Data Cleaning that depend on the type of data. For example, while cleaning the financial data, certain totals might be compared against reliable published numbers or defined thresholds. Likewise, quantitative data methods can be used for outlier detection that would be subsequently excluded in analysis.
•	Data Analysis
Data that is processed, organized and cleaned would be ready for the analysis. Various data analysis techniques are available to understand, interpret, and derive conclusions based on the requirements. Data Visualization may also be used to examine the data in graphical format, to obtain additional insight regarding the messages within the data.
Statistical Data Models such as Correlation, Regression Analysis can be used to identify the relations among the data variables. These models that are descriptive of the data are helpful in simplifying analysis and communicate results.
The process might require additional Data Cleaning or additional Data Collection, and hence these activities are iterative in nature.
•	Communication
The results of the data analysis are to be reported in a format as required by the users to support their decisions and further action. The feedback from the users might result in additional analysis.
The data analysts can choose data visualization techniques, such as tables and charts, which help in communicating the message clearly and efficiently to the users. The analysis tools provide facility to highlight the required information with color codes and formatting in tables and charts.
 
























## DATA VISUALIZATION

Data visualization is an important skill in applied statistics and machine learning.
Statistics does indeed focus on quantitative descriptions and estimations of data. Data visualization provides an important suite of tools for gaining a qualitative understanding.
This can be helpful when exploring and getting to know a dataset and can help with identifying patterns, corrupt data, outliers, and much more. With a little domain knowledge, data visualizations can be used to express and demonstrate key relationships in plots and charts that are more visceral to yourself and stakeholders than measures of association or significance.
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.
In the world of Big Data, data visualization tools and technologies are essential to analyze massive amounts of information and make data-driven decisions.
There are five key plots that you need to know well for basic data visualization. They are:

•	Line Plot
•	Bar Chart
•	Histogram Plot
•	Box and Whisker Plot
•	Scatter Plot
To communicate information clearly and efficiently, data visualization uses statistical graphics, plots, information graphics and other tools. Numerical data may be encoded using dots, lines, or bars, to visually communicate a quantitative message. Effective visualization helps users analyze and reason about data and evidence. It makes complex data more accessible, understandable and usable. Users may have particular analytical tasks, such as making comparisons or understanding causality, and the design principle of the graphic (i.e., showing comparisons or showing causality) follows the task. Tables are generally used where users will look up a specific measurement, while charts of various types are used to show patterns or relationships in the data for one or more variables.

Data visualization is both an art and a science. It is viewed as a branch of descriptive statistics by some, but also as a grounded theory development tool by others. Increased amounts of data created by Internet activity and an expanding number of sensors in the environment are referred to as "big data" or Internet of things. Processing, analyzing and communicating this data present ethical and analytical challenges for data visualization. The field of data science and practitioners called data scientists help address this challenge.
 

Line Chart
 
                               Bar plot




## MACHINE LEARNING


Arthur Samuel, a pioneer in the field of artificial intelligence and computer gaming, coined the term “Machine Learning”. He defined machine learning as – “Field of study that gives computers the capability to learn without being explicitly programmed”.
In a very layman manner, Machine Learning (ML) can be explained as automating and improving the learning process of computers based on their experiences without being actually programmed i.e. without any human assistance. The process starts with feeding good quality data and then training our machines (computers) by building machine learning models using the data and different algorithms. The choice of algorithms depends on what type of data do we have and what kind of task we are trying to automate.
 
Example: Training of students during exam.
While preparing for the exams students don’t actually cram the subject but try to learn it with complete understanding. Before the examination, they feed their machine (brain) with a good amount of high-quality data (questions and answers from different books or teachers notes or online video lectures). Actually, they are training their brain with input as well as output i.e. what kind of approach or logic do they have to solve a different kind of questions. Each time they solve practice test papers and find the performance (accuracy /score) by comparing answers with answer key given, Gradually, the performance keeps on increasing, gaining more confidence with the adopted approach. That’s how actually models are built, train machine with data (both inputs and outputs are given to model) and when the time comes test on data (with input only) and achieves our model scores by comparing its answer with the actual output which has not been fed while training. Researchers are working with assiduous efforts to improve algorithms, techniques so that these models perform even much better
.
 

Basic Difference in ML and Traditional Programming
•	Traditional Programming : We feed in DATA (Input) + PROGRAM (logic), run it on machine and get output.
•	Machine Learning : We feed in DATA(Input) + Output, run it on machine during training and the machine creates its own program(logic), which can be evaluated while testing.
 
## LEARNING FOR COMPUTER


A computer is said to be learning from Experiences with respect to some class of Tasks, if its performance in a given Task improves with the Experience.
A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E
Example: playing checkers.
E = the experience of playing many games of checkers
T = the task of playing checkers.
P = the probability that the program will win the next game
In general, any machine learning problem can be assigned to one of two broad classifications:
Supervised learning and Unsupervised learning.



## PRACTICAL APPLICATION OF MACHINE LEARNING:-
•	Talking about online shopping, there are millions of users with an unlimited range of interests with respect to brands, colors, price range and many more. While online shopping, buyers tend to search for a number of products. Now, searching a product frequently will make buyer’s Facebook, web pages, search engine or that online store start recommending or showing offers on that particular product. There is no one sitting over there to code such task for each and every user, all this task is completely automatic. Here, ML plays its role. Researchers, data scientists, machine learners build models on the machine using good quality and a huge amount of data and now their machine is automatically performing and even improving with more and more experience and time.
Traditionally, the advertisement was only done using newspapers, magazines and radio but now technology has made us smart enough to do Targeted advertisement (online ad system) which is a way more efficient method to target most receptive audience.
 
•	Even in health care also, ML is doing a fabulous job. Researchers and scientists have prepared models to train machines for detecting cancer just by looking at slide – cell images. For humans to perform this task it would have taken a lot of time. But now, no more delay, machines predict the chances of having or not having cancer with some accuracy and doctors just have to give an assurance call, that’s it. The answer to – how is this possible is very simple -all that is required, is, high computation machine, a large amount of good quality image data, ML model with good algorithms to achieve state-of-the-art results.
Doctors are using ML even to diagnose patients based on different parameters under consideration.
 
•	You all might have use IMDB ratings, Google Photos where it recognizes faces, Google Lens where the ML image-text recognition model can extract text from the images you feed in, Gmail which categories E-mail as social, promotion, updates or forum using text classification, which is a part of ML.
 
WORKING OF A MACHINE LEARNING ALGORITHM
•	Gathering past data in any form suitable for processing.The better the quality of data, the more suitable it will be for modeling
•	Data Processing – Sometimes, the data collected is in the raw form and it needs to be pre-processed.
Example: Some tuples may have missing values for certain attributes, an, in this case, it has to be filled with suitable values in order to perform machine learning or any form of data mining.
Missing values for numerical attributes such as the price of the house may be replaced with the mean value of the attribute whereas missing values for categorical attributes may be replaced with the attribute with the highest mode. This invariably depends on the types of filters we use. If data is in the form of text or images then converting it to numerical form will be required, be it a list or array or matrix. Simply, Data is to be made relevant and consistent. It is to be converted into a format understandable by the machine
•	Divide the input data into training,cross-validation and test sets. The ratio between the respective sets must be 6:2:2
•	Building models with suitable algorithms and techniques on the training set.
•	Testing our conceptualized model with data which was not fed to the model at the time of training and evaluating its performance using metrics such as F1 score, precision and recall.















CONCLUSION
We successfully performed data analysis and data visualization and performed classification using machine learning. The conclusion drawn from analysis and visualization are:
•	The rate of suicides in males is higher than women.
•	The suicide rates have fallen dramatically for the year 2016.
•	The suicide rates are quite high for the age group 24-35 years.
•	The suicide rates highly depend on GDP per capita.


































REFERENCES

1.	https://www.kaggle.com/kralmachine/data-visualization-of-suicide-rates
2.	https://www.kaggle.com/rblcoder/mental-health-happiness-economics-human-freedom
3.	https://seaborn.pydata.org/
4.	https://matplotlib.org/contents.html
5.	https://towardsdatascience.com/data-visualization-with-the-seaborn-library-4a24f65bd315
6.	https://library.uoregon.edu/introduction-data-visualization

