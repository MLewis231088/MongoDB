# MongoDB

# Private Functions Analysis
This repository contains a MongoDB project focused on analyzing private functions and their characteristics. The dataset provides information about various private functions, including details such as function type, food choices, number of guests, duration, disc jockey details, and venue information.

The project aims to provide insights into private functions, enabling event planners and managers to enhance the quality of their services and meet customers' needs more effectively.

Contents
1. Introduction
2. Background to the Dataset
3. Understanding Embedded Documents in MongoDB
4. Generating Data Using Mockaroo
5. Installing Mongo Shell on MacBook Pro M1
    Installing Xcode Command-Line Tools
    Installing Homebrew
    Installing MongoDB Community Edition on MacOS Using Shell
    Running MongoDB Community Edition on MacOS Using Shell
    Connecting and Using MongoDB on MacOS
6. Loading and Executing JavaScript Files in Mongosh
    Creating a new database using Mongosh
    Viewing the database in Mongosh
    Loading the JavaScript files in Mongosh
    Executing the JavaScript files in Mongosh
7. Using the count() function
8. Using the find() and pretty() functions
9. Getting Started with MongoDB Simple Queries
    Query 1: $ne, $not, $in, $gt
    Query 2: $and, $lte, $not
    Query 3: $elemMatch, $or, $gte, $ne, $exists
    Query 4: $gte, $in, $lt
    Query 5: $regex, $and
    Query 6: $strLenCP, $and, $expr, $gte, $eq, $mod
    Query 7: $mod, $all, $in, $ne
    Query 8: $where, $and, $regex, $exists, $gt
    Query 9: $setIntersection, $and, $expr, $gt, $size, $ne, $where
    Query 10: $gt, $expr, $gte, $add, $size, $ne
    Query 11: $lte, $expr, $abs, $subtract, $in, $gte
    Query 12: $expr, $strLenCP, $gt, $gte
    Query 13: $or, $gt, $options, $in, $lt
    Query 14: $divide, $and, $expr, $gte, $in
    Query 15: $multiply, $size, $lte, $gte, $expr, $and
    Query 16: $size, $mod, $and, $gt, $expr, $strLenCP
    Query 17: $options, $size, $divide, $all, $not, $regex, $mod, $strLenCP, $expr, $and, $gt
    Query 18: $divide, $size, $expr, $and, $gte, $lte
    Query 19: $all, $strLenCP, $expr, $and, $lt, $in
    Query 20: $nin, $divide, $gte, $expr, $and, $gt
    Query 21: $regex, $and, $nin, $gte
    Query 22: $or, $all, $expr, $lt, $strLenCP
    Query 23: $size, $ne, $not, $multiply, $in, $and, $expr, $gt
    Query 24: $elemMatch $or, $and, $lte, $nin, $in, $gt, $eq, $not
    Query 25: $exists, $regex, $and, $eq, $ne, $gt, $nin, $expr
    Query 26: insertOne(), deleteOne()
    Query 27: insertMany(), deleteMany()
10.Using Advanced Aggregate Function in MongoDB
    Aggregate Query 1: Find the maximum number of guests for each year
    Aggregate Query 2: Find the total number of guests and the average duration of each function type held in the city of Mountrath
    Aggregate Query 3: Find the average fee for each disc jockey who performed at Athlone and have a fee less than 500 euros, sorted in ascending order
    Aggregate Query 4: Find the number of functions held in each venue type, sorted in descending order
    Aggregate Query 5: Find the total count of events held in each city where the venue was Park, and only include cities where more than 1 event has been held
    Aggregate Query 6: Find the average fee for a disc jockey, grouped by the day of the week they are available on
    Aggregate Query 7: Find venues with good acoustics and a capacity greater than or equal to 400, sorted in ascending order of capacity
    Aggregate Query 8: What are the top three most popular types of events held each year, based on the average number of guests and duration, as well as the unique food and alcohol choices served at each event?
    Aggregate Query 9: What is the breakdown of event statistics for each city in the database, including the total number of events, the average and maximum number of guests, average fee for disc jockeys, and top three food choices for events in each city?
    Aggregate Query 10: What are the top 10 food choices for weddings with at least 300 guests, and how many times was each food choice served, and what is the average number of guests for each choice?
    Aggregate Query 11: What are the various statistics and characteristics of events held in 2022?
    Aggregate Query 12: What are the venues with good acoustics that have hosted at least 50 events, and what are the average number of guests and acoustic ratings for each city in which they are located? Also, how much alcohol and soft drinks have been served at these events in each city?
11. MongoDB Compass Interface
    Connecting to a localhost MongoDB deployment
    Creating a database in MongoDB Compass using a JSON file
    Running a basic query using Mongosh in Compass
    Running an aggregate query in MongoDB Compass
12. Stages in Aggregations: A Detailed Explanation of Each Stage in MongoDB Compass
    Query 1: Stage 1: $match, Stage 2: $group, Stage 3: $sort
    Query 2: Stage 1: $match, Stage 2: $group, Stage 3: $match, Stage 4: $lookup, Stage 5: $project, Stage 6: $sort
13. YouTube Link
14. References

This repository provides comprehensive instructions on setting up MongoDB, loading data, executing basic and advanced queries, and utilizing MongoDB Compass for visualization. The aggregate queries cover a wide range of scenarios, providing insights into private function analysis.

For detailed information and examples, please refer to the respective sections within the repository.

Note: This repository assumes basic knowledge of MongoDB and its query syntax. It is recommended to have MongoDB installed and running before proceeding with the provided instructions.
