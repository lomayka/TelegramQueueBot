# Queue_bot for Telegram

This Telegram bot provides a queue service for large groups to form an online queue. It could be convinient for anybody, who would like to form, administrate and use online queues without any additional software.

To use this bot you must register it with @bot_father and insert the token into the bot.js file, on the token field. Now you can start it in any convinient way (npm or yarn) and use it.

Main commands for the bot:

<code>/start@Queue_bot</code>

allows the administrator of the group to connect queue_bot to chat.

<code>/openQueue:"queue name"</code>

Opens the queue of the chosen name 

<code>/enqueue:"queue name"</code>

Adds the person, who sent the message to the queue

<code>/dequeue:"queue name"</code>

Deletes the person from queue

<code>/close:"queue name"</code>

closes the queue

<code>/stop</code>

deletes the bot from chats


