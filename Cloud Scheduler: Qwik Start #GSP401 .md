

# GSP401
[![](https://api.pointscounter.me/servers/img/subscribe)](https://www.youtube.com/@CloudHustlers)
### Run in CloudShell
```cmd
gcloud services enable cloudscheduler.googleapis.com
gcloud pubsub topics create cron-topic
gcloud pubsub subscriptions create cron-sub --topic cron-topic
```
