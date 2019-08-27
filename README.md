# Challenges


# Email

### Scenario: User sends a message to a Message Server. 

```gherkin 
Given A User sends an "hello" message 
When The message is converted by the Adapter
Then The Message server should contain the "hello" message in the queue
```  
