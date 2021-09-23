# RASA Chatbot

## Chat with the Bot

Make sure you installed all requirements and your grakn server is running.

If you want to chat with the bot, execute the following steps:
1. Train the bot using `rasa train`.
2. Start the action server with `rasa run actions` in a separate terminal.
3. Chat with the bot on the command line by executing `rasa shell`.

If you want to see what slots are set and how confident the bot is in predicting the next action, you should run 
the bot in debug mode: `rasa shell --debug`.

Here are some example questions you can ask the bot:
- “Quero dicas de cafeterias”
- “Quais as cafeterias no Centro?”
- “Me fale mais sobre a Prestinaria” 
- “Qual o endereço da Bocca Lupo?” 
- “Qual o horario da Rause Café?”
