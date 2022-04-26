# Data Analytics Notes

## Definitions

### 1. Key Players in the Data Ecosystem
- Data Engineering convert raw data into usable data
- Data Analytics use this data to generate insights
- Data Scientists use Data Analytics and Data Engineering to predict the future using data from the past
- Business Analysts and Business Intelligence Analysts use these insights and predictions to drive decisions that benefit and grow their business

### 2. Data Analysis
Data analysis is the process of gathering, cleaning, analyzing and mining data, interpreting results, and reporting the findings. 
With data analysis we find patterns within data and correlations between different data points. And it is through these patterns and correlations that insights are generated, and conclusions are drawn. 

### 3. Different types of Data Analysis

#### 1. Descriptive Analytics
Descriptive Analytics helps answer questions about what happened over a given period of time by summarizing past data and presenting the findings to stakeholders. It helps provide essential insights into past events. For example, tracking past performance based on the organization's key performance indicators or cash flow analysis.

#### 2. Diagnostic analytics

Diagnostic analytics helps answer the question. Why did it happen? It takes the insights from descriptive analytics to dig deeper to find the cause of the outcome. For example, a sudden change in traffic to a website without an obvious cause or an increase in sales in a region where there has been no change in marketing. 

#### 3. Predictive analytics

Predictive analytics helps answer the question, What will happen next? Historical data and trends are used to predict future outcomes. Some of the areas in which businesses apply predictive analysis are risk assessment and sales forecasts. It's important to note that the purpose of predictive analytics is not. to say what will happen in the future, it's objective is to forecast what might happen in the future. All predictions are probabilistic in nature.

#### 4. Prescriptive Analytics 

Prescriptive Analytics helps answer the question, What should be done about it? By analyzing past decisions and events, the likelihood of different outcomes. Is estimated on the basis of which a course of action is decided. Self-driving cars are a good example of Prescriptive Analytics. 

### 4. The Data Analysis Process

1. Understanding the problem and desired result
	- Where you are and where you want to be should be clearly defined before the analysis process begins.
2. Setting a clear metric
	- Deciding what will be measured and how it will be measured 
3. Gathering data
	- Identifying data you require, the sources from which you will access this data, and the best tools for the job
4. Cleaning data
	- Fixing quality issues in the data and standardizing data coming in from multiple sources.
5. Analyzing and Mining data
	- Extracting, analyzing, and manipulatig data from difference perspectives to understand trends, identify correlations, and find patterns and variations.
6. Interpreting results
	- Interpreting results, evaluating defendability of analysis and circumstances under which analysis may not hold true
7. Presenting your findings
	- Communicating and presenting your findings in clear, impactful, and convincing ways.

### 5. Diff between Data Analysis vs Data Analytics

The terms Data Analysis and  Data Analytics are often used interchangeably.

However it is important to note that there is a subtle difference between the terms and meaning of the words Analysis and Analytics.  In fact some people go far as saying that these terms mean different things and should not be used interchangeably. Yes, there is a technical difference...

The dictionary meanings are:

> Analysis - detailed examination of the elements or structure of something

> Analytics - the systematic computational analysis of data or statistics

Analysis can be done without numbers or data, such as business analysis psycho analysis, etc. Whereas Analytics, even when used without the prefix "Data", almost invariably implies use of data for perfoming numerical manipulation and inference. 

So we take a more liberal view, and use the terms Data Analysis and Data Analytics to mean the same thing.

### 6. Responsibilities of a Data Analyst
-  Acquiring data from primary and secondary data sources.
- Creating queries to extract required data from databases and other data collection systems. 
- Filtering, cleaning, standardizing, and reorganizing data in preparation for data analysis. 
- Using statistical tools to interpret data sets.
- Using statistical techniques to identify patterns and correlations in data.
- Analyzing patterns in complex data sets and interpreting trends. 
- Preparing reports and charts.
- Creating appropriate documentation to define and demonstrate the steps of the data analysis process.

### 7. Skills required for Data Analysis
The data analysis process requires a combination of technical, functional, and soft skills.
- Technical Skills
	1. Microsoft Excel or Google Sheets
	2. Microsoft Power BI, SAS or Tableau
	3. Python, R, Java or MATLAB
	4. SQL and NOSQL Databases
	5. Hadoop, Hive and Spark
- Functional Skills
	1. Proficiency in Statistics
		- Analyze data, validate the analysis, identify fallacies and logical errors
	2. Analytical skills
		- Research and interpert data, theorize, make forecasts
	3. Problem-Solving Skills
		- Come up with possible solutions for a given problem
	4. Probing skills
		- Identify and define the problem statement and desired outcome
	5. Data Visualization Skills
		- Create clear and compelling visualizations to present the analysis
	6. Project Management skills
		- Manage the process, prople, dependencies and timelines
- Soft Skills
	1. Your ability to:
		- work collaboratively with business and cross-functional teams
		- communicate effectively to report and present your findings
		- tell a compelling and convincing story
		- gather support and buy-in for your work
	2. Curiosity
		- Allowing new questions to surface and challenging your own assumptions and hypotheses
	3. Intuition 
		- Having a sense of the future based on pattern recognition and past experiences
  
### 8. Types of Data
Data is unorganized information that is processed to make it meaningful. Generally, data comprises of facts, observations, perceptions, numbers, characters, symbols, and images that can be interpreted to derive meaning.
One of the ways in which data can be categorized is by its structure.
#### 1. Structured data 
Data that follows a rigid format and can be organized neatly into rows and columns is structured data.This is the data that you see typically in databases and spreadsheets.
 
 #### 2. Semi-structured data
 Semi-structured data is a mix of data that has consistent characteristics and data that doesn’t conform to a rigid structure. For example, emails
  
  #### 3. Unstructured data 
Data that is complex, and mostly qualitative information that is impossible to reduce to rows and columns. For example, photos, videos, text files, PDFs, and social media content. 

### 9. Database
A database is a collection of data, or information, designed for the input, storage, search and retrieval, and modification of data. And a Database Management System, or DBMS, is a set of programs that creates and maintains the database. It allows you to store, modify, and extract information from the database using a function called querying.

### 10. Relational Database
A relational database is a collection of data organized into a table structure, where the tables can be linked, or related, based on data common to each. Tables are made of rows and columns, where rows are the “records”, and the columns the “attributes”. 

### 11. NoSQL Database

NoSQL, or “Not Only SQL”. Non-relational databases emerged in response to the volume, diversity, and speed at which data is being generated today, mainly influenced by advances in cloud computing, the Internet of Things, and social media proliferation. Built for speed, flexibility, and scale, non-relational databases made it possible to store data in a schema-less or free-form fashion. NoSQL is widely used for processing big data.

### 12. Data warehouse
A data warehouse works as a central repository that merges information coming from disparate sources and consolidates it through the extract, transform, and load process, also known as the ETL process, into one comprehensive database for analytics and business intelligence. At a very high-level, the ETL process helps you to extract data from different data sources, transform the data into a clean and usable state, and load the data into the enterprise’s data repository

### 13. Big Data Stores
Big Data Stores, that include distributed computational and storage infrastructure to store, scale, and process very large data sets.

### 14. Data mart  
A data mart is a sub-section of the data warehouse, built specifically for a particular business function, purpose, or community of users. The idea is to provide stakeholders data that is most relevant to them, when they need it. For example, the sales or finance teams accessing data for their quarterly reporting and projections. 
Since a data mart offers analytical capabilities for a restricted area of the data warehouse, it offers isolated security and isolated performance. The most important role of a data mart is business-specific reporting and analytics. 

### 15. Data Lake
 A Data Lake is a storage repository that can store large amounts of structured, semi-structured, and unstructured data in their native format, classified and tagged with metadata. So, while a data warehouse stores data processed for a specific need, a data lake is a pool of raw data where each data element is given a unique identifier and is tagged with metatags for further use. You would opt for a data lake if you generate, or have access to, large volumes of data on an ongoing basis, but don’t want to be restricted to specific or pre-defined use cases. Unlike data warehouses, a data lake would retain all source data, without any exclusions. And the data could include all types of data sources and types. Data lakes are sometimes also used as a staging area of a data warehouse. The most important role of a data lake is in predictive and advanced analytics. 

### 16. ETL
ETL is how raw data is converted into analysis-ready data. It is an automated process in which you gather raw data from identified sources, extract the information that aligns with your reporting and analysis needs, clean, standardize, and transform that data into a format that is usable in the context of your organization; and load it into a data repository. While ETL is a generic process, the actual job can be very different in usage, utility, and complexity.

### 17. Batch processing
Batch processing, meaning source data, is moved in large chunks from the source to the target system at scheduled intervals. Tools for batch processing include Stitch and Blendo.

### 18. Stream processing
Stream processing, which means source data is pulled in real-time from the source and transformed while it is in transit and before it is loaded into the data repository. Tools for stream processing include Apache Samza, Apache Storm, and Apache Kafka. 

### 19. Data pipeline
A data pipeline is a high performing system that supports both long-running batch queries and smaller interactive queries. The destination for a data pipeline is typically a data lake, although the data may also be loaded to different target destinations, such as another application or a visualization tool. There are a number of data pipeline solutions available, most popular among them being Apache Beam and DataFlow.

### 20. Big Data
Big data refers to the dynamic, large, and disparate volumes of data being created by people, tools, and machines. It requires new, innovative and scalable technology to collect, host, and analytically process the vast amount of data gathered in order to drive real-time business insights that relate to consumers, risk, profit, performance, productivity management, and enhanced shareholder value. 
There is no one definition of big data but there are certain elements that are common across the different definitions, such as 
- Velocity : Velocity is the speed at which data accumulates..
- Volume: Volume is the scale of the data or the increase in the amount of data stored
- Variety: Variety is the diversity of the data.
- Veracity:  Veracity is the quality and origin of data and its conformity to facts and accuracy.
- Value. Value is our ability and need to turn data into value.

These are the V's of big data

### 21. The process of identifying data 
The process of identifying data begins by 
1. Step 1: determining the information you want to collect. 
	- The specific information you need
	- the possible sources for this data.
2. Step 2: Define a plan for collecting data
	- Establish a timeframe for collecting data
	- How much data is sufficient for a credible analysis
	- Define dependencies, risks, and mitigation plan.
3. Determine yout data collection methods
	- The methods depend on:
		- Source of Data
		-  Type of data
		-  Timeframe over which you need the data
		-  Volume of data

The data you identify, the source of that data, and the practices you employ for gathering the data have implications for quality, security, and privacy.

### 22. Data Sources
Data sources can be internal or external to the organization, and they can be primary, secondary or third party sources of data. 
#### 1. Primary Data
The term primary data refers to information obtained directly by you from the source. This could be from internal sources such as data from the organization, CRM, HR or workflow applications. It could also include data you gather directly through surveys, interviews, discussions, observations and focus groups. 
#### 2. Secondary data
Secondary data refers to information retrieved from existing sources, such as external databases, research articles, publications, training material and Internet searches, or financial records available as public data. This could also include data collected through externally conducted surveys, interviews, discussions, observations and focus groups. 
#### 3. Third party data
Third party data is data you purchased from aggregators who collect data from various sources and combine it into comprehensive datasets purely for the purpose of selling the data.

## Important Points