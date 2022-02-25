# Movies-ETL

## Purpose
The purpose of this analysis was to create a pipeline that takes in data, transforms the data, and loads the data into existing tables. This analysis was completed using refactored code. We began by writing a function to include data from three separate data sources:

<img width="871" alt="Screen Shot 2022-02-25 at 1 15 51 PM" src="https://user-images.githubusercontent.com/95551195/155793655-830dd24b-e03c-4387-bb76-8c2e77f1ec33.png">


We were successfully able to extract and transform data from a Wikipedia & Kaggle data source:

<img width="1079" alt="Screen Shot 2022-02-21 at 12 05 02 PM" src="https://user-images.githubusercontent.com/95551195/155013679-6907f289-f061-4948-a1e0-6a709c655366.png">

<img width="1059" alt="Screen Shot 2022-02-21 at 12 05 14 PM" src="https://user-images.githubusercontent.com/95551195/155013699-49426336-463c-4e04-ab19-884e82113957.png">

<img width="1056" alt="Screen Shot 2022-02-21 at 12 05 40 PM" src="https://user-images.githubusercontent.com/95551195/155013754-30fca469-2764-4849-a610-b3fda739827b.png">


We then read that data into a Postgres SQL databse for future use:

<img width="98" alt="movies_query" src="https://user-images.githubusercontent.com/95551195/155793790-9d2fa288-1e3d-4605-840c-d39530fbca64.png">

<img width="149" alt="ratings_query" src="https://user-images.githubusercontent.com/95551195/155013455-f6e76d71-1528-4a83-8a06-863e3a78493c.png">

The ETL process allows us to clean and compile data into a usable form. With continued practice and use, ETL will continue to serve meaningful and crucial transformation of the data process.
