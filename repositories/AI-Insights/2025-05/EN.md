# AI Insights #1 – May 2025
Welcome to the inaugural edition of the AI Insights newsletter. Our aim is to keep you regularly updated on the most significant trends and news shaping the world of artificial intelligence. We're here to act as your AI guide, cutting through the jargon and highlighting what truly matters, in order to share important information that can inspire your projects and bring new perspectives. In this first issue, we're focusing on the biggest AI trends we've observed so far. While some news may not be directly applicable to our immediate work, we believe it's essential to stay informed about the broader developments in the industry.

In the coming months, we'll be bringing you more focused updates on month-to-month developments from the leading AI companies, as well as keeping a close eye on the exciting news in the Open Source ecosystem. Since this is our maiden voyage, your feedback is invaluable! Let us know what you think of the format, what topics you'd love us to explore next, whether you want deep dives into specific areas, or if you prefer shorter, more frequent updates. We're all ears and eager to make this newsletter a valuable resource for you.

## AI Agents
AI Agents are THE hottest topic in AI for 2025! But what exactly are they? Broadly speaking, an AI Agent is a system or program engineered to perform tasks autonomously by designing its own workflow and leveraging available tools. Now, you might be thinking, "Hey, doesn't that sound like pretty much every chatbot out there?" And you'd have a point! By this definition, even current chatbots that use search tools to retrieve information before answering your queries could technically qualify as agents. However, it's probably more helpful to think of agentic behavior as a spectrum rather than a simple yes or no. Think of it like 'intelligence' in humans – it's not just a binary condition, but a whole range of abilities. The AI landscape in May 2025 showcases a fascinating array of agentic approaches, which can be broadly categorized into three main patterns.

### AI Agent Products
These are AI systems meticulously optimized for specific use cases, offering impressive power within their defined boundaries. However, this specialization often comes with less flexibility when it comes to integrating custom tools or unique integrations. A prime example of an AI Agent Product making waves is Manus, a Chinese startup that burst onto the scene in March 2025 and genuinely amazed people with its remarkable problem-solving capabilities. Turns out, this impressive feat was powered by the standard Claude Sonnet from Anthropic, armed with a carefully selected arsenal of 29 tools. This showcases just how much reasoning current large language models (LLMs) are capable of when applied strategically. The key takeaway here is that these AI Agent Products are like highly specialized tools – amazing for the job they're built for, but not so great for custom integrations.

### Managed Agentic Platforms
The big players (and some savvy startups) are also jumping into the agent game with Managed Agentic Platforms. Think of these as your 'AI Agent Starter Kits' – pre-configured and ready to roll! Examples include Azure AI Agent Service & Microsoft Copilot Studio, AWS Agent Builder, and Google's Vertex AI Agent Builder. These platforms come loaded with pre-built integrations, making it super quick to get your first agent up and running. However, a word of caution: these platforms are often optimized for their provider's ecosystem, so be mindful of potential 'vendor lock-in'. Pricing can also vary quite a bit, based on everything from the number of conversations to infrastructure usage and compute power.

### Open-Source Libraries
For the DIY enthusiasts out there, the Open-Source ecosystem is brimming with possibilities! These libraries offer maximum flexibility, but remember, you're the one in the driver's seat for development and management. Key players in this space include LangGraph (from the awesome LangChain team), LlamaIndex, SmolAgents (kudos to HuggingFace!), CrewAI, AutoGen, and Microsoft's SemanticKernel.

To provide a clearer picture of these distinct patterns, here's a quick comparison:

Feature | AI Agent Products | Managed Agentic Platforms | Open-Source Libraries
|-----|-----|-----|-----|
**Focus** | Specific Use Cases | Speed of Initial Development | Flexibility and Customization |
**Flexibility** | Less flexible for custom tools/integrations | Optimized for provider's ecosystem | Highly flexible
**Ease of Use** | Generally user-friendly for intended purpose | Easy initial setup with preconfigured integrations | Requires self-management and development effort
**Integration** | Limited to specific use case needs | Optimized for specific cloud provider ecosystem | Highly customizable with various tools and APIs
**Management** | Managed by the product vendor | Managed by the platform provider | Requires self-management
**Example** | Manus | Azure AI Agent Service, Copilot Studio, etc. | LangGraph, LlamaIndex, CrewAI, etc.
**Pros** | Optimized for specific tasks, easy to use | Fast development, preconfigured integrations | High flexibility, no vendor lock-in
**Cons** | Limited flexibility, potential feature lock-in | Potential ecosystem lock-in, pricing variability | Requires technical expertise, self-management

## Deep Research
Tired of endless Google searches? Enter Deep Research! This trend takes web search integration to a whole new level, moving beyond simple chatbots that just fetch info. Imagine an AI that not only searches the web but also crafts a detailed research plan, investigates each topic step-by-step, and then compiles its findings into a comprehensive report – complete with links to its sources! This capability, often referred to as report generation, has rapidly gained traction in the AI community. Perplexity was the first to the party with this functionality, launching its Deep Research feature in February 2025. This tool quickly garnered attention for its ability to generate in-depth research reports on virtually any topic, performing numerous searches, analyzing hundreds of sources, and reasoning through the material to deliver a comprehensive output. Perplexity's Deep Research is available on the web and is gradually rolling out to mobile platforms, offering a limited number of free queries daily for non-subscribers and a significantly higher limit for Pro users.

It wasn't long before others like OpenAI and Google jumped in. Shows you how quickly things move in the AI world! OpenAI followed suit in February 2025 with its own Deep Research agent, initially for Pro users, leveraging a version of their upcoming o3 model optimized for web browsing and data analysis. This tool aimed to function as a "research analyst," capable of independently retrieving, analyzing, and synthesizing online information to produce structured reports with citations. OpenAI later expanded access to Plus, Team, Enterprise, and even free users with a lightweight version powered by o4-mini. Google also entered the arena with Gemini's Deep Research, initially launched in December 2024 for Gemini Advanced subscribers and further updated in March 2025. Gemini's approach involves transforming prompts into multi-point research plans, autonomously searching and browsing the web, reasoning over gathered information, and providing comprehensive reports, sometimes even with audio overviews.

Comparisons between these Deep Research tools have already begun to emerge. Perplexity is often lauded for its speed and accessibility, offering a free tier and generally faster response times. OpenAI's Deep Research is noted for its accuracy and the inclusion of clear citations. Gemini's Deep Research benefits from its deep integration with Google's search expertise and the unique feature of audio overviews. Ultimately, the choice of which Deep Research tool to use may depend on individual needs and priorities, whether it's speed, accuracy, integration, or cost-effectiveness.

## Voice Interface
Who needs keyboards anyway? While they've been around for ages, there's a growing wave towards using our voices for more natural chats with AI. While many chatbots already offer basic speech-to-text or text-to-speech functionality, May 2025 has seen some truly remarkable advancements in creating more human-like and intuitive voice interfaces.

### ChatGPT's Advanced Voice Mode
ChatGPT's Advanced Voice Mode is like talking to a real person (almost!). It picks up on your tone, accent, even those awkward pauses when you're thinking. This multi-modal interface processes the user's voice directly, reacting to nuances like tone, accents, pauses, and cadence. It's especially cool for language learning, helping you nail that pronunciation. This mode aims to mimic human conversation more closely by reducing interruptions and allowing for more natural pacing. Users on paid plans also benefit from an updated personality that OpenAI describes as "more engaging, direct, and concise".

### Sesame
Then there's Sesame, a startup making waves with its incredibly realistic AI voices. They can handle tone, pauses, even laughter! While it still infers emotions from context, the responses sound eerily human. Sesame's new Conversational Speech Model (CSM) has even led some testers to report feeling emotional connections to the AI voices, named Maya and Miles. The company, founded by Brendan Iribe (co-founder of Oculus), aims to achieve "voice presence," making spoken interactions feel genuinely real, understood, and valued. Sesame's technology analyzes entire conversations to adjust tone, rhythm, and pacing based on mood and content, mimicking natural human speech.

### Nari-labs' Dia
Fresh off the press! Nari-labs dropped Dia just last week. This model is a master of context, generating tones that fit the conversation, even handling multiple speakers, laughs, and coughs! Released in late April 2025, Dia is an open-source Text-to-Speech (TTS) model designed to generate realistic, multi-speaker dialogue directly from text transcripts, complete with non-verbal cues. And get this – it was developed by just TWO people! Talk about impressive! This really shows what's achievable today with focused effort. Dia distinguishes itself by focusing on generating realistic dialogue with relevant tones based on conversation context, even handling multiple speakers and non-verbal expressions like laughs and coughs.

## Key AI Releases
The AI world never sleeps, and May 2025 has already brought a flurry of exciting releases and updates. Here are a few noteworthy highlights:

### NotebookLM from Google
Google's NotebookLM just got a cool upgrade: it can now generate podcast-style audio summaries in over 50 languages, including Czech! Great for learning on the go!. This feature, powered by Gemini's native audio support, allows users to transform their notes and sources into engaging, podcast-like conversations that can be downloaded for offline listening.

### Alibaba Group
Big news from Alibaba! They've released an Open-Weight model with some serious reasoning power, and it's under the Apache 2.0 license. This means you can run it on your own hardware, even for commercial use! Alibaba launched its Qwen 3 model family on April 28, 2025, with all models licensed under the permissive Apache 2.0 license. This release includes eight distinct models, featuring both dense and Mixture of Experts (MoE) architectures, with sizes ranging from 0.6B to 235B parameters. A key feature of Qwen 3 is its hybrid approach to problem-solving, supporting both a "Thinking mode" for complex reasoning and a "Non-Thinking mode" for faster, direct responses.

### OpenAI
OpenAI hasn't been sitting still either! They've dropped the full version of their o3 model, along with the o4-mini. These are the 'thinkers' of the AI world, designed to take their time and really ponder before giving you an answer. Great for those tricky tasks like coding, tackling complex math problems, diving into science, or even understanding visual data. Released on April 16, 2025, o3 and o4-mini are the latest in OpenAI's o-series of reasoning models. These models are trained to deliberate longer before responding, showcasing enhanced capabilities in coding, math, science, and even visual perception. They also have full access to tools within ChatGPT, including web search, file analysis, and image generation, enabling a new level of agentic problem-solving.

### Gemini 2.5 from Google
And last but not least, Google's Gemini 2.5 has been making waves, quickly climbing to the top of the LLM leaderboards! You can even try it out for free in preview mode, in both its 'Flash' (fast) and 'Pro' (powerful) versions. Go give it a whirl! Gemini 2.5 from Google has rapidly ascended the LLM leaderboards, demonstrating state-of-the-art performance across a range of benchmarks. Available in preview mode since March and April 2025, both the Flash and Pro versions offer a glimpse into Google's most intelligent AI model yet, featuring enhanced reasoning and advanced coding capabilities.

## Must-Listen AI Podcasts
Staying informed in the fast-paced world of AI can be a challenge, but thankfully, there are some fantastic podcasts out there to help you keep up. We label each podcast using these three categories:
- **Complexity**: Indicates the level of technical knowledge needed to understand the AI concepts discussed.
- **Applicability**: Shows how directly the AI solution can be applied to common tasks.
- **Timeline**: Reflects how long it will take for the technology to be available.

Here are a few must-listens:

### AI for Humans Podcast - [Listen here](https://www.aiforhumans.show/deepmind-says-were-not-ready-for-agi-academy-awards-say-ai-video-is-ok-and-ai-voice-models-get-we/)
- Want to hear some expert opinions on whether we're ready for AGI? The latest episode of the 'AI for Humans' podcast dives into DeepMind's take, plus the Academy Awards' view on AI video and some truly bizarre AI voice model developments. Released on April 24, 2025, this episode breaks down Google’s new “Era of Experience” paper, discussing agentic systems, long-term memory, and the potential for truly intelligent machines. Plus, you'll hear about a real AI vending machine running on Claude and a robot half-marathon in Beijing! And for a bit of dark humor, they talk about Cluely, the tool that helps you lie better with AI! Also, they touch on AI video tools from Minimax and Character.AI. And let's not forget Runway’s 48-hour film contest and Dia, the open-source voice model that can scream and cough better than humans!

- **Complexity**: 🤯
- **Applicability**: 🎯 🎯 🎯
- **Timeline**: 🗓️


### Last Week in AI Podcast - [Listen here](https://lastweekin.ai/p/lwiai-podcast-205-gemini-25-chatgpt)
- Stay up-to-date with the rapid pace of AI with the 'Last Week in AI' podcast. Their episode #205, released around April 1, 2025, covers the impressive image generation capabilities of ChatGPT, showcasing some serious advancements. They also discuss OpenAI's massive $40 billion funding round (led by SoftBank), Sam Altman's move towards technical direction, and Anthropic's groundbreaking research into understanding how AI models reason. And if you're into pushing AI to its limits, they talk about new benchmarks like ARC AGI 2 and super-tough Sudoku puzzles! This podcast provides weekly summaries and discussions about the most interesting developments in AI, deep learning, and robotics.

- **Complexity**: 🤯 🤯 🤯
- **Applicability**: 🎯 🎯
- **Timeline**: 🗓️ 🗓️

### Practical AI Podcast - [Listen here](https://practicalai.fm/309)
- For a more technical deep-dive, check out the 'Practical AI' podcast. Their episode #309, released around April 14, 2025, features a discussion with EPAM's Chief Technologist about the nitty-gritty of orchestrating AI agents and managing connections to different systems using APIs and MCP servers. You'll get insights from Pavel Veller about his work with agentic architectures and internal tools like 'DIAL'. They also demystify MCP servers and explain why connecting AI assistants via APIs is relatively easy, but making them genuinely useful is the real challenge. This podcast focuses on productive implementations and real-world scenarios in artificial intelligence.

- **Complexity**: 🤯 🤯 🤯 🤯
- **Applicability**: 🎯 🎯 🎯 🎯
- **Timeline**: 🗓️

#### Disclaimer
We've crafted this newsletter based on our own ideas, but leveraged AI for editing, fact-checking, and tone; please share your thoughts to help us refine our approach.
