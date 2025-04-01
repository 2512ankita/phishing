# phishing
Phishing Website Detection Using Machine Learning
**Overview**
This Jupyter Notebook focuses on feature extraction for detecting phishing websites. It analyzes a dataset containing various features extracted from URLs to distinguish between legitimate and phishing websites. The project includes data exploration, visualization, and preliminary analysis to identify key characteristics that differentiate phishing websites from legitimate ones.

**Dataset**
The dataset used in this notebook is named 5.urldata.csv and contains the following features:

**Domain: The website domain.**

Have_IP: Indicates if the URL has an IP address (binary).

Have_At: Indicates if the URL contains '@' symbol (binary).

URL_Length: Length of the URL.

URL_Depth: Depth of the URL structure.

Redirection: Presence of redirection (binary).

https_Domain: Use of HTTPS in the domain (binary).

TinyURL: Use of URL shortening (binary).

Prefix/Suffix: Presence of prefix or suffix in the domain (binary).

DNS_Record: DNS record availability (binary).

Web_Traffic: Web traffic rank (binary).

Domain_Age: Age of the domain (binary).

Domain_End: Domain expiration status (binary).

iFrame: Use of iFrame (binary).

Mouse_Over: Mouse-over effects (binary).

Right_Click: Right-click functionality (binary).

Web_Forwards: Use of web forwarding (binary).

Label: Binary label indicating phishing (1) or legitimate (0).

**Features**
The notebook performs the following tasks:

Data Loading: Imports necessary libraries and loads the dataset.

Data Exploration: Examines the dataset's shape, columns, and basic information.

Visualization: Uses seaborn and matplotlib to visualize data distributions and relationships.

Feature Analysis: Investigates the correlation between features and the target variable (Label).

**Requirements**
To run this notebook, you need the following Python libraries:

pandas

numpy

seaborn

matplotlib

**Usage**
Clone the repository or download the notebook.

Ensure the dataset 5.urldata.csv is in the same directory as the notebook.

Run the notebook cells sequentially to perform the analysis.

**Results**
The notebook provides insights into the features that are most indicative of phishing websites. These insights can be used to build machine learning models for phishing detection.
