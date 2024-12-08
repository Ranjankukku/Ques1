# Ques1


### Question 1
<img width="1470" alt="Screenshot 2024-12-08 at 10 04 40 PM" src="https://github.com/user-attachments/assets/0ae6fb00-dd2c-40e4-b125-8ce6ae4361d5">

#### (i) List three (3) important questions you would ask your client.
1. What specific insights or metrics do you want to derive from the collected data (e.g., customer behavior, sales trends)?
2. What is the frequency and granularity of data collection required (e.g., hourly, daily, by department)?
3. Are there any privacy or compliance requirements (e.g., GDPR) that need to be adhered to during data collection?

#### (ii) Describe the data and/or file formats that you are likely to use in collecting the data.
- **Data formats**: CSV, JSON, XML for structured data like receipts; video formats like MP4 for camera feeds.
- **File formats**: Relational database tables for transactional data, and NoSQL document stores for unstructured sensor data.

#### (iii) Suggest a type of database system to use, giving a reason for your choice.
- **Database system**: A hybrid approach using both a relational database (e.g., PostgreSQL) for transactional data and a NoSQL database (e.g., MongoDB) for unstructured sensor data.
- **Reason**: Relational databases are ideal for structured sales data, while NoSQL databases handle the scalability and flexibility needed for unstructured sensor/camera data.

---

#### (i) Why is it useful to categorize data?
Categorizing data helps in organizing it systematically, making it easier to analyze, identify patterns, and derive actionable insights. It also improves searchability and compatibility with analytical tools.

#### (ii) Give possible categories for the following example data:
a. Gender of students studying computer science in Ireland: **Categorical**  
b. Highest current qualification of computing seminar attendees: **Ordinal**  
c. Shoe size of students in CA682: **Numerical (Discrete)**  
d. House prices for all sales in Dublin 9 in 2017: **Numerical (Continuous)**  
e. Global birth rate by country in 2016: **Numerical (Continuous)**  

---

#### Q1(c): Describe activities at each stage of the generic data analytics pipeline and name tools.
1. **Gathering**: Collecting raw data from sources like sensors or surveys. Tool: Apache Kafka.
2. **Processing**: Cleaning and transforming raw data into usable formats. Tool: Python (Pandas).
3. **Analyzing**: Applying statistical or machine learning techniques to extract insights. Tool: R or Python (Scikit-learn).
4. **Presenting**: Visualizing results through charts or dashboards. Tool: Tableau or Power BI.
5. **Preserving**: Storing processed data securely for future use. Tool: Amazon S3 or Hadoop HDFS.

---

### Question 2
<img width="1470" alt="Screenshot 2024-12-08 at 10 05 21 PM" src="https://github.com/user-attachments/assets/050c72ee-2b3d-4847-973f-052f2628a147">

#### (i) Give simple example metadata for describing buildings.
1. Building name
2. Location coordinates
3. Year of construction
4. Primary use/purpose

#### (ii) Why would a standard be useful for this type of metadata?
Standards ensure consistency, interoperability across systems, and ease of integration with other datasets.

#### (iii) Identify one problem with enforcing a standard.
Different organizations may have varying requirements or legacy systems that make adhering to a single standard challenging.

---

#### Q2(b): Explain how the MapReduce algorithm is part of Hadoop and its usefulness.
MapReduce is a programming model within Hadoop used to process large datasets by dividing tasks into two phases:
1. **Map phase**: Processes input data into key-value pairs.
2. **Reduce phase**: Aggregates results from the Map phase.

It is useful because it enables distributed processing across multiple nodes, making it efficient for handling large-scale unstructured or structured datasets.

---

#### Q2(c): REST API components in the URL example:
- Protocol: `http`
- Domain name: `www.example.com`
- Resource path: `/rest/CUSTOMER/`
- Query parameters: `sortBy=age` and `country=US`

---

#### Q2(d): Big Data characteristics and challenges:
(i) Big Data is often varied and unstructured, meaning it includes multiple formats such as text, images, videos, etc., without a predefined schema.  
(ii) This makes it difficult to store in traditional relational databases because they require structured schemas and are not optimized for scalability or diverse formats.

---

### Question 3
<img width="1470" alt="Screenshot 2024-12-08 at 10 07 28 PM" src="https://github.com/user-attachments/assets/cd36d7b6-1e42-4486-9b33-9c9de89ec236">

#### Q3(a): Causes and consequences of poor-quality data:
| Data Source | Cause | Consequence |
|-------------|-------|-------------|
| Census statistics | Outdated information | Misleading policy decisions |
| Survey data | Sampling bias | Unrepresentative insights |
| Traffic counting devices | Sensor malfunction | Incorrect traffic flow analysis |
| Social media content | Noise/spam | Skewed sentiment analysis |
| Predictive model | Inaccurate assumptions | Faulty growth projections |

---

#### Q3(b): Data cleaning approach and quality enforcement:
- **Approach**: For survey data, handle missing values by imputation or removal.
- **Enforcement**: Implement validation rules during survey design to ensure mandatory fields are completed.

---

#### Q3(c): Data quality issues addressed by OpenRefine:
1. Removing duplicates
2. Standardizing inconsistent formatting
3. Handling missing values  
OpenRefine is used during the **Processing** stage of the pipeline.

---

#### Ethical question on sharing patient test data:
No, you cannot share patient test data due to privacy regulations like GDPR unless explicit consent has been obtained or the dataset is anonymized.

---

### Question 4
<img width="1470" alt="Screenshot 2024-12-08 at 10 07 48 PM" src="https://github.com/user-attachments/assets/2e905a67-2056-4c0a-8c5e-beebd42091a9">

#### Q4(a): Appropriate graph types:
A. Scatter plot – To show correlation between vitamin C intake and cold duration.  
B. Stacked bar chart – To compare government expenditure categories over time.  
C. Heatmap – To visualize disease spread geographically and temporally.  
D. Box plot – To compare grade distributions across modules.

---

#### Q4(b): Problems with Figure 1 design:
1. Lack of clear labels on axes.
2. Poor color contrast.
3. Overcrowded elements make it hard to interpret.
Better alternative: Use a grouped bar chart with distinct colors per category.

---

#### Q4(c): Marks and attributes in Figure 2:
- Marks: Bars
- Attributes: Height represents value; color distinguishes categories.

---

#### Q4(d): Design considerations for Visa advertisement:
1. Use clear visuals emphasizing Visa's superior transaction speed.
2. Highlight key statistics with bold text or annotations.

---

### Question 5
<img width="1470" alt="Screenshot 2024-12-08 at 10 08 16 PM" src="https://github.com/user-attachments/assets/3b610aa7-1587-4b28-b9e1-00b627a3e7b3">

#### Q5(a): Sketch components for graph using Figure 3's sample data:
- Title: "First Programming Language Preferences"
- X-axis: Programming languages
- Y-axis: Percentage (%)
- Legend: Color-coded bars
- Tick marks on both axes

---

#### Q5(b): Gestalt theory application:
Using proximity to group related bars together can draw attention to specific programming languages' popularity trends. Yes, this leverages pre-attentive processing as grouping is immediately noticeable.

---

#### Q5(c): Searchlight model explanation:
The searchlight model describes how visual attention focuses on specific areas of interest while ignoring others temporarily. Designers can use this by strategically placing highlights or contrasting elements to guide viewers’ focus.

---

#### Q5(d): Graph examples:
(i) Categorical visualization – Bar chart showing programming language preferences by percentage.
(ii) Relational visualization – Scatter plot showing correlation between study hours and exam scores.

Figure 1
![image](https://github.com/user-attachments/assets/4ba952ae-588a-47c5-a2c6-9ed47e156d10)

Figure 2 
![image](https://github.com/user-attachments/assets/d93269cb-e972-4f68-8028-78db5fb16f49)

Figure 3
Python 15%
C/C++ 30%
Java 20%
PHP 5%
JavaScript 5%
Pascal 10%
Fortran 10%
Other 5%
First programming language of conference attendees (audience survey


