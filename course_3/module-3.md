# Learn how AI works

In this lab, you'll use Gemini to brainstorm material for a presentation.

[TOC]

## Learn foundational AI concepts

Artificial intelligence is the concept ​of building intelligent machines ​that can do things like reasoning through a problem ​and providing recommendations.

 ​AI models are computer programs that are trained on tons ​of data, like articles, images, or videos. ​The model finds patterns in the data, ​and then is able to apply those patterns ​to new situations like making predictions ​or generating new content.

 This process, called **training**, ​helps the model improve over time. A model's training data shapes what it does. It's also one reason why one model may produce ​different results from another. ​A second reason is the model architecture itself. ​How a model is programmed ​and the rules it applies to its data ​and learning may vary from model to model (**model architecture**).

 Some AI models, like Gemini, learn from massive amounts ​of data that go way beyond images of fruit alone. ​With more data and training, ​a model can start doing some pretty amazing things. ​It can understand a request ​and respond to it, ​even if it's the first time it's encountering ​that type of request. ​This advanced type of model is called a **large language model** ​or an **LLM** for short.  ​

AI's ability to create something new is called Generative AI ​or GenAI for short.

Some GenAI assistants are **multimodal**, ​which is just a fancy way of saying they can work ​with more than just text. ​They can understand and create images, videos, ​audio, and more.

**AI Agents** are systems ​that combine the intelligence of advanced AI models ​with access to tools like your calendar or email. ​Instead of giving an agent a single task, ​you can give it a broader goal. ​Then the agent can break that goal down into smaller steps ​and take action on your behalf, all under your control. ​

## Fundamentals of machine learning

### Understand artificial intelligence

When we say **artificial intelligence (AI)**, we’re referring to a broad field focused on creating tools that can complete tasks usually associated with human intelligence. These tasks can range from writing emails to suggesting driving routes.

It's important to recognize that its knowledge comes from the specific data it was trained on. This is where **Machine Learning** comes in.

### Understand machine learning

One of the most common ways of training AI models is with machine learning, a technique that enables a tool to find patterns and learn from data on its own. It doesn’t even need to be programmed for every possible scenario.

For example, let’s say someone wants to use AI to sort zebras from horses. For this to work, they must first train a machine learning program so it can distinguish zebras from horses. They provide the machine learning program with thousands of images depicting both zebras and horses. As the machine learning program processes these images, it eventually learns to identify features of zebras, like stripes.

After being trained with machine learning, AI can then identify zebras from photos that weren't in its training set. This process is called **inference**.

Understanding the role machine learning plays helps you recognize that AI’s performance is a direct result of the data it was trained on.

### Approaches to machine learning

There are three common machine learning approaches used to develop AI:

1. **Supervised learning** is used to train AI from a large dataset that has been labeled by people. This technique is often used when there is a specific, known output in mind.

   - For example, a model is trained on millions of pictures that a person has explicitly labeled zebra or horse. AI learns the specific characteristics of each animal so it can automatically sort new images into those predefined categories.

1. **Unsupervised learning** is used to train AI from a dataset that has not been labeled by people. This technique is used to identify patterns and structures in data when there isn't a specific, known output in mind.

    - For example, a model analyzes a large, unlabeled dataset of photos containing horses and zebras. Without being told what a zebra is, the AI discovers patterns on its own, like striped or solid, and clusters images with similar features together.

1. **Reinforcement learning**is used to train AI through a trial-and-error process that is guided by a reward system. This technique is used to continuously refine how AI approaches a specific task or goal.

   - For example, a model is tasked with identifying zebras in a video. It has not received any training, so it has to make a guess. Each time the model guesses correctly, it receives a "positive reward.” If the guess is wrong, it receives a "penalty." Over many attempts, AI learns to adjust its strategy to maximize its total reward, gradually mastering the task through experience.

Today, many AI models use a combination of all three machine learning approaches to create text, images, video, and more.

## Understand AI limitations

A key part of being a responsible AI user is knowing how AI works and where it can fall short. AI has limitations, such as potential biases, knowledge cutoffs, and drift in output. Recognizing these limitations can help you evaluate outputs more effectively and use AI in a way that’s fair, accurate, and responsible.

### Understand biases in AI

Data bias can be a foundational challenge for AI. This can happen when the data used to train an AI model is skewed, incomplete, or reflects historical or societal biases. Because the model’s output is directed by its training data, it can sometimes reproduce existing biases in its response, like connecting specific activities with certain age groups.

Part of following a responsible AI approach is being aware that AI models may create stereotypes or bias in their outputs. Your role is to guide the model toward a fair and impartial output.

To avoid unfair bias in outputs, you can use these techniques in your prompts:

- **Be specific about the output you want:** Add important context about your intended audience and their needs. You can also provide fair and balanced references for the model to follow.

- **Use follow-up prompts to correct outputs that seem biased or inaccurate:** If AI provides a biased response, point out the stereotype when you iterate on your prompt and ask the model to correct the bias.

### The constraint of knowledge cutoff

**Knowledge cutoff** is the point in time when a model’s training data ends. This means the model lacks information on events, discoveries, or data that occurred after that date.

You might notice that a model can provide information about very recent events. Some may do this by performing a live web search to find current information that they can supplement their answer with. It's helpful to think of this as the difference between what the model knows from its training versus what it can look up in the moment. The model's core knowledge is not continuously updated, which is why the concept of a knowledge cutoff remains a critical limitation to bear in mind.

Always use a search engine or other reliable sources to fact-check statistics, news, or any information about recent events.

To work effectively with a model's knowledge cutoff, you can use these techniques:

- **Look up the cutoff:** You can search online for the knowledge cutoff date of a specific AI tool. This helps you understand the boundary of its internal knowledge.

- **Verify time-sensitive information:** For any statistics, breaking news, or details about recent events, always cross-reference AI's answer with a reliable external source, like a search engine or an official report.

- **Specify your timeframe:** When asking about a topic that changes over time, state the timeframe for what you need. For example, instead of "What was the biggest song of the summer?" ask “What was the biggest song of the summer in 2025?”

- **Refine with follow-up prompts:** If an answer seems outdated, like calling a product new when it is several years old, use a follow-up prompt to ask for more recent alternatives or clarification.

### Changes in AI’s performance over time

**Drift** is the gradual decline in a model’s accuracy and relevance as the real world changes. You might observe drift in two ways:

- **Factual drift:** This is when AI becomes less accurate over time because of its knowledge cutoff. For example, an AI model's advice on current fashion trends may become less useful the further you get from its training date.

- **Behavioral drift:** This refers to changes in AI’s behavior over time. As developers update models, you might notice that the formatting, tone, or conversational style changes, even when you use the same prompts.

Here are a few ways to manage and mitigate both kinds of drift:

- **Provide accurate and up-to-date context in your prompts**, especially for topics that change quickly, like market trends or technology.

- **Keep chats focused by starting a new conversation for each specific task.** This also helps to reset the context window if a conversation becomes too long or the output starts to feel off topic.

- **Be explicit** with clear and specific instructions in your prompts.

The best results come from a combination of human ingenuity and AI’s capabilities. So keep asking insightful questions, refining your prompts, and above all, applying your critical-thinking skills to verify outputs before you use them.

## Leverage AI features and capabilities for work

Let's start with some of the things AI can do ​and how it can help you at work.

​First, AI can help you understand information. ​Think of summarizing multi-page reports in seconds, ​getting insights from a dense spreadsheet, ​or getting up to speed on a client's industry. ​This can help set you up for better decisions. ​AI can also create new things. ​It can help you draft communications, ​build the outline of a presentation, ​and even generate product images. ​And finally, AI can help you improve your work. ​It can poke holes in a project plan, ​or suggest ways to make a client proposal better, ​and it can give you fresh ideas for you to evaluate.

If you can give instructions, ​you already have some of the skills. ​That's because AI understands natural language. ​That means you communicate through everyday words, ​either through typing or through speech.

The key to using AI well ​is giving clear and specific instructions, or prompts. **​Prompts** are instructions you give to AI ​to get the results that you want. ​Sometimes you'll upload files ​or other documents in your prompt ​that you want it to take into account. ​Everything you include in your prompt is called an **input**. ​What AI generates in return is called the **output**.

​Knowing how to prompt well ​is a fundamental skill to unlock AI's full capabilities. ​First, let's start with the [AI model Gemini][1]. ​It's the technology ​that does the actual reasoning and generation. Gemini app, [gemini.google.com,][2] helps you access the Gemini model.

To command AI, we use parts of its interface, ​like the **chat box** and its features. ​But the Gemini models power more than just the Gemini app. ​It's a family of some of Google's most capable AI models, ​and it's built into products like Google search, ​Maps, Pixel, and more. ​While you're in the Gemini app, ​you can explore different models and features ​to pick the right one for what you're trying to accomplish.

​Different AI models have different strengths, ​depending on how they were trained ​and how their learning was refined. ​Some models are really good ​at quickly providing all-around help. ​Other models might be best for advanced tasks ​like research, coding, ​or weighing the pros and cons of a complicated decision. ​Keep in mind, more complex tasks require more computations, ​which could take the model longer to complete.

[1]: <https://deepmind.google/models/gemini/> "Gemini"
[2]: <https://gemini.google.com/> "Gemini app"
