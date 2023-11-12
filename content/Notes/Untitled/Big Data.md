Save
Store
Process
Analyze 

V-> Velocity, Variety,

Managing data and process it to be analyzing it

Client and Server Architecture 

Applications -- Google, Wikipedia, Maps , Gmail   >> WebApps


Diff Between Bigdata and WebData

**Big Data:**

- **Definition:** Refers to extremely large and complex datasets.
- **Size:** Involves massive volumes of data.
- **Characteristics:** Characterized by the three Vs: Volume, Velocity, Variety.
- **Data Types:** Includes structured, semi-structured, and unstructured data.
- **Purpose:** Used for various purposes, including analytics, machine learning, and business intelligence.
- **Tools:** Requires big data processing and analytics tools.
- **Source:** Data can come from various sources, not limited to the web.

**Web Data:**

- **Definition:** Data extracted from websites.
- **Size:** Data from specific web sources.
- **Characteristics:** Can be structured or unstructured.
- **Data Types:** Often unstructured (text, images, etc.).
- **Purpose:** Used for tasks like web scraping, content aggregation, and price monitoring.
- **Tools:** Relies on web scrapers and web crawlers.
- **Source:** Specifically collected from websites and web pages on the internet.


Big Data- High Volume ,velocity, variety ,varacity, large datasets

Information that requires the new forms of processing for enhanced decision making and insight discovery and process optimizations , it is a collection of large and complex datasets that the traditional data

Structures, semisctructed , un structured data --- Multi structured data


Bigdata Analytics
	Definition
	Importance -- Collection , Storage, Processing, Analysis
	Types of data -- Multimedia ,excel ,email, chats, social media
	Classification of data
	Application of Big Data

Hadoop
	Storage -- HDFS
	Processing -- Map Reduce
	Analysis -- YARN

2 Nodes --  Master node (name node) --> Slave Node (Data Node)
	Master
		- the Master Node manages the file system and the name space and gives a regulatory acess to the files by the clients, 
		- files system operation such as - opening ,closing ,renaming ,managing directories
		- Also determines the mapping of blocks to the data nodes and handles the data node failures
		- Block creation, deletion, modification ,replication
	Slaves
		- Serving the read and write requests form the file system to the clients
		

The Entire data is divided into Blocks -- done by node manager to resource manager

Resource Manager -> Node Manager -> Application Master -> Container

Resource Manager  
	- identifies request from node manager and allocated the resources
	- Acts as a  control Center
[text, image,mp4,mp3] --> [text]  [Image]  [mp4]  [mp3]
if data exceeds blocks, it ask the resource manager to allocate more data

Centralized Computing vs Distributed Computing


