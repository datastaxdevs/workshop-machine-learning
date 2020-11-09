# Machine Learning with Apache Spark & Cassandra
## Cassandra + Spark = ❤️ 

A Hands-on Lab delivered by DataStax' Developer Advocates team. Want to learn the awesomness of distributed databases and computational systems? Jump in, watch the slides and do the practicals steps!

## Slides

* [CodeLabs Cassandra+Spark](./slides/CodeLabs_Cassandra.pdf)
* [Introduction to Machine Learning with Apache Cassandra and Apache Spark](./slides/Intro%20to%20ML%20with%20C_%20and%20Spark.pdf)

## Labs

### Reqs

- git
- docker
- docker-compose

### Installation

```
git clone https://github.com/DataStax-Academy/machine-learning-workshop-online.git
cd machine-learning-workshop-online
docker-compose up -d
```

### Usage

- For the Cassandra labs, access DataStaxs Studio: http://localhost:9091
- For the Spark labs, access Jupyter Notebooks:   http://localhost:8888 password: `datastax`

You may need to use some custom IP instead of localhost if you use docker-for-mac, docker-for-windows or similar installation.

### Known Issues

In some cases executing the exercises may lead to memory issues, especially on weaker or non-Linux machines due to docker limitations on memory. If you have any issues with exercises after the first few, try to clean up and start again `docker-compose kill && docker-compose down && docker-compose up -d`. You may need to repeat steps of the notebook you were working on.
