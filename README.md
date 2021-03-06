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

In this lab, you'll create a bot that echo your message

## [2. Save user and conversation data](./02.ManageState.md)

In this lab, you'll add state management feature to your bot so that your bot can know your name

## [3. Prompt users for input](./03.PromptUserInput.md)

In this lab, you'll add dialogs to ask few questions in order

## [4. Implement sequential conversation flow](./04.SequentialFlow.md)

In this lab, you'll add dialog set which is a logical group of dialogs to ask a set of questions

## [5. Write directly to storage](./05.PersistData.md)

In this lab, you'll create a CosmosDB and save some data when conversation is done

## [6. Add Welcome Message](./06.WelcomeMessage.md)

In this lab, you'll use different Sctivity type to welcome a user  

## [7. LUIS](./07.IntegrateLUIS.md)

In this lab, you'll add more intelligent to your bot using LUIS

## 8. Publish Bot

In this lab, you'll publish your bot via Skype Channel

## [(Optional) 10. Add Media To Message](./10.AddMediatoMessage.md)

## [Middleware](./08.Middleware.md)

## [Enterprise Bot Template](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-enterprise-template-overview?view=azure-bot-service-4.0)

---

## References

[Managing State](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-state?view=azure-bot-service-4.0)

[Prompt Users for input](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-primitive-prompts?view=azure-bot-service-4.0&tabs=csharp)

[Implement sequential conversation flow](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-conversation-flow?view=azure-bot-service-4.0&tabs=csharp)

[Persist data](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-tutorial-persist-user-inputs?view=azure-bot-service-4.0&tabs=csharp)

[LUIS](http://aihelpwebsite.com/Blog/EntryId/1033/Using-LUIS-Language-Understanding-Intelligent-Service-MS-Bot-Framework-V4-Preview-Edition)
