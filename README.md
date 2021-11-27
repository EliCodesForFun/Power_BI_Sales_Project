# Power_BI_Sales_Project
Power BI Sales Project - Using Randomly Generated Product Names


This Project is meant as a tutorial/walkthrough for people looking to analyze Sales Data.
In the folder, we will have the project already made, but I will loosely explain how to recreate it from scratch.

Step 1. Import Data
Select the sheets from the Excel xlsx file that have our data. Make sure to grab the Sales tabs for 2018, 2019, and 2020.
Click "Transform Data here"
We can rename the data sheets from "Product Data" to simply "Products" and follow this format for all of our tabs.

Step 2. Power Query
In Power Query we're going to Append the different Sales tabs (2018, 2019, and 2020) together into one database.
![image](https://user-images.githubusercontent.com/9376306/143663355-42ceb117-9bc4-49ee-b40f-1f57ded990c2.png)

Click "Append as New" and drop the 3 tables together. Let's call it "Sales".

Step 3. Import a Dates table.
One thing that's a great resource to have with Power BI is your own Dates table. My system is partly in Japanese so I'll share the Query you can import in the file. We use this Dates Table to apply filters, create slicers and timelines in our project. 
Set the Date Range from January 1st, 2018 to December 31s, 2020.
You simply hit New>Blank Query> Paste the query in and fill out the date range, and it will generate this.

![image](https://user-images.githubusercontent.com/9376306/143663451-8d2c619a-e917-4b54-85ab-9d1e42dff65c.png)


Step 4. Setting up our Measures
Measures in Power BI are ways to do advanced calculations in a simple way, where it will adjust automatically with how we filter the data.
The first filter you'll need is for the Total Costs.
...
...


Step 5. Making some visualizations.
Here's an example of a Visualization you can make.
Add a Stacked Bar Chart.
Drag the Customer Name and the [Total Values] Measure onto the graph.

![image](https://user-images.githubusercontent.com/9376306/143663795-5c2cf0e2-daaa-4f50-9b83-2524b9156dda.png)
You can click to the formatting tab and add Data labels for clarity.

![image](https://user-images.githubusercontent.com/9376306/143663816-e0dd23fa-67da-4c16-9966-428b1ff65b94.png)


