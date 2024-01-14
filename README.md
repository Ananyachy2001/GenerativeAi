## setup and instructions
1. At first I have built a laravel project with the composer package command


2.Then after making the project I have made a chatcontroller "php artisan make:controller ChatController" by this command.

3.Then I have created two view folders which is layouts and ChatGpt. In the layout folder it contains the head portion of the HTML.

4.After that I have created the fontend of the chat box for generative answers with the help of bootstrap.

5. As I had to work with the OpenAI api so at first I had to login to OpenAI. 

6. After logging in I have to greate a generative api key from which I can get the datas using it.

7. After copying the api key I have declared a variable in the env file which is called "OPENAI_API_KEY"

8.then i have created a openai.php file to call the api key for reference.

9.Then in the controller I have created 3 fuctions which are index, ask and asktoChatGPT. in these functions the main backend logics handled and with the help of OpenAi documentations I was able to fetch the data from api.

10. To go from one page to another or to refresh I haves used routes in the web.php from where I was able to get and post the data.

11.there are many roles in these api but i have used the base user role and also I haved used the max_tokens so that the api can't generate crazy numbers of answers.

12. Then I have created two templates for the user and chatbot messeage from where I was able to show the new generated on the same page by using the generateChatBoxMessage function.

13. Finally I have created a Chatbot which can help people with their work.
