# springboot-chatgpt

1. First, login to chatgpt

2. go to https://platform.openai.com/account/api-keys to generate an API key, which will be used for authentication purpose. Note: the token will only be visible once, so make sure to store it at some place

3. Also, navigate to https://platform.openai.com/playground to understand the chatgpt request response structure better

4. download and import the code as existing maven application

5. under resources folder, application.properties file - provide your api key against "openai.api.key"

6. run the application as spring boot app

7. open postman and provide url: localhost:8080/bot/chat

8. authentication bearer token and provide your API key

9. under parameter, pass prompt as a key and any question you want to ask as value

10. hit the API. It will take few seconds and it will return you the result

11. ask some specific questions related to code examples and it will give you all

# Note: You can create an OpenAI API key for free. All new trial users usually get $5 worth of credit after signing up. However, this credit expires after three months.

_*_*_*_*_*_*_*_*__**__*_*_*_*_*_*__*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*

# Happy coding

