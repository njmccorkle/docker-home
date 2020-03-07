See here:
https://docs.influxdata.com/influxdb/v1.7/administration/authentication_and_authorization/#user-management-commands

Create user
CREATE USER admin WITH PASSWORD 'admin' WITH ALL PRIVILEGES;
CREATE USER homeassistant WITH PASSWORD 'homeassistant'

GRANT READ ON homeassistant TO homeassistant;
GRANT WRITE ON homeassistant TO homeassistant;
