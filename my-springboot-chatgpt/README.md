# Integration of chatGPT with springboot

- After login into your own chatGPT account, generate your chatGPT api-key like this which will work as auth token.
![](https://github.com/AadityaUoHyd/chatGPT_springboot_integration/blob/master/API%20keys.jpg)

- First, we will access it through normal POST, where only we have to provide url and api-key of chatGPT at auth token.
And when you send the request with proper JSON format(which will carry our question) via POSTMAN, we'll receive response (our answer for the query) from chatGPT.
![](https://github.com/AadityaUoHyd/chatGPT_springboot_integration/blob/master/PostReq.jpg)


- Second, we will integrate chatGPT gpt-3.5-turbo model with springboot code. Now, with GET request we will send query as QUERYPARAM using api-key of chatGPT as auth token.
say, "http://localhost:8080/bot/chat?prompt=What is spring batch" as url, and in response we'll receive appropriate answer of the query from chatGPT.
![](https://github.com/AadityaUoHyd/chatGPT_springboot_integration/blob/master/GetReq.jpg)

Sources from where I learnt : <br>
https://platform.openai.com/docs/introduction/overview <br>
https://www.baeldung.com/spring-boot-chatgpt-api-openai 
