# Music App Events (Udacity Data Engineering Nanodegree Project `Data Modeling with Apache Casandra`)

## Description of this project
Load song play data from CSV files and save them to Apache Cassandra database.

## ETL process
ETL consists from three processes.

- make one CSV file from many CSV files that was recorded song play history of music app
- load and save data to database
- analyze history data by three way

## How to set up

```shell
# pull docker images (if not exists on local machine) and run necessary process
docker-compose up --build -d
# set up jupyter to enable to use cassadra
docker-compose exec notebook pip install -r requirements.txt
# then, open jupyter notebook
open http://localhost:8888
```
