# Fifth Tribe and QUESTech Sponsored Datathon

In this Datathon, I worked with Melvin Rajendran to analyze the major trends of Elon Musk's tweets and Tesla order cancellations.

By conducting thorough analysis and external research, **we provided insights and recommendations relating to the behavior, sentiment, and patterns surrounding Elon Musk and Tesla**. We started with two datasets - one set of Elon Musk's tweets, and one set of tweets related to cancelled tesla orders.

Our work was scored based on three equally weighted categories - depth of analysis, breadth of analysis, and how actionable our recommendations were. Luckily, our hardwork paid off and our team was were able to win **first place** - a $500 check!

![download](https://user-images.githubusercontent.com/44681827/223003867-0532787c-049d-479a-ab74-6758fb7637a3.png)

&nbsp;

## Tools and Libraries Used:

For our project, we used **Jupyter Notebook**, along with the following libraries:

- **nltk**: This library provides a number of natural language processing tools, such as stopwords and lemmatization.
- **numpy**: This library provides a number of numerical computation tools.
- **pandas**: This library provides a number of tools for working with data frames.
- **seaborn**: This library is used for creating statistical visualizations.
- **pickle**: This library is used for serializing and deserializing objects.
- **pyLDAvis**: This library is used to visualize topic models.
- **re**: This library provides tools for regular expression matching.
- **collections**: This library provides a number of useful data structures, such as Counter, which is used to count the frequency of words in a text corpus.
- **gensim**: This library provides a number of tools for natural language processing, including topic modeling.
- **matplotlib**: This library is used for creating visualizations, such as word clouds.
- **pprint**: This library is used to pretty-print data structures.
- **wordcloud**: This library is used to create word clouds.

  &nbsp;
  
### We Found Four Strongly Correlated Reasons for Tesla Order Cancellations:
- Difficulty ordering or receiving a Tesla (32%)
- Issues with customer service (25.6%)
- Elon Musk's online persona (25.3%)
- Tesla's supply chain (17.1%)
  
![Screenshot 2023-03-05 at 8 54 40 PM](https://user-images.githubusercontent.com/44681827/223002285-5fb555bc-dd9b-41ce-9aa4-72407a66d1f0.png?scale=0.5)

&nbsp;

### Additonally, These Three Topics in Elon Musk's Tweets are Strongly Correlated with Tesla Order Cancellation:
- His acquisition of Twitter (39.7%)
- Politics (30.2%)
- Engaging in discourse / Tagging others (30.1%)

![Screenshot 2023-03-05 at 8 55 40 PM](https://user-images.githubusercontent.com/44681827/223002367-b23fde7d-889a-4571-a473-230d01b7d81d.png)

## Recommendations
- **Streamline the Tesla delivery process.** This includes providing regular updates on delivery timelines, offering convenient delivery options, and providing a         more seamless handover experience.
- **Improve the customer experience.** This includes incentivizing the mobile service program, expanding the service center network, and personalizing the customer experience.
- **Invest in domestic manufacturing facilities.** This would simplify the supply chain and reduce the risk of disruptions.
- **Elon Musk should avoid discussing topics strongly correlated to Tesla cancellation.** This would help to reduce customer anxiety and improve the perception of Tesla as a reliable brand.

&nbsp;

## Five-year Implementation Outline:
### Year 1:
Conduct customer feedback surveys to identify specific areas for improvement in customer service.
Hire and train additional customer service personnel to improve response times.
Conduct feasibility studies and site selection for a new factory and begin the process of securing funding and permits.
### Year 2:
Launch an online knowledge base and self-help tools to empower customers to troubleshoot and resolve common issues on their own.
Begin construction on the new factory and install the necessary equipment and infrastructure.
### Year 3:
Launch a customer loyalty program to reward repeat purchases and referrals.
Complete construction of the new factory and begin production.
### Year 4:
Develop new partnerships with other companies to increase reach and accessibility for customers.
Introduce new product lines or features to increase demand and maintain a competitive edge.
### Year 5:
Continue to refine and optimize the customer service system, production processes, and distribution channels.
Evaluate and review progress.

&nbsp;

## Project Timeline:
### Data Collection:
Reading in tweet data from CSV files.
### Data Cleaning:
- Removing unnecessary columns and unwanted characters.
- Converting text to lower-case.
- Expanding contractions.
- Lemmatizing every word.
- Converting every tweet into a list of words.
### Data Exploration:
- Creating a list of stop words to eliminate bias.
- Data Modeling:
- Performing Latent Dirichlet Allocation (LDA) topic modeling.
- Determining the number of topics based on the maximized coherence.
### Data Visualization:
- Creating word clouds.
- Plotting coherence score vs. number of topics.
- Displaying a bar chart for the top-30 most relevant terms for each topic.

&nbsp;

## Note:
We ran out of time to eliminate all bias, such as selection and confirmation bias when analyzing the tweets.  We also did not address the potential for bot data to comprise some of our results. These issues could be addressed with a continuation of this project.
 
I hope this is helpful! Let me know if you have any other questions. Additionally, go check out Melvin's Github Page: https://github.com/melvinrajendran
