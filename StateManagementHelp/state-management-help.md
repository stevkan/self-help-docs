# I need help on Bot Framework SDK (Bot Development)\State management
State within a bot follows the same paradigms as modern web applications, and the Bot Framework SDK provides some abstractions to make state management easier.

As with web apps, a bot is inherently stateless; a different instance of your bot may handle any given turn of the conversation. For some bots, this simplicity is preferred - the bot can either operate without additional information, or the information required is guaranteed to be within the incoming message. For others, state (such as where in the conversation we are or previously received data about the user) is necessary for the bot to have a useful conversation.
## For more information:
- [Managing state](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-state?view=azure-bot-service-4.0)
- [Save user and conversation data](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-state?view=azure-bot-service-4.0&tabs=csharp)
- [Implement custom storage for your bot](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-custom-storage?view=azure-bot-service-4.0)
- [Manage state data (Warning: v3!)](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-state?view=azure-bot-service-3.0)
- [Manage custom state data with Azure Cosmos DB for .NET (Warning: v3!)](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-state-azure-cosmosdb?view=azure-bot-service-3.0)
- [Manage custom state data with Azure Cosmos DB for Node.js (Warning: v3!)](https://docs.microsoft.com/en-us/azure/bot-service/nodejs/bot-builder-nodejs-state-azure-cosmosdb?view=azure-bot-service-3.0)
- [Manage custom state data with Azure Table Storage for .NET (Warning: v3!)](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-state-azure-table-storage?view=azure-bot-service-3.0)
- [Manage custom state data with Azure Table Storage for Node.js (Warning: v3!)](https://docs.microsoft.com/en-us/azure/bot-service/nodejs/bot-builder-nodejs-state-azure-table-storage?view=azure-bot-service-3.0)
- [Mange state data (State service deprecation announcement)](https://docs.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-state?view=azure-bot-service-4.0)
## Additional assistance:
- https://stackoverflow.com/questions/tagged/botframework
- https://blog.botframework.com/