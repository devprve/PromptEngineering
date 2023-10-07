# PromptEngineering

Note: you can make full use of gpt4 coding abilities and chatgpt for these assignments

 

a) Use chatgpt to write an medium.com article on best practices for writing prompts.

apply this best practices in your custom domain for a full example. 

another part of the project: You will write an app which will critique a given prompt for all the missing information. Put gpt4 as expert prompt engineer and ask it to critique and provide clues on how to improve and suggest changes for improvements so user can accept

 

Hint (you can do better than me - please try to extract best) :
https://chat.openai.com/share/43c5dc55-2273-44c1-9d20-b2b90a264a68Links to an external site.

https://chat.openai.com/share/917d0281-f34b-4eda-834d-322a19d525a0

Answer:

Part A : https://medium.com/@devipriyassn.dp/crafting-the-perfect-prompt-best-practices-9ed4f0c4c156

*************************************************************************************************************************************************************************************

b) Write an gradio or streamlit application for perfect prompt generation with proper ux  (following all best practices) using gpt4 assisted help

You will brainstorm with prompt gpt for meta prompting. come up with best prompt

Your web app -  will ask very detailed inquiry of the user requirements in iterative back and forth fashion until you have all the information you need

 

customer  will be able to test end2end the prompt with samples 

 

Then you will have refinement and iteration.

 

Use gpt4 to help you do coding for the app - or gpt-engineer or metagpt https://github.com/geekan/MetaGPTLinks to an external site. or devgpt - https://github.com/jina-ai/dev-gptLinks to an external site. - or you can also use https://vercel.com/Links to an external site. for build entire full stack app. sample app for inspiration - https://jina.ai/news/promptperfect-prompt-engineering-done-right/Links to an external site.

 

Prepare a medium.com article

checkin all the artifacts and demos with a 10 min slideshow presentation of the project.

Eg prompt that you can use as starter in your web application:

 

https://docs.google.com/document/d/1kVH-XDR06_TKQfzV6bEH1XzSMGdkv5LUwWLUc3urBDI/edit?usp=sharingLinks to an external site.

 

https://chat.openai.com/share/69140dcc-9306-40d5-b7b2-93754475616eLinks to an external site.

 

the above dialog in chatgpt is an example that you can use as a test case for your full app back and forth.

Answer:

Part B : Promptgenerationapplication.py 
When running this code in Streamlit, the user will be provided with a UI to input the domain and goal of their prompt. GPT will then suggest questions to further narrow down the details needed for prompt generation. Once the details are gathered, GPT will generate a prompt, which the user can then test. Feedback can be provided for prompt refinement.

Medium article : https://medium.com/@devipriyassn.dp/harnessing-ai-for-perfect-prompt-generation-2e2134666152

******************************************************************************************************************************************************************************

c) Write a full web app for prompt library with prompt search (use pinecone langchain library) - people can contribute the prompts nad search for prompts

 

use chatgpt generously for full app 

Should support prompt fragments as well as full prompts

support proper templating, input and output answer engienering

prompt fragments - parts of instructons of prompt that can be reused in. many usecases

 

prompt template - full system prompt, role play, input engineering, instruction engineering, output engineering

Answer : 

Part C : PromptLibrary.py
Prompt Submission: Users can submit prompt fragments or full prompts. 
Prompt Search: Integrated with pinecone for efficient search. Prompt Display: Showcasing submitted prompts with proper templating and structuring. 
Answer Engineering: Ensuring the prompt gets the desired response from the AI. 
Interaction with ChatGPT: Use GPT (like GPT-3) generously for app interactions and improvements.

