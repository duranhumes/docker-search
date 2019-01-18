# Docker ELK stack for search you know.

### Installation and use 
`rename .env.example to .env`
change .env file as your need 
`docker-compose up -d`

---

Logstash will go by the schedule and fetch the data accordingly.


---

You'll have to make sure that the `elasticsearch/data` directory is owned by elasticsearch `1100:1100` otherwise elasticsearch will crash.



