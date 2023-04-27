---
page_type: sample
languages:
- csharp
products:
- office-teams
description: FAQ Plus bot is one of the best friendly Q&A bots that bring a human in the loop when it is unable to help with an answer from the knowledge base.
urlFragment: microsoft-teams-apps-faqplus
---


#  FAQ Plus App

| [Documentation](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Home) | [Deployment guide](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Deployment-Guide) | [Architecture](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Solution-Overview) |
| ---- | ---- | ---- |

Chatbots on Microsoft Teams are an easy way to provide answers to frequently asked questions by users. However, most chatbots fail to engage with users in a meaningful way because there is no human in the loop when the chatbot fails to answer a question well. 

FAQ Plus bot is a friendly Q&A bot that brings a human in the loop when it is unable to help. A user can ask the bot a question and the bot responds with an answer if it's in the knowledge base. If not, the bot offers  the user an option to "Ask an expert", which posts the question to a pre-configured team of experts to provide support. An expert can assign the question to themself, chat with the user to gain more context and add the question to the knowledge base from using a messaging extention so that the next user to ask that same question will get an answer from the chatbot!

**FAQ Plus includes [Question Answering](https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/question-answering/overview), an Azure Cognitive Service for Language feature. Question answering provides cloud-based Natural Language Processing (NLP) that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. 
Build a knowledge base by adding unstructured documents or extracting questions and answers from your semi-structured content, including FAQ, manuals, and documents. Get the best answers from the questions and answers in your knowledge base—automatically. Question Answering supports a multi-turn feature to the end user experience. With the multi-turn feature, users will be presented with follow-up options along with an answer to their question. This enables the FAQ Plus bot to answer the user's question with more relevance. Multi-turn follow-up options are programmed directly into the Question Answering when the tenant admin uploads the Q&A pairs into the knowledge base.
FAQ Plus separates the end-user and the sme bot. With splitting the bot and having different bot registrations, users can setup different permission policies for these two bots.**

****

**FAQ Plus provides features to the expert team such as:**
* Adding/editing/deleting/previewing QnA
* Viewing update history of QnA
* View all the existing QnA
* View the original version of the edited QnA
* View details of manually added QnA

**Here are some screenshots showing FAQ Plus in action:**

*	A user interacting with FAQ Plus through chat:

![FAQ Plus in action (user view)](https://github.com/OfficeDev/microsoft-teams-faqplusplus-app/wiki/images/FAQPlusEndUser.gif)


*	Expert using FAQ Plus:

![FAQ Plus in action (experts view)](https://github.com/OfficeDev/microsoft-teams-faqplusplus-app/wiki/images/FAQPlusExperts.gif)


*	Expert invoking the task module to add QnA pair:

![Invoking_taskmodule1](https://github.com/OfficeDev/microsoft-teams-apps-faqplus/wiki/Images/Invoking_taskmodule1.png)

More screenshots and tips on how to use the app are in the [Wiki](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Home) of this repository.

## Getting Started

Begin with the [Solution overview](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Solution-Overview) to read about what the app does and how it works.

When you're ready to try out FAQ Plus, or to use it in your own organization,  you can choose to follow one of the below guides.
* [Deployment guide powershell](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Deployment-Guide-manual).
    * **Recommended** Use this option to deploy the FAQ Plus using powershell script. The entire set-up is done by the powershell script.
* [Deployment guide](https://github.com/Shrujal-Tailor/FAQ-Plus/wiki/Deployment-Guide).
    * Use this option to deploy the FAQ+ manually.


## Feedback

Thoughts? Questions? Ideas? Share them with us [here](https://aka.ms/fqbappfeedback)!

Please report bugs and other code issues [here](https://github.com/Shrujal-Tailor/FAQ-Plus/issues/new).
