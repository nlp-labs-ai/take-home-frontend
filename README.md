# Assignment

The goal of this take home assignment is to assess product engineering mindset and approach.

* [Product Engineering](https://posthog.com/blog/what-is-a-product-engineer)
* [Case for Product Engineering](https://weaviate.io/company/playbook/the-case-of-product-engineering)


## Task

Your work for an AI fintech company that is looking to build an AI-enabled product for financial analysts to conduct research faster. Through customer interviews you've learned that one of the biggest painpoints in researching a company is pouring through hundreds to thousands of pages of [EDGAR SEC 10-K Filings](https://www.sec.gov/edgar/searchedgar/companysearch). Assume from the interviews that analysts typically have 2 types of research questions, factual and summarization. Here are some plausible research questions:

* What was Tesla's revenue and COGS in 2022Q3? (Factual)
* Summarize the operating risks of Amazon (Summarization)

You and your team think that solving the problem of extracting information from 10-K filings would be a huge value add to the company's product/platform. 

Before spending weeks to engineer a complete solution, you decide it's better to come up with a quick prototype that an analyst can get their hands on and execute some queries.

Your goal is to build a prototype that does the following:

* Allow the user to execute queries against 10-K documents
* Log user behavior such that it would allow your team 1) understand if the returned query results were useful and 2) inform future ideas to work on. 

To help you build the prototype, here are some libraries and tools to help you get started but feel free to use any tool:
* [LlamaIndex](https://www.llamaindex.ai/)
* [Langchain](https://www.langchain.com/])
* [SEC EDGAR Downloader](https://sec-edgar-downloader.readthedocs.io/en/latest)
* [LlamaIndes SEC Insights](https://github.com/run-llama/sec-insights)


Since this assignment is quite product focused and a throwaway prototype, we'd advise to spend less time things like engineering abstractions, unit testing, and making the UI look pretty and focus more on getting learnings and concrete takeaways from analysts using the prototype.
