# NO_SQL_ANALYSIS
Flight Delay DataLab (MongoDB Project)
Airline_Delays is a data analysis project focused on studying the causes of flight delays in airports across the United States using NoSQL database technology. The project uses a large dataset containing monthly information about airlines, airports, and different types of delay factors such as weather conditions, airline operational issues, security incidents, problems within the National Aviation System (NAS), and late aircraft arrivals.

The dataset, obtained from Kaggle, includes multiple attributes such as the number of arriving flights, delayed flights, total delay minutes, and the minutes associated with each specific delay cause. By leveraging MongoDB as the NoSQL database and Python libraries such as PyMongo and Pandas, the project demonstrates how large volumes of semi-structured data can be efficiently stored, processed, and analyzed.

The analysis workflow includes several key database operations: data importation from CSV files, document insertion into MongoDB collections, filtering and projection queries to retrieve specific information, updates to enrich documents with new calculated fields, and aggregation pipelines to perform statistical analysis. Through these operations, the project identifies patterns in flight delays, highlights the most common delay causes, and determines which airports accumulate the highest average and total delay times.

The results reveal that major hub airports with high traffic volumes tend to experience greater delays due to operational complexity and congestion. Overall, the project demonstrates the effectiveness of NoSQL technologies for handling large-scale datasets and performing flexible analytical queries in real-world domains such as the aviation industry.
