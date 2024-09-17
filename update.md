# change log
1. More functions of zhipu ai. For docs editor, there are 10 functions to help you edit the docs. 
For spreadsheet editor, there are 6 functions to help you edit the spreadsheet. 
For presentation editor, there are 5 functions to help you edit the presentation.
2. Improved prompts of request. Better prompt words help ai models better understand questions and answer them.
3. New version zhipu ai interface.
4. Refer to the ChatGPT plugin project, I add the custom request function and Internet Explorer processing logic.
5. New UI design of chat interface.

# File Introduction
index.html: The main page of the plugin, which is the entry point of the plugin.

index_setting: The settings page of the plugin, which is used to set the API key.

custom_req_window.html: The custom request window of the plugin, which is used to send a custom request to the server. Referring to the ChatGPT plugin project, I make some changes based on the source file.

ie_message.html: The IE browser displays an error message by referring to the ChatGPT plugin.

styles/style.css: The style file of the plugin, which is used to set the style of the plugin.

styles/custom.css: The style file of the custom request window, referring to the ChatGPT plugin project.

scripts/main.js: The main script file of the plugin, which is used to control the main page(chat page) of the plugin.

scripts/prompt.js: The prompts of requests.

scripts/zhipu_ai.js: The simple sdk of zhipu AI.

scripts/jwt.js: jwt util, same as original.

scripts/custom.js: The script file of the custom request window, referring to the ChatGPT plugin project.

scripts/ie_message.js: The script file of the IE browser error message, referring to the ChatGPT plugin project.

scripts/code_ie.js: The script file of the IE browser error message, referring to the ChatGPT plugin project.

# How to use
1. Find the Zhipu AI plugin.
2. Set the API key.
3. Click the "Start" button to chat with the Zhipu AI or click the "Custom Request" button to send a custom request to the server.
4. Select the right content and right-click evoke menu to use the zhipu ai function.
