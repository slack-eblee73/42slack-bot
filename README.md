# Slack bot
* https://okdevtv.slack.com test bed

## 환경 설정하기
* Set up 5 values
  * https://okdevtv.com/mib/slack

## 빌드
```sh
git clone https://github.com/innovationacademy-kr/42slack-bot
cd 42slack-bot
npm i
cp .env.sample .env
# set up .env values
open http://localhost:4002
npm start
```

```sh
curl -X POST localhost:4002/marvin -H 'Content-Type: application/json' -d '{"text": "lotto"}'
```

## ref
* https://okdevtv.com/mib/slack
