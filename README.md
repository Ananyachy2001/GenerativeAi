## #setup and instructions
1. At first I built a laravel project with the composer package command


2. Then after making the project I made a chatcontroller "php artisan make: controller ChatController" by this command.

3. Then I created two view folders which are layouts and ChatGpt. The layout folder contains the head portion of the HTML.

4. After that, I created the front-end of the chat box for generative answers with the help of Bootstrap.

5. As I had to work with the OpenAI API so at first I had to log in to OpenAI. 

6. After logging in I have to create a generative API key from which I can get the data using it.

7. After copying the API key I have declared a variable in the env file which is called "OPENAI_API_KEY"

8. Later, I created an openai.php file to call the API key for reference.

9. In the controller file I have created 3 functions which are index, ask, and asktoChatGPT. in these functions the main backend logic is handled and with the help of OpenAi documentation, I was able to fetch the data from API.

10. To go from one page to another or to refresh I have used routes in the web.php from where I was able to get and post the data.

11. There are many roles in these APIs but I have used the base user role and also I have used the max_tokens so that the API can't generate crazy numbers of answers.

12. Then I created two templates for the user and chatbot message from where I was able to show the new generated on the same page by using the generateChatBoxMessage function.

13. Finally I have created a Chatbot which can help people with their work.
