Session presented at Global Azure Bootcamp Building a Conversational Bot using Bot Framework and Microsoft Azure 

During this session we presented how to build a Bot using Visual Studio 2015 and the C# SDK.

The sample was built in three stages.

1. Build a Bot that looks up a Stock based on a ticker name (uses Yahoo Web API)
2. Extend the Bot to add in a [LUIS](https://www.luis.ai/) model
    * Provides the ability to ask "Show me MSFT" (and similar requests)
    * Provides the ability to ask "How about now?" to return the last queried stock. This sample also uses GetBotUserData and SetBotUserData
    * The LUIS model is publised in the "Model" folder
3. Add a Forms model to the Stock Bot that demonstrates
    * Defining a form through Class elements
    * Defining prompts for form items
    * Validating user input in a form
    
The Stage 2 (LUIS) project is in the Stock-LUIS folder

The Stage 3 (Forms) project is in the StockBot folder.

