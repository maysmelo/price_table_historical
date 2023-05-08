# Price Table Historical

This project was created to replicate one of the projects I've worked at but using fake customer information. 

The idea is to historize the monthly price the customers owned this ficticious company over time, knowing that they can switch prices multiple times during their contracts. 

I'm using Python to:
- include the CSV file with the price switches;
- generate a dataframe with all the dates from the first contract date until current date;
- use pysqldf to join the two different dataframes and explore the data;
- export the output on CSV file;
- visualize and come up with insights about the data.


Plotlib graph:
>![2023-05-08 15 21 47](https://user-images.githubusercontent.com/124809927/236835441-9ccc08d1-388a-42ce-bf09-6c9043029517.gif)