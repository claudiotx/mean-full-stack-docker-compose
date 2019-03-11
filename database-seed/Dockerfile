FROM mongo:3.6.11

COPY data.json /data.json
CMD mongoimport --host mongo-db --db sample --collection data --type json --file /data.json --jsonArray
