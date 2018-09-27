# Dockerized and Slack-integrated Hubot

Setup a hubot from https://slack.com/services/new/hubot and assign the API token to the following command

```
docker pull chihchun/hubot-slack
docker run -e HUBOT_SLACK_TOKEN=xoxb-1234567890-XXXXXXXXXXXXXXXXXXXXXXXX -d chihchun/hubot-slack
```

# Hubot Scripts
* hubot-diagnostics
* hubot-help
* hubot-heroku-keepalive
* hubot-google-images
* hubot-google-translate
* hubot-pugme
* hubot-maps
* hubot-redis-brain
* hubot-rules
* hubot-shipit
* hubot-moretext
* hubot-standup-alarm
* hubot-victory

## Reference
* Bot Users | Slack https://api.slack.com/bot-users
