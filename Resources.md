### <center> Bot and related resources </center>

* [How bots work](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
* [Azure Bot Service 4.0 document](https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
)
* [Adaptive Cards](adaptivecards.io)
* **Bot developement** [End to End workflow](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0#building-a-bot)[](https://docs.microsoft.com/en-us/azure/bot-service/media/bot-service-overview.png?view=azure-bot-service-4.0)

* **Two ways to create bots**:
  - [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/introduction) low-code/no-code
  - [Bot Framework SDK](https://docs.microsoft.com/en-us/azure/bot-service/index-bf-sdk?view=azure-bot-service-4.0)
  
### Tools
Main tools in Bot Framework for development: <a href="https://docs.microsoft.com/en-us/composer/introduction" target="_blank">Bot Framework Composer</a>, <a href="https://github.com/microsoft/BotFramework-WebChat/blob/master/README.md" target="_blank">Bot Framework WebChat</a>, <a href="https://github.com/Microsoft/BotFramework-Emulator#readme" target=_blank>Bot Framework Emulator</a>, <a href="https://adaptivecards.io/designer/" target=_blank>Adaptive Card Designer</a>, <a href="https://luis.ai">LUIS</a>. Further information:
  * **Bot Framework Composer**[(doc)](https://docs.microsoft.com/en-us/composer/introduction) [(desktop)](https://github.com/microsoft/BotFramework-Composer#get-started)[(build local docker image)](https://github.com/microsoft/BotFramework-Composer#build-composer-locally) - A visual editing canvas for conversation flows and a number of activities:
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
  * [Bot Framework WebChat](https://github.com/microsoft/BotFramework-WebChat/blob/master/README.md) -  a highly customizable web-based client chat control for Azure Bot Service that provides the ability for users to interact with your bot directly in a web page
  * **Bot Framework Emulator** [(doc)](https://github.com/Microsoft/BotFramework-Emulator/wiki)[(download)](https://github.com/Microsoft/BotFramework-Emulator#download) - a desktop application that allows bot developers to test and debug bots built with the SDK. The emulator can test bots running on local machine or connect to bots running through a tunnel
  * **Adaptive Card Designer with Templating**[portal](https://adaptivecards.io/designer/) - An online UI card designer 
  * **LUIS** [(doc)](https://docs.microsoft.com/en-us/azure/cognitive-services/luis/what-is-luis) [(portal)](https://luis.ai) - Language of understanding. LUIS extracts intents and entities for a subject domain. LUIS is essential to chat, search, and other downstream NLP applications
#### Bot Framework Concepts
* Adaptive cards - Open, platform-agnostic snippets of UI, authored in JSON, that apps and services can openly exchange. When delivered to a specific app, the JSON is transformed into native UI that automatically adapts to its surroundings. It helps design and integrate light-weight UI for all major platforms and frameworks. [Adaptive Card Designer](https://adaptivecards.io/designer/) using [templating](https://docs.microsoft.com/en-us/adaptive-cards/templating/#what-is-adaptive-cards-templating) to separate layout and data
* [Dialogs](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0)  - (container, [component](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#component-dialogs), [waterfall](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#waterfall-dialogs), [prompt](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#prompts), [adaptive](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#adaptive-dialogs), action, input, [skill](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#skill-dialog), [QnA Maker](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#qna-maker-dialog))
* [Skill, skill consumer, root bot](https://docs.microsoft.com/en-us/azure/bot-service/skills-conceptual?view=azure-bot-service-4.0)
  * Skill is a bot that performs a set of tasks for another bot 
  * A bot can be both a skill and user-facing bot (consumer/root bot) 
  * Skill consumer can consume bots across language implementation (C#, Python, Javascript)
* [Adaptive expressions](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0) evaluate outcome of a condition based on runtime info available in memory to the dialog, or the language generation system. The evaluation determines how a bot reacts to user input and other factors that impact bot functionality.
* [Bot Framework Composer](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0&tabs=arithmetic#bot-framework-composer) is an open-source UI authoring tool to build bots. Composer uses adatpive expressions to create, calculate, and modify values.
* [Bot Framework Activity](https://github.com/microsoft/botframework-sdk/blob/master/specs/botframework-activity/botframework-activity.md) - Activity schema is an application-level representation of conversation actions by humans and automated software. The schema includes provision for communicating text, multimedia, non-content actions like typing indicators. Visual interactive cards (Framework Cards, Adatpive Cards) are not defined in Activity.
* [Language Genseration (.lg file)](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-language-generation?view=azure-bot-service-4.0) - language-agnostic template 

### Bot Builder Tutorials
A number of bot projects with [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/tutorial/tutorial-introduction) and on [GitHub](https://github.com/microsoft/BotBuilder-Samples/blob/main/README.md)
* [Weather bot with Composer and Emulator](https://docs.microsoft.com/en-us/composer/tutorial/tutorial-introduction)
* [QnA Maker Knowledge base (create, train, test)](https://www.qnamaker.ai) - Knowledge base is a collection of question-answer pairs, stored and indexed by Azure Search as the first ranking layer. Top results from Azure Search are passed through QnA Maker's NLP re-ranking model to produce the final results and confidence score
* [Python (GitHub)](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/python) - echo bot, multi-turn, adaptive cards, QnA Maker, NLP, ...
* [Javascript (GitHub)](https://github.com/microsoft/BotBuilder-Samples/tree/main/samples/javascript_nodejs) - echo bot, multi-turn, adaptive cards, QnA Maker, NLP, ...

### <center> Additional related resources </center>
* Airbnb Knowledge Graph
   * [Jan 2019](https://medium.com/airbnb-engineering/contextualizing-airbnb-by-building-knowledge-graph-b7077e268d5a) + [Some insights from Xiaoya Wei](https://www.infoq.com/news/2019/03/wei-airbnb-knowledge-graph/)
   * [Sept 2018](https://medium.com/airbnb-engineering/scaling-knowledge-access-and-retrieval-at-airbnb-665b6ba21e95)
