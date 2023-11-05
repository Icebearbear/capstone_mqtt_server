# capstone_mqtt_server

go to root 
su root

run mosquitto broker
mosquitto -v

run subscriber
mosquitto_sub -h localhost -t /home/test

run publisher
mosquitto_pub -h localhost -t /home/test -m HELLOSUP


