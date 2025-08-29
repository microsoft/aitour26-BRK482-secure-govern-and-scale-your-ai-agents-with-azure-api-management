# DEMO-2: Demonstrate monitoring

In this demo, we start with Azure API Management in Azure Portal. We get to see dashboards, bespoke queries and finally we're taken back to Azure AI Foundry for analysis of user traffic. 

**Link:**

> https://aka.ms/AAxo6jw

### 🕐Timing

| Time        | Description 
--------------|-------------
00:00 – 00:21 | Dashboard showcasing prompt tokens, completion tokens, total tokens, total requests, max tokens per minute (throughput). Also pie charts for which model is used, what APIs and which subscriptions
00:22 – 00:31 | A breakdown on which deployments were used and how much
00:32- 01:30  | lets log how we can write bespoke queries, select “Logs”, example “LLM Logs”, shows every single request in a table so we can see exactly what happened, how many tokens used, model etc
01:31 – 01:46 |  Another query, “LLM prompts and completions”, here we look at what the user typed as prompt, and the resulting output. We can export this to CSV for example for further analysis in Azure AI.
