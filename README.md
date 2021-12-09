## Overview
This is the lambda that fulfills Lex and Alexa requests. 

## Integration Testing

```
sam local invoke "QnABotFulfillmentLambdaJMeqq75oakh2" -e ./events/events.json --profile 111365482541_shcva-Developer --region us-west-2 | jq '.dialogAction.message.content'
```

## Tests
test are run using:
```shell
npm test
```

or
```shell
npm unit {{test-name}}
```

