---
title: Computational Thinking & Gen AI
layout: default
nav_order: 4
---
## Contents
{: .no_toc .text-delta}

1. TOC
{:toc}

### The Power of Text and LLMs

When you think of "computation" or "programming," what comes to mind? Perhaps you envision a software engineer writing complex code, a data analyst crunching numbers in a spreadsheet, or a mobile app developer creating the next viral game. These are all valid examples of traditional computation, where explicit instructions are written to perform specific tasks.
On the other hand, text generation might evoke images of automated email responses, simple chatbots, or perhaps even grammar and spell-check tools.  These applications, while useful, often involve predefined templates or rule-based systems with limited flexibility. But the true power of text generation lies in its ability to tackle complex, nuanced tasks that were once thought to be exclusive to human intelligence. Consider these examples:

* **Creative Work:** Imagine generating compelling marketing copy for a new product. An AI assistant could analyze product features, target audience demographics, and even competitor messaging to craft original and persuasive content.
* **Analytical Work:**  Instead of manually sifting through mountains of data, an AI could analyze reports, summarize key findings, and even extract insights from unstructured data like meeting transcripts and emails.
* **Automation Work:**  AI-powered chatbots can provide instant, personalized customer support, analyze technical issues, and guide users to relevant solutions, all while communicating in a natural and engaging manner.

Large Language Models (LLMs) are driving this revolution. They can generate human-quality text, translate languages, write different kinds of creative content, and answer your questions in an informative way,  all through simple prompts written in natural language.  This allows for creating ad-hoc solutions to complex business problems on demand, without the need for specialized programming or data science expertise.

However, crafting effective prompts that can elicit the desired output from an LLM requires more than just asking a question. It involves applying the principles of computational thinking:

* **Decomposition:** Breaking down a complex problem into smaller, more manageable sub-problems that the LLM can address.
* **Abstraction:**  Focusing on the essential information and desired outcome, while avoiding unnecessary details that might confuse the model.
* **Algorithmic Thinking:**  Structuring the prompt in a logical and sequential manner, providing clear instructions and constraints.
* **Pattern Recognition:**  Understanding the patterns and nuances of language to craft prompts that resonate with the LLM's training data and elicit the most relevant and accurate responses.

### Understanding Large Language Models (LLMs)

**2.1 What are LLMs?**

Large Language Models (LLMs) are sophisticated AI systems that can understand and generate human-like text.  They are built upon **neural networks**, which are complex structures inspired by the human brain. These networks consist of interconnected **nodes**, processing and transmitting information like neurons.

**(Include a simplified visual representation of a neural network with interconnected nodes.)**

Imagine each node as a tiny decision-maker,  collectively contributing to the model's ability to understand and generate language.

**2.2  Key Characteristics of LLMs**

To effectively leverage LLMs, it's important to understand some of their key characteristics:

* **Training Data:** LLMs are trained on massive datasets of text and code, which influences their capabilities and potential biases.
* **Architecture:** The arrangement of these interconnected nodes in layers affects the model's performance and efficiency. Information flows through these layers, allowing the model to process and generate text.
* **Parameters:**  Think of parameters as the knobs and dials that control the model's behavior. A simple linear model might need only two parameters to describe a relationship. But human language is vastly more complex, requiring millions or even billions of parameters for LLMs to capture its nuances. For instance, ChatGPT boasts 175 billion parameters, while Gemini has even more!
* **Capabilities:** LLMs demonstrate remarkable capabilities, including:
    * **Text generation:**  Writing stories, poems, articles, and even code.
    * **Translation:**  Accurately translating between multiple languages.
    * **Summarization:**  Condensing lengthy documents into concise summaries.
    * **Question answering:**  Providing informative and comprehensive answers to complex questions.

It's important to note that while some LLMs may excel in multiple areas, trade-offs often exist. A model optimized for creative writing might not be the best at factual summarization. Additionally, LLMs can sometimes "hallucinate," generating incorrect or nonsensical information, highlighting the need for careful evaluation and critical thinking when using these models.

**2.3 Understanding Model Cards**

Now that you have a basic understanding of LLMs, let's explore how companies actually access and utilize these powerful models.

**Accessing LLMs**

There are several ways for businesses to get started with LLMs:

* **Public Cloud Providers:** Companies like Google, Microsoft, and Amazon offer LLMs as a service through their cloud platforms. This allows businesses to access and use these models without the need for significant infrastructure investments.
* **Model Repositories:** Platforms like Hugging Face and Google's Vertex AI Model Garden provide access to a wide range of pre-trained LLMs, often with different capabilities and specializations.
* **Web Services/Subscriptions:** Many LLMs are accessible via web services or APIs (Application Programming Interfaces). This allows developers to integrate these models into their own applications or workflows using simple REST (Representational State Transfer) commands.
* **Self-Hosting:** For companies with specific security or privacy requirements, self-hosting LLMs in their own data centers is also an option, although it requires significant infrastructure and expertise.

**(Include a visual showing these different access methods, perhaps with icons representing cloud providers, model repositories, web services, and on-premises data centers.)**

**The Need for Model Cards**

With so many LLMs available, choosing the right one for a specific task can be challenging. This is where **model cards** play a crucial role.

To help users choose the right LLM for their needs, model developers provide **model cards**. These cards provide essential information about the model, including:

* **Training data:**  What kind of data was the model trained on?
* **Intended use cases:** What tasks is the model best suited for?
* **Limitations:** What are the model's limitations or potential biases?
* **Ethical considerations:** Are there any ethical implications to consider when using the model?
* **Performance metrics:** How well does the model perform on different tasks?

**(Include a screenshot of a model card from Vertex AI Model Garden or HuggingFace, highlighting the key sections.)**

By understanding the information presented in a model card, you can evaluate an LLM's fitness-for-purpose and make informed decisions about its suitability for your specific business needs.

**2.4  Beyond the Basics**

While this provides a high-level overview, there are many other aspects to LLMs, such as:

* **Fine-tuning:** Adapting a pre-trained LLM for specific tasks or domains.
* **Prompt engineering:** Crafting effective prompts to elicit desired outputs.
* **Model evaluation:**  Assessing the performance and limitations of different LLMs.

We'll explore some of these topics in more depth later in the lesson.




---

**Visual 1: Diverse Applications of Computation**

* **Background:** A dynamic, abstract background with swirling colors and lines, symbolizing the ever-evolving nature of technology.
* **Foreground:** A collage of icons representing various computational applications: a smartphone, a laptop, a robot, a brain, a data center, and a cloud.
* **Text Overlay:** The phrase "Computation Beyond Code" in a bold, eye-catching font.

**Visual 2: LLM Structure**

* **Background:** A simple, clean white background.
* **Foreground:** A diagram illustrating the basic structure of an LLM. This could include:
    * Input layer: A box representing the input text (prompt).
    * Hidden layers: Multiple layers of interconnected nodes, symbolizing the processing of the input text.
    * Output layer: A box representing the generated text.
    * Arrows connecting the layers to show the flow of information.
* **Text Overlay:** "Large Language Model (LLM)" and brief explanations of each layer.

**Visual 3: LLM vs. Search Engine**

* **Background:** A split-screen design with a search engine interface on one side and a chat interface with an LLM on the other.
* **Search Engine Side:**  A search bar, search results, and ads.
* **LLM Side:** A chat interface with a user prompt and the LLM's generated response.
* **Text Overlay:** "Search Engine vs. LLM: A Comparison" with brief explanations of the key differences.

**Additional Tips:**

* **Simplicity:** Keep the visuals clean and uncluttered, focusing on the key elements.
* **Visual Hierarchy:** Use size, color, and placement to guide the viewer's eye to the most important elements.
* **Accessibility:** Ensure that the images are accessible to people with visual impairments by using appropriate color contrasts and alternative text.

By following these guidelines, you can create visually appealing and informative visuals that enhance your lesson. If you encounter any limitations with your image generation tools, consider exploring alternative options like using pre-designed templates or hiring a graphic designer for more complex visuals.

--- 

1. **The Power of Text and LLMs:**
    *  Introduce text generation as a form of computation.
    *  Explain Large Language Models (LLMs) as the technology behind it.
    *  Compare and contrast LLMs with traditional search engines.

2. **Prompt Design as Computational Thinking:**
    *  Introduce the concept of prompts and their importance in interacting with LLMs.
    *  Map prompt design elements (instructions, examples, constraints) to computational thinking concepts (algorithms, abstraction, decomposition).

3. **Hands-on with Google AI Studio and Gemini:**
    *  Introduce Google AI Studio as a platform for accessing and experimenting with generative AI models.
    *  Introduce Gemini and explain its availability as both a web service and an API.
    *  Provide a concise overview of the Gemini API and its core elements.
    *  Guide students through authentication to access the Gemini service.
    *  Engage students in creating and submitting various types of prompts (system instructions, few-shot examples, role-play).
    *  Introduce the `requests` library for making API calls to Gemini within AI Studio.
    *  Facilitate hands-on practice with basic prompting using the API.

4. **Generative AI in Business and AI Safety:**
    *  Explore real-world applications of generative AI in business (marketing, customer service, content creation).
    *  Discuss the potential impact of generative AI on various business functions and industries.
    *  Briefly introduce the concept of AI safety and ethical considerations.
    *  Direct students to an independent module for a more in-depth exploration of Responsible AI.


This streamlined lesson plan provides a focused and manageable learning experience, while still covering the essential aspects of computational thinking and generative AI. It balances conceptual understanding with hands-on practice, ensuring students gain practical skills and a broader appreciation for the technology's potential in the business world.

I'm ready to start developing content for each section whenever you are! Just let me know which section you'd like to tackle first.
