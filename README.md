# VentureScout AI: Multi-Agent VC Due Diligence System

**Project Overview:**
VentureScout AI is a multi-agent system designed to automate the preliminary due diligence process for Venture Capital investment. Using CrewAI, it orchestrates a team of autonomous AI agents to research a target startup, analyze its competitors, gauge market sentiment, and generate a comprehensive investment memo.

**The Crew:**
1.  **Tech Scout:** Analyzes the product, features, and pricing from the company website.
2.  **Market Skeptic:** Identifies competitors and evaluates the startup's "moat".
3.  **Culture Spy:** Scrapes Reddit, Twitter, and review sites for user sentiment.
4.  **The Partner:** Synthesizes all data into a final "Buy/Pass" recommendation.

**Tools Used:**
- `SerperDevTool` (Google Search API)
- `ScrapeWebsiteTool` (Web Scraping)
- `LangChain` & `OpenAI` (LLM Engine)
