How to run Elastic APM for the first time:

I will be using Docker Desktop (I know - lame)

1. Run `docker compose up`
2. Check if Kibana/Elastic are up
   1. Go to Elastic http://localhost:5601/
   2. Login: `elastic`
   3. Password: `admin`
   4. If UI is there - all is ready
3. Start APM server image in docker
4. Enable APM server in Kibana
   1. Go to APM
   2. Check if APM server is there
   3. Add Kibana objects
5. You are ready to go!

<img src="2022-11-08 16.53.32.gif" width="800"/>

