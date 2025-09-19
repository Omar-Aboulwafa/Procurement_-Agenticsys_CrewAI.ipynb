# Bonian AI Agent for Product Procurement

This notebook demonstrates an AI agent built using CrewAI to automate the process of finding and comparing product prices online and generating a procurement report. The agent utilizes several tools and technologies:

- **CrewAI**: Framework for orchestrating autonomous AI agents.
- **Tavily Search**: Employed for searching the web to find product information and URLs.
- **ScrapeGraphAI**: Used for scraping product details from individual product pages.
- **AgentOps**: Integrated for monitoring and observability of the agent's operations.

The agent workflow is designed to:

1. **Suggest Search Queries**: Generate specific search terms for product discovery.
2. **Perform Web Search**: Use the suggested queries to find relevant product pages.
3. **Scrape Product Details**: Extract key information (title, price, specs, etc.) from product pages.
4. **Generate Procurement Report**: Compile the collected data into a structured HTML report for procurement decisions.

This project aims to provide a practical example of building multi-agent systems for automating online research and data collection tasks.
