LangGraph Agentic Chatbot
A sophisticated conversational agent built using LangGraph to manage complex state and cyclical logic. This chatbot doesn't just talk; it reasons and uses external tools like Wikipedia and ArXiv to provide fact-based, researched answers.

Tech Stack
Orchestration: LangGraph (Stateful, multi-actor applications)
Framework: LangChain
LLM Provider: langchain_groq (High-speed inference)
Observability: LangSmith (Debugging, testing, and monitoring)
Integration: langchain_community

External Tools & Research Capabilities
To ensure the chatbot provides accurate and up-to-date information, the following tools are integrated into the graph's node logic:

Wikipedia Search: Utilizes WikipediaAPIWrapper and WikipediaQueryRun for fetching summaries of general knowledge.
ArXiv Research: Integrated arxiv to pull technical papers and scientific research directly into the conversation.
