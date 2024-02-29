**Sales Analysis**
1.	Imported os and pandas
   
    a.	os module for combining multiple files
  	
    b.	pandas module for reading and merging data from all month
  	
3.	Read the csv file
   
5.	Clean-up the data
   
    a.	Remove unwanted data from the data frame like NaN data
  	
    b.	Remove entries which are not having order dates
  	
    c.	Convert columns to required type. Like “Quantity Ordered” or “Price Each” are of str type. Convert them to int type.
  	
6.	Augmentation of dada by adding columns
   
    a.	Month column will be further needed for finding month wise sales
  	
    b.	City column will be further needed for finding  city wise sales
  	
8.	Reset the index
   
    a.	For avoiding errors occurring due to missing indexes after removal of NaN data.
  	
    6.	Data Exploration
       
10.	Create the Sales column
    
    a.	For finding the month wise total sales
   	
11.	Imported matplotlib
    
    a.	For plotting month vs sales graph
   	
    b.	For plotting city vs sales graph.
   	
12.	Create Hour column
    
    a.	To find right time for advertising by plotting hour vs quantity ordered
   	
13.	Create new data frame of duplicated order id
    
    a.	For finding products that are sold together.
