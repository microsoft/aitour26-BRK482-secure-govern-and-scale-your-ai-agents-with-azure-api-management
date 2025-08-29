# DEMO-5: Security enhancements

Here we demonstrate working with the Credential Manager in Azure API Manager and how to set up a connection to GitHub using OAuth. We also test this connection from Visual Studio Code as we set up an MCP server that uses the GitHub OAuth connection.

**Link:**

> https://aka.ms/AAxn3yz

### 🕐Timing

SET UP CREDENTIAL MANAGER

| Time        | Description 
--------------|-------------
00:00 - 00:10 | Azure portal, showing where credential manager is in the menu
00:11 - 00:52 | Create a provider (GitHub as example)
00:53 - 01:29 | Setting up a GitHub app, save client id and secret, paste redirect url from Azure API Manager.

CREATE AND TEST YOUR OAUTH CONNECTION VIA AN API

| Time          | Description 
----------------|-------------
01:30- 03:40    | Try out provider and its connection in Azure Portal, 
**01:31-02:34** |  explain how API needs to be set up towards GitHub base URL and more.
**02:35**       | Test with api call.
**03:05**       | Show the policy we need on API level, provider and connection name needs to be pointed out.

EXPOSE AS MCP SERVER

| Time          | Description 
----------------|-------------
03:41-04:15     | Create mcp server.

TEST MCP SERVER

| Time          | Description 
----------------|-------------
04:16-05:46     | Add entry to *mcp.json*, add entry to "inputs" to ensure we can prompt user for subscription key (comes from Azure Portal and Azure API Management) + test calling it from "chat" in GitHub Copilot.
