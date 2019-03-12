# puppeteer-slack

* <https://github.com/GoogleChrome/puppeteer>

## Prepare

* Slack App
  * <https://my.slack.com/services/new/bot>

## Uasge

```
$ docker run --rm \
    -e SLACK_BOT_TOKEN=xxxx-0000-0000-xxxx \
    -e CHANNEL=sandbox \
    -e TARGET_URL=https://opspresso.com/ \
    -e WIDTH=800 \
    -e HEIGHT=600 \
    quay.io/opspresso/puppeteer-slack
```

## Params
