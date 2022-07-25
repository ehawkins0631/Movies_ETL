Movies_ETL

Extract, Transform, Load

Purpose
* Create an ETL pipeline from raw data to a SQL database.
* Extract data from disparate sources using Python.
* Clean and transform data using Pandas.
* Use regular expressions (Regex) to parse data and to transform text into numbers.
* Load data with PostgreSQL and verify in PgAdmin.

The project included extracting a large data set from Kaggle, then transforming the data into a usable dataset for a "hacking competition." Once the data was transformed and narrowed in scope for the hackathon, the DataFrames were loaded into PostgresSQL.

Extracting, Transforming and Loading:

![image](https://user-images.githubusercontent.com/101227930/180764573-83add107-a8af-4b76-a34c-d81c0d957732.png)




![image](https://user-images.githubusercontent.com/101227930/180764616-36f29b9a-a37e-4570-8a21-a448904a37cd.png)



![image](https://user-images.githubusercontent.com/101227930/180764880-49908fd4-c55f-4705-8f47-416cc272e9e0.png)

Verifying the data in PgAdmin


Movies Query

![image](https://user-images.githubusercontent.com/101227930/180764968-d380972d-e886-4855-bdd0-17554f651643.png)

Ratings Query

![image](https://user-images.githubusercontent.com/101227930/180765943-c22fecad-149b-4f8a-8c4e-d160d1c6f8dd.png)




Summary
A JSON file and 2 Kaggle files were extracted, then transformed, and joined. A movies and ratings file were loaded into a database for the hackathon event.
