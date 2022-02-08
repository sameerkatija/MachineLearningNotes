Data Science

# Data Science Notes

## Definitions

### 1. Business

- An ongoing legal activity operating on a for-profit basis
- An Organization that exists to make money

### 2. Data

- Information gathered for reference
- Businesses store data to track activities and make inferences that can help them perform better

#### a. Qualitative Data

- Comes in the form of text and is descriptive in nature
- Doesn't provide a precise specification but approximates
- Contains no numbers
  - Eg. Customer Feedback

#### b. Quantitative Data

- Numeric data
- Quantifiable information that can be involved in statistical and mathematical computuations
  - Eg. Numbers of units produced

### 3. Analysis

- The separation of a whole into smaller, digestible components to be studied individually and examined how they releate to other parts
- Breaking down available data into pieces/making parts
- Any dataset you will work on will always contain past data.

### 4. Analytics

- Analysis + Logical and computational reasoning
- Explore patterns in your data by applying logics and reasoning to predict the future outcome.

### 5. Business Intelligence (BI)

- Studies the past of a company
- Comprises several activities, including business and data analysis
- It takes full advantage of rational databases

### 6. Data Science

DataScience is an inter disciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from many structural anf unstructural data.

- Relies on certain characteristics of business and data analytics
- Often involves the implementation of machine learning algotrithms
- Sometimes advanced statostical methods and regression analysis can do the job
- However you still have to ensure that your data has been properly prepared in advanveDataScience is an inter disciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from many structural anf unstructural data.
- Relies on certain characteristics of business and data analytics
- Often involves the implementation of machine learning algotrithms

### 7. Mathematics for Data Science

#### a. Matrix

A matrix is a collection of Numbers ordered in rows and columns.
E.g:

<center>

![Latex to image](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bequation*%7D%20A_%7B%283x3%29%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%26%203%20%5C%5C%204%20%26%205%20%26%206%20%5C%5C%207%20%26%208%20%26%209%20%5Cend%7Bbmatrix%7D%20%5Cend%7Bequation*%7D)

</center>
- Matrices are main characters in mathametical operations
- A matrices can only contains numbers, symbols, or expressions
- If any matric is A<sub> m x n</sub>. It means the matrixs has m rows and n columns

#### b. Scalars

All numbers we know from algebra are referred to as scalars in Linear Algebra
E.g:
15, 1, 2 , [-5], pi etc

#### c. Vectors

A vector is practically the simplest Linear Algebra object, it is single dimension.
E.g:

- Row vector
  <center>

  ![Image of row vector](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bequation*%7D%20A_%7B1%20x%203%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%26%202%20%26%203%20%5Cend%7Bbmatrix%7D%20%5Cend%7Bequation*%7D)

  </center>

- Column vector
  <center>

  ![Image of column vector](https://latex.codecogs.com/gif.latex?%5Cbegin%7Bequation*%7D%20A_%7B3%20x%201%7D%20%3D%20%5Cbegin%7Bbmatrix%7D%201%20%5C%5C%203%20%5C%5C%203%20%5Cend%7Bbmatrix%7D%20%5Cend%7Bequation*%7D)

  </center>

### 8. What are the basic skills of data scientist?

A Data Scientist

- knows which questions to ask,
- can interpret the data well
- understands the structure of the data
- can be comfortable to work in team

### 9. Why we use data visualization?

There are two primary uses for data visualization:

- To explore data
- To communicate data

### 10. Famous Libraries for visualization

- seaborn is built on top of matplotlib and allows you to easily produce prettier (and more complex) visualizations.
- D3.js is a JavaScript library for producing sophisticated interactive visualizations for the web. Although it is not in Python, it is both trendy and widely used, and it is well worth your while to be familiar with it.
- Bokeh is a newer library that brings D3-style visualizations into Python.
- ### 11 Data Analyst
  A person whose job is to examine information in order to find something out, or to help with decisions. he makes data more meaningful than just lines on a spreadsheet.

### 12. Cleaning Data

Data Cleaning is a very active part of data analysis. It allows you to add data and calculations, and reshape data into the way you need it for reporting, charts, and futher analysis.

### 13. Confounder

An extraneous variable that may affect the relationship between the dependent and independent variables.

### 14. Data Analysis Process.

1. Ask
2. Prepare
3. Process
4. Analyze
5. Share
6. Act.

### Important Points

- The ability to understand what creates economic value in an organization and in industury is key strength
- Data isn't a valueable asset in itself, it is the data insights that are the real treasure.
- What does a data analyst do?
  - Formulate Questions
  - Data Gathering/Data Collection
  - Data Cleaning
  - Data preprocessing
  - Data visualization and anaysis
  - Train Algortihms (ML)
  - Evalute the Algo (ML)
- Process involved in data science
  - Formulate Question
  - Gather data
  - Clean data
  - Explore and visualize
  - Train Algorithms
  - Evaluate
- Well formulated questions will help you do better research.
- While it’s not necessary to have a deep understanding of NumPy for many data analytical applications, becoming proficient in array-oriented programming and thinking is a key step along the way to becoming a scientific Python guru.
- np.empty will return an array of all zeros. In some cases, it may return uninitialized “garbage” values.
- Calling numpy.astype always creates a new array (a copy of the data), even if the new dtype is the same as the old dtype.
- Comparisons between arrays of the same size yield boolean arrays
- Operations between differently sized arrays is called broadcasting
- The Python keywords and and or do not work with boolean arrays. Use & (and) and | (or) instead.
- Regardless of how many dimensions the array has, the result of fancy indexing in numpy is always one-dimensional.
- Keep in mind that fancy indexing, unlike slicing, always copies the data into a new array.
- np.save and np.load are the two workhorse functions for efficiently saving and loading array data on disk. Arrays are saved by default in an uncompressed raw binary format with file extension .npy:
- A fundamental part of the data scientist’s toolkit is data visualization. Although it is very easy to create visualizations, it’s much harder to produce good ones.
- Using lists as vectors is great for exposition but terrible for performance.
- Statistics refers to the mathematics and techniques with which we understand data.
- My advice to an aspiring data scientist is to be curious, extremely argumentative and judgmental. Curiosity is absolute must. If you're not curious, you would not know what to do with the data. Judgmental because if you do not have preconceived notions about things you wouldn't know where to begin with. Argumentative because if you can argument and if you can plead a case, at least you can start somewhere and then you learn from data and then you modify your assumptions and hypotheses and your data would help you learn.
- Process of data analysis
  1.  Inspecting data
  2.  Cleaningdata
  3.  Transformingdata
  4.  Modeling data
  5.  Using data to inform decision-making
- A chart is worth of thousands line of data
- A good data scientist asks questions first and seeks out relevant data second.
- You could have all the data you could ever hope for, but if you don’t have a question to start, the data is useless.
- This “balancing” of confounders is often achieved by randomization.
- Clean data is the key to making sure your data has integrity before you analyze it.
