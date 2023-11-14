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

* Allow the user to execute queries against [Amazon 10-K PDF](https://d18rn0p25nwr6d.cloudfront.net/CIK-0001018724/f965e5c3-fded-45d3-bbdb-f750f156dcc9.pdf)
* Log user behavior such that it would allow your team 1) understand if the returned query results were useful and 2) inform future ideas to work on. 

To help you build the prototype, here are some libraries and tools to help you get started but feel free to use any tool:
* [Langchain Typescript SDK](https://js.langchain.com/docs/get_started/introduction)
* [Langchain Document QA](https://js.langchain.com/docs/use_cases/question_answering/)
* [QA over Docs with Langchain JS](https://www.youtube.com/watch?v=AKsfHK_4tf4&ab_channel=LangChain)
* [Vercel AI SDK](https://sdk.vercel.ai/docs)


Since this assignment is quite product focused and a throwaway prototype, we'd advise to spend less time things like engineering abstractions and unit testing and more focus on UI/UX and thoughtfully capturing user behavior when using the prototype.
