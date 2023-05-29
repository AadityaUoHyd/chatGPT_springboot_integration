# Integration of chatGPT with springboot

- First, we will access it through normal POST, where only we have to provide url and api-key of chatGPT at auth token.
And when you send the request with proper JSON format(which will carry our question) via POSTMAN, we'll receive response (our answer for the query) from chatGPT.



- Second, we will integrate chatGPT gpt-3.5-turbo model with springboot code. Now, with GET request we will send query as QUERYPARAM using api-key of chatGPT as auth token.
say, "http://localhost:8080/bot/chat?prompt=What is spring batch" as url, and in response we'll receive appropriate answer of the query from chatGPT.

