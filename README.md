# RadarTraffic
II. Introduction
Government agencies and major companies in the transportation industry gather and analyze traffic data for several business, infrastructure, and safety reasons.

Traffic flow management requires data mining focused on efficient traffic distribution, road maintenance scheduling, and other research driven analysis such as smart roads construction.

Using sophisticated cameras and radar units mounted on major intersections and on side of freeways, data is collected, stored, and analyzed. Using this data gathered on daily basis, major traffic attributes such as traffic volume, speed, and vehicles classification are obtained using historical or real time data.

Most of traffic flow attributes such as speed depends on wide range of factors including road conditions, pending major events on the surrounding area, accidents and time of the day. 

Our project uses an existing government traffic data that is available for public, and analyzes this data to provide a useful insight focused on the three traffic flow attributes described above. 

We will be using pySpark libraries along with panda data frame APIs and other python libraries to process our data. In addition, most of our data analysis functionalizes will be implemented using key concepts we are converging throughout our course such as python list, tuples, dictionary, and file. 

II. Design
Use Case: Traffic Flow Analysis:
Scope: System.
Level: User Goal
Primary Actor: Data Analysis Engineer
Pre-conditions: Traffic data is collected is retrieved from device and stored in csv format.
Post-conditions: Analysis visualization plots providing insights on traffic condition are provided.

Main Success Scenario:
1. Collection data is verified using data size and format verification methods.
2. Data is ready to be processed.
3. Data is imported to data frames.
4. Data attributes are verified on the data frame against the expected format.
5. Data is sorted, filtered, and processed for each of the traffic attributes.
6. Result is provided using multiple python plots showing trends of traffic flow including useful data comparison.
II. Code
Our data processing and analysis code will be developed from a scratch using pySpark data frame libraries using PyCharm. It will include four modules. 
Module 1: The first module will be an interface to the user specifying the different options on traffic data analysis. 
