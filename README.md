# Data Science Study (CMSE428 EMU)
- People create, recieve and generate data.
- Data is collected by companies to influence our decisions by sending *matching commercials*
- Intelligent algorithms can help you decide which movie to which, which book to read, which place to visit...
- In biometric sensors, algorithms may help understand our emotions and support making better decisions. Help in health as well (detecting cancer cells and start of several diseases)
- Big Tech companies apply *Attension Marketing* business model to collect data (they provide free information, services, intertainment and collect data about us)
- Data should be processed to extract information from it.
- **Main Data Science Concepts**:
    - Data Collection
    - Data Visualization
    - Data Exploration
    - Data Modeling
    - Models Evaluation
- Programming languages used in data science: **python** & **R**
- Data science can be defined as Engineering of Data.
- **Data Scientist** : is capable of making decisions about what data to collect, and why. The need to be able to formulate questions and hypotheses then make a plan for how the problem will be attacked.
- **Components Fields of Data Science**
    - Statistics
    - Algorithms
    - Scientific Methods
    - Machine Learning
    - Data Analysis
    - Models
- ![Data Engineering]()
- Steps of data engineering:
    - Ask question what data needs to be recorded or collected?
    - After row data is collected (emails, logs, medical records, surveys, blood drawn, ...)
    - Data Processing (Pipelines, web-scraping, cleaning, munging, joining, wrangling)
    - Finally data is cleaned and ready (clean, outliers, missing values, debugging, tables)

- Data is never clean!
- The exploratory data analysis combines visualization and data sense => crucial part. (scientist will find patterns, build models, algorithms to serve as prototypes)

### To Implement a DataScience Project:

     - **Discovery**: first phase of data science
          - learn and ivestigate the problem
          - develop context and understanding
          - learn about data source needed and available for the project
          - team formulates initial hypotheses that can be tested later with data.
          - Identify main objective of project
          - Identify what needs to be achieved in business terms
          - Identify what must be done to meet needs
          - consider success creteria
          - Identify kinds of data team will need to solve problem, consider volume, type, time span of the data needed to test the hypothese.
          - in most cases, team will need the row data to avoid introducing bias(by domain experts) for the analysis.
          - Develop set of hypotheses
              - Form ideas that can be tested
              - Come up with few primary hypothese to test.
              - Hypothesis form the basis of the analytical tests the team will use in later phases and serve as foundation for findings to be shared
          - Make a list of candidate data sources team may need.
          - make inventory of datasets currently available.
          - Begin understanding the interdepndencies among data attributes and become familliar with content of data, its quality and limitations
          - Evaluate data structures and tools needed.
            
     - **Data Preperation**: includes steps to explore, preprocess data
           - team needs to create robust environment in which it can explore data that is separate from production environment.
           - > critical aspect of data science project is to become familiear with the data itself
           - Data Conditioning = cleaning data, normalizing datasets, performing transformations on data.
                 - join data
                 - merge data
           - Visualization to gain overview of data.
     - **Model Planning**:
           - team identifies candidate models to apply (clustering, classifying, finding relationships in data depending on goal of project)
           - the objective of data exploration in this phase is to understand the relationships among the variables to inform selection of variables and methods and to understand problem domain
           - better variable sets lead to better models. (use tools to perform data visualizations)
           - *team main goal is to choose an analytical technique* based on end goal of the project. 
     - **Model Building**: training and testing the model
           - gain training data and test data.
           - model is fit on the training data
           - model is evaluated againest the test data
           - model planning and model building phases can overlap, in practice we can iterate between the two phases for a while.
           - Modeling tools:
                 - R: strong statistical language
                 - Octave: free software programming language for computational modeling, has some of MATLAB functionalities.
                 - WEKA: free data mining software package (can be executed within java code.
                 - Python: provides toolkits for ML and analytics such as scikit-learn, numpy, scipy, pandas, matplotlib..
       
     - **Communicate Results**:
         - team compares outcomes of modeling to the criteria
         - team must be rigorous enough to prove or disprove the hypotheses outlined in discovery phase.
         - determine if results are statistically significant and valid.
  
     - **Operationalize**:
          - team communicates benefits of project more broadly.
          - deploy work in a controlled way before broadening work to a full enterprise or ecosystem of users.
          - team learns about performance and related constraints of the model production environment on a small scale then make adjustments before a full deployment.
          - create mechanisim for performing ongoing monitoring of model accuracy, and if accuracy degrades, find a way to retrain model.

### Case Study (Development of a Daibetes Detection App Based on non-invasive Biomarkers)
1. Discovery
    - form a team involving diabetes experts.
    - know how long will it take to collect data? how to identify participants? which hospital?
    - know which measuring device will be needed(to measure weight, height..)
    - know where to store data
    - know who will be responsible for data collection
    - know what will be the main objective of the project
    - know what should be the main characteristics of the app?
    - know about the performance of the model in terms of True Positive Rate and False Positive Rate
    - know what will be the hypothesis?
      
2. Data preperation
    - know if there are missing values?
    - normalization, transformation needed or not?
    - cleaning?
    - Labeling?
    - Visualization for deeper understaning?
    - Number of participants?
  
     
3. Model planning
    - which model to use?
    - should we apply backward elimination to choose the best variable set?
    - are other methods of variable selection needed?
      
4. Model building
     - split data to two parts: training and testing data
     - you can use 10-fold cross validation for this purpose
     - compute detection performance of the models developed
       
5. Communicate results
     - implement the model as a mobile app
     - present the expected performance of the developed system in practice to the experts in domain
     - present the findings in terms of strengths and weaknesses
     - present the resultant system to the experts in the domain and explain how to use it
       
6. Operationalize
     - set up a pilot project to evaluate the app
     - identify the characteristics of the people for whom the model fails

----
