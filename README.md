# gpt
GPT Prompt new ways

### Always include the key works
- "Think hard about this"
- "Think deeply about this"
- "Think carefully"


### Engineering Mindset & Foundations
- Instead of thinking..                   Start thinking..
- What question should I ask?             What system should I design?
- Why didn't it understand me?            How can I adapt my instructions
- I hope it gives me what I want.         I will guide it to produce exactly what I need

### The 3 Principles of Effective Prompt Engineering:
- 1. Clarity over brevity - Being clear is more important than being concise
  2. Direction over correction - Guide first, then refine
  3. Systems over questions - Build frameworks, not just queries

### Build Example-Driven Systems
- 1. Few-Shot Exercise: Create a few-shot prompt for a classification or categorization task you frequently perform (e.g., categorizing leads, sorting content ideas, evaluating opportunities)
  2. Chain-of-Thought Exercise: Build a reasoning prompt for a complex business decision (e.g., market-entry, resource allocation, strategic prioritization)
  3. Compare Results: Test both methods and document:
  - Quality and depth of analysis
  - Accuracy of conclusions
  - Time saved vs. traditional methods.




## Verbosity Controls

- 1. **Low-verbosity: Give me the bottom line in 100 words or less, use markdown for clarity and structure**
  2. **Medium-verbosity: Aim for a concise 3-5 paragraph explanation.**
  3. **High-verbosity: Provide a comprehensive and detailed breakdown (xxx-xxx words)**
 
- ### **Effort: Low-verbosity outputs work best when we need only critical information.**
  1. *Example: Ask Chatgpt with prompt ``Draft a Zoom Chat message updating our co-worker on
     the critical incident ticket last-night due the power outage.``*
     - *Then add in the prompt: ``Give me the bottom 100 words or less, use markdown for clarity and structure.``*
    
- ### **Effort: Medium-verbosity works best when we need key takeaways PLUS context.**
  1. *Example: Ask Chatpgt with prompt: ``Generate a request ticket using ServiceNow when I ask this specificy words. The request is coming from NameHERE and request message.``*
     - *Then add in the prompt: ``Provide 3-5 paragraph explanation for an internal use for the team and details breakdown.``*

- ### **Effort: High-verbosity outputs are great for comprehensive documents like project briefs, research summaries, or reference materinals for multiple teams.**
  1. *Example: Ask Chatpgt with prompt: ``Generate a project brief for an internal team kick-off. The project is a complete overhaul of Powershell script code for exchange login.``*
     - *Then add in the prompt: ``Provide a comprehensive and details breakdown (600-800 words).``*
    



### Tip for using Optimize for GPT-5 url: https://platform.openai.com/chat/edit?models=gpt-5&optimize=true
- 1. Or use this prompt:
````You are an expert prompt engineer specializing in creating prompts for AI language models, particularly ChatGPT 5 Thinking model.
Your task is to take my prompt and transform it into a well-crafted and effective prompt that will elicit optimal responses.
Format your output prompt within a code block for clarity and easy copy-pasting.
Here's my initial prompt:
````


### Use The Perfection Loop (High Effort)
- 1. GPT-5 is excellent at critiquing and improving its own work, a feature OpenAI recommends we exploit.
  2. The "Perfection Loop" involves instructing the model to create its own definition of a "world-class" response, ```grade its own work against that standard, and iterate internally until it produces a perfect result. This works best for complex, zero-to-one tasks like writing a finished document from scratch.```

### You don't need to write custom instructions every time. You can use this universal prompt at the end of your request:
```
Before you respond, create an internal rubric for what defines a 'world-class' answer to my request. Then internally iterate on your work until it scores 10/10 against that rubric, and show me only the final, perfect output.
```
