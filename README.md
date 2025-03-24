# maui-check-copilot
Example repo for experimenting with prompts to effectively replace 'maui-check' with AI

## Prerequisites

1. Install the MauiDevEnv MCP Server dotnet tool: `dotnet tool install --global Mcp.Server.MauiDevEnv`
2. Ensure the `chat.promptFiles` feature is enabled:
   ![image](https://github.com/user-attachments/assets/9f9d6af5-bf43-4365-8f90-13f3b4a4a5a7)
4. Open a new Copilot chat (use Copilot Edits and select the _Agent_ mode).
   ![image](https://github.com/user-attachments/assets/8132715f-53be-4933-b17b-55692e7e5656)
5. Check that the MauiDevEnv MCP server is running and lists its tools
   ![image](https://github.com/user-attachments/assets/8892a52b-b2bf-4292-b91e-8834c6f47e5c)
6. Click "Add Context..." in the chat and add a "Prompt", selecting "maui-dev-env.prompt.md"
   ![image](https://github.com/user-attachments/assets/3c515c12-5993-4410-b364-1c36ee505740)

## Chatting

Now you can ask the chat something like:

> Can you check my environment and help setup anything I need for .NET MAUI development?


Enjoy!


