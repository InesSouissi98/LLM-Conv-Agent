# LLM-Conv-Agent

This project is about a Conversational LLM Agent, augmented with a continual learning system, which can resolve four issues that occur in continual learning: <br>
1- Duplicated memories: If there are repeated events, you don’t want to recall all of them. Otherwise you may fill up the context with identical events and retrievals will be uninformative. <br>
2- Contradictory memories: If there are two instructions that contradict each other, how should the LLM respond when it should execute one of the instructions? 
3- Temporary memories: Information with some finite lifetime (E.g “Until further notice…”)  
<br>
4- Episodic memories: refer to the ability of the LLM agent to remember specific events or interactions in a time-stamped manner. Unlike general rules or guidelines, these are memories tied to particular instances or conversations, allowing the LLM agent to reference past interactions for context or to provide more personalized and informed responses. <br>

Tools :
Programming language: Python, NLP <br>
Library: ConversationSummaryMemory <br>
Model: HuggingFaceH4/zephyr-7b-beta model API: Hugging Face API Key 
