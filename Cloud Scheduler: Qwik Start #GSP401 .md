# GSP401
### Run in CloudShell
```cmd
gcloud services enable cloudscheduler.googleapis.com
gcloud pubsub topics create cron-topic
gcloud pubsub subscriptions create cron-sub --topic cron-topic
```
