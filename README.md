Here,
docker-compose.yml has the image with ksqlDB,
docker-compose1.yaml has without ksqlDB,
docker-compose2.yaml has with zookepper without ksqlDB.
docker-compose3.yaml has no kraftID and has a zookeeper with three brokers as kafka-1,2,3.


kafka cluster ids:

MkU3OEVBNTcwNTJENDM2Qk  &  i_sU4uZNRKSxvd76LWN5Qw    b21MJrp3TleIUI6vfc1HkA
go to broker in shell and do     cd /usr/bin       and do      kafka-storage random-uuid
it creates new cluster id and can use it again to craete a new cluster.

This kafka in Docker setup is for free.


![image](../images/confluent-logo-300-2.png)
  
# Documentation

You can find the documentation and instructions for this repo at [https://docs.confluent.io/platform/current/tutorials/build-your-own-demos.html](https://docs.confluent.io/platform/current/tutorials/build-your-own-demos.html?utm_source=github&utm_medium=demo&utm_campaign=ch.examples_type.community_content.cp-all-in-one)
