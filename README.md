# [HTTP API video editor](https://github.com/superdesk/video-server) application instance 


## Requirements

These services must be installed, configured and running:

 * Python (>= 3.6)
 * FFmpeg
 * MongoDB 
 * RabbitMQ (celery backend)
 
 
 ## Installation steps:
```
git clone https://github.com/superdesk/video-server-app.git
cd video-server-app/
pip install -r requirements.txt
honcho start
```
 
 :exclamation:  
 Using Gunicorn is not required, you can use any WSGI HTTP Server.  
 Using Honcho is not required, you can run processes listed in `Procfile` with another tool (e.g. Supervisor).