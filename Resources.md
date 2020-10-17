### <center> Bot and related resources </center>

* [How bots work](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
* [Azure Bot Service 4.0 document](https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
)

<div>
[![Sway me](https://sway.office.com/5wpqXe2gWimGh8FK?ref=Link)](https://sway.office.com/5wpqXe2gWimGh8FK?ref=Link)
</div>


<!--blank line -->
<iframe width="760px" height="500px" src="https://sway.office.com/s/N92cMD32lP3bZtrc/embed" frameborder="0" marginheight="0" marginwidth="0" max-width="100%" sandbox="allow-forms allow-modals allow-orientation-lock allow-popups allow-same-origin allow-scripts" scrolling="no" style="border: none; max-width: 100%; max-height: 100vh" allowfullscreen mozallowfullscreen msallowfullscreen webkitallowfullscreen></iframe>
<!-- blank line -->


* Two ways to create bots:
  - [Bot Framework Composer](https://docs.microsoft.com/en-us/composer/introduction) low-code/no-code
  - [Bot Framework SDK](https://docs.microsoft.com/en-us/azure/bot-service/index-bf-sdk?view=azure-bot-service-4.0)
* [Dialogs](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0)  - (container, [component](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#component-dialogs), [waterfall](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#waterfall-dialogs), [prompt](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-waterfall-dialogs?view=azure-bot-service-4.0#prompts), [adaptive](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#adaptive-dialogs), action, input, [skill](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#skill-dialog), [QnA Maker](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0#qna-maker-dialog))
* [Skill, skill consumer, root bot, ](https://docs.microsoft.com/en-us/azure/bot-service/skills-conceptual?view=azure-bot-service-4.0) - Skill is a bot that performs a set of tasks for another bot. A bot can be both a skill and user-facing (consumer/root) bot. Skill consumer can consume bots across language implementation (C#, Python, Javascript)
* [Adaptive expressions](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0) evaluate outcome of a condition based on runtime info available in memory to the dialog, or the language generation system. The evaluation determines how a bot reacts to user input and other factors that impact bot functionality.
* [Bot Framework Composer](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-adaptive-expressions?view=azure-bot-service-4.0&tabs=arithmetic#bot-framework-composer) is an open-source UI authoring tool to build bots. Composer uses adatpive expressions to create, calculate, and modify values.
* [Bot Framework Activity](https://github.com/microsoft/botframework-sdk/blob/master/specs/botframework-activity/botframework-activity.md) - Activity schema is an application-level representation of conversation actions by humans and automated software. The schema includes provision for communicating text, multimedia, non-content actions like typing indicators. Visual interactive cards (Framework Cards, Adatpive Cards) are not defined in Activity.
* [Language Genseration (.lg file)](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-language-generation?view=azure-bot-service-4.0) - language-agnostic template 