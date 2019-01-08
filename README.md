# Microsoft Azure Bot Service Hands-on Lab

Experience Microsoft Bot Services by building a sample bot

## Requirements for Lab

- Azure Subscription (Subscription Contributor or Resource Group Owner)
- Visual Studio 2017 15.6.7 (Any Edition)
- [Bot Framework Emulator & ngrok](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator?view=azure-bot-service-4.0)
- [Bot Builder V4 SDK Template for Visual Studio](https://marketplace.visualstudio.com/items?itemName=BotBuilder.botbuilderv4)

## 0. Create Development Environment

Create a VM:

* Data Science Virtual Machine Windows 2016
* Standard DS3 v2 (4 vcpus, 14 GB memory)
* West US 2 ( Or region where close to you )

Login to the DSVM you created and download followings:

* [Bot Framework Emulator & ngrok](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-debug-emulator?view=azure-bot-service-4.0)

## [1. Create and Deploy a Bot 101](./01.CreateAndDeployBot.md)

Create a project to experience how to build and deploy bot

## [2. Save user and conversation data](./02.ManageState.md)

Rememer what we said during the conversation

## [3. Prompt users for input](./03.PromptUserInput.md)

## [4. Implement sequential conversation flow](./04.SequentialFlow.md)

## [5. Write directly to storage](./05.PersisData.md)

## [6. Add Welcome Message](./06.WelcomeMessage.md)


## [7. LUIS](./07.IntegrateLUIS.md)

## [Middleware](./08.Middleware.md)

## [Enterprise Bot Template](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-enterprise-template-overview?view=azure-bot-service-4.0)

---

## References

[Managing State](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-state?view=azure-bot-service-4.0)

[Prompt Users for input](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-primitive-prompts?view=azure-bot-service-4.0&tabs=csharp)

[Implement sequential conversation flow](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-conversation-flow?view=azure-bot-service-4.0&tabs=csharp)

[Persist data](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-tutorial-persist-user-inputs?view=azure-bot-service-4.0&tabs=csharp)

[LUIS](http://aihelpwebsite.com/Blog/EntryId/1033/Using-LUIS-Language-Understanding-Intelligent-Service-MS-Bot-Framework-V4-Preview-Edition)
