# Challenges

In order to complete the challenges ahead, you need to previously install the [Flow](https://github.com/rafaelspinto/flow) Framework. To do that, please run the following commands in the command line:


```shell
git clone https://github.com/rafaelspinto/flow
cd flow
mvn install
```


# 1. Email Test

### Scenario: User sends a message to a Message Server.

Implement code in so that the following Acceptance Criteria is met:

```gherkin
Given A User sends an "hello" message
When The message is converted by the Adapter
Then The Message server should contain the "hello" message in the queue
```
