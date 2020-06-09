# Database

## What is it?
The database- is repositories to:
- learn how to installation DB Postgresql + Jupyter Notebook using Docker.
- how to ingest csv file to DB.
- how to build a query from python in Jupyter notebook.
- and making a simple visualization using Plotly.

## How did it work?


- first 
    - run file docker-compose.yml : docker-compose -f Database-/docker-compose.yml up -d
- second
    - check container : docker container ls --all
- third
    - check the logs Jupyter if the container ready, to get the token access : docker log 'container name'
- fourth
    - if you can open the jupyter worksheet, run the script 'Ingest csv to db.pynb'
- fifth
    -  run your complex query to doing aggregation data

