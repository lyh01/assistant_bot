### <center> Bot and related resources </center>

* [How bots work](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
* [Azure Bot Service 4.0 document](https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
)
* [Adaptive Cards](adaptivecards.io)


<div>

<! -- iframe src="https://sway.office.com/s/uaCt77AbIkX7exrh/embed"  --><!-- /iframe -->

</div>



* Two ways to create bots:
  - [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/introduction) low-code/no-code
  - [Bot Framework SDK](https://docs.microsoft.com/en-us/azure/bot-service/index-bf-sdk?view=azure-bot-service-4.0)
  
* Tools - Main tools in Bot Framework for development: <a href="https://docs.microsoft.com/en-us/composer/introduction" target="_blank">Bot Framework Composer</a>, <a href="https://github.com/microsoft/BotFramework-WebChat/blob/master/README.md" target="_blank">Bot Framework WebChat</a>, and <a href="https://github.com/Microsoft/BotFramework-Emulator#readme" target=_blank>Bot Framework Emulator</a>
  * Bot Framework Composer - A visual editing canvas for conversation flows and a number of activities:
    * Build bots without the need to write code
    * Author and publish NLP data such as LUIS models and QnA Maker knowledge base
    * Author and validate language generation templates
    * Author bots in multiple languages
    * Import and export dialog assets to share with other developers
    * Build, export, and call a skill
    * Export and customize runtime (C# | JavaScript Preview)
    * Create your own custom actions
    * Host Composer in the cloud
    * Extend Composer with plugins
    * Publish bots to Azure App Service and Azure Functions
    * Integrate external services such as QnA Maker knowledge base
  * Bot Framework WebChat
  * Bot Framework Emulator
#### Bot Framework Concepts
* Adaptive cards - Open, platform-agnostic snippets of UI, authored in JSON, that apps and services can openly exchange. When delivered to a specific app, the JSON is transformed into native UI that automatically adapts to its surroundings. It helps design and integrate light-weight UI for all major platforms and frameworks
* [Dialogs](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0)  - (container, [component](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#component-dialogs), [waterfall](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#waterfall-dialogs), [prompt](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#prompts), [adaptive](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#adaptive-dialogs), action, input, [skill](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#skill-dialog), [QnA Maker](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#qna-maker-dialog))
* [Skill, skill consumer, root bot, ](https://docs.microsoft.com/en-us/azure/bot-service/skills-conceptual?view=azure-bot-service-4.0)
  * Skill is a bot that performs a set of tasks for another bot 
  * A bot can be both a skill and user-facing (consumer/root) bot 
  * Skill consumer can consume bots across language implementation (C#, Python, Javascript)
* [Adaptive expressions](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0) evaluate outcome of a condition based on runtime info available in memory to the dialog, or the language generation system. The evaluation determines how a bot reacts to user input and other factors that impact bot functionality.
* [Bot Framework Composer](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0&tabs=arithmetic#bot-framework-composer) is an open-source UI authoring tool to build bots. Composer uses adatpive expressions to create, calculate, and modify values.
* [Bot Framework Activity](https://github.com/microsoft/botframework-sdk/blob/master/specs/botframework-activity/botframework-activity.md) - Activity schema is an application-level representation of conversation actions by humans and automated software. The schema includes provision for communicating text, multimedia, non-content actions like typing indicators. Visual interactive cards (Framework Cards, Adatpive Cards) are not defined in Activity.
* [Language Genseration (.lg file)](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-language-generation?view=azure-bot-service-4.0) - language-agnostic template 
