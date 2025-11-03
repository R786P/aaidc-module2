# AAIDC Module 2: Multi-Agent Publication Assistant

A multi-agent system that helps improve AI project publications by analyzing GitHub repos and providing actionable suggestions.

## 🤖 Agents
1. **RepoAnalyzer** – Understands repo structure
2. **MetadataRecommender** – Suggests title, tags, summary
3. **Reviewer** – Checks for missing sections & improvements

## 🛠️ Tools Used
- Web Search (Tavily)
- Math Calculator
- RAG (simulated)

## 📦 Tech Stack
- LangGraph (orchestration)
- LangChain
- OpenAI (gpt-3.5-turbo)
- FAISS (vector store)

## ▶️ How to Run
1. Get a free [Tavily API key](https://tavily.com/)
2. Create `.env` file:
   ```env
   TAVILY_API_KEY=your_key_here
   OPENAI_API_KEY=your_key_here
