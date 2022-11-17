# kafka-docker-setup
Setup Kafka(Zookeeper/Broker/Kafka-Manager) on a local machine or an EC2

#### Before you run docker-compose, change the IP address to your machine address in the kafka-docker-compose-setup.yaml file
substitute {add-your-IP-address-here} with your IP address in the kafka-docker-compose-setup.yaml file

#### Fire the below command to host a single broker Kafka on your local or Ec2
docker-compose -f kafka-docker-compose-setup.yaml up -d 
