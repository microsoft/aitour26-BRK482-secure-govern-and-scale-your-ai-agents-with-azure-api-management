# DEMO-4: Create MCP Server from Azure API Management service

Here we demonstrate how you can create an MCP Server easily from existing APIs in Azure API Management.

**Link:**

> https://aka.ms/AAxo6jv

### 🕐Timing

| Time        | Description 
--------------|-------------
00:00 – 00:12 | Inspect your API first to see what operations we have that we want to turn into mcp
00:13 – 00:38 | Select “Mcp Server” and carry out the conversion, select the operations you want turned into tools
00:40 – 00:54 | Show policies, that you can add things like rate limiting, additional security like managed identity, JWT tokens and more.
00:55 – 02:58 | Test out the mcp server from VS Code, copy url, add entry to mcp.json, write a prompt, get response, great !
02:59 - 04:00 | While we are here, let’s author some policies for our MCP Server
04:01 -       | Let’s run the inspector, this brings up a web ui where we can call tools and even test our newly drafted throttling policy, and see how we’ve been “timed out”, meaning the policy is working and only allows us to call the api   5 calls every 60 second.. 
