# AI Agents 101: From Idea to Demo

The goal of this project is to demonstrate how to build a **working AI agent**
quickly using **n8n**.

---

## 🚀 What This Project Does

This n8n workflow implements an AI agent with:

- ✅ A **trigger** for user input (e.g. Telegram)
- 🤖 An **AI Agent** powered by a chat model (LLM)
- 🧠 **Memory** to retain conversation context
- 🛠️ **Tools** for taking actions (e.g. Google Sheet database, Google Calendar)
- 🔊  **Voice input**
- 📤 A clear response sent back to the user

---

## 📦 Requirements

Before importing the workflow, make sure you have:

- An **n8n instance** (cloud or self-hosted)
- Required credentials, such as:
  - Google Gemini API key
  - Telegram Bot Token 
  - Google Calendar API / Google Sheet API credentials 

> ⚠️ Credentials are **NOT included** in the workflow JSON for security reasons.

---

## 🛠️ How to Use This Workflow

### Step 1: Download the Workflow
- Go to the `workflows/` folder
- Download the `.json` file

### Step 2: Import into n8n
1. Open your **n8n Dashboard**
2. Navigate to **Workflows**
3. Click **Import**
4. Choose **Import from File**
5. Upload the downloaded `.json` file

---

### Step 3: Configure Credentials
After importing:
- Open the workflow
- Configure required credentials for:
  - Chat model (LLM)
  - Triggers (Telegram, Webhook, etc.)
  - Tools (Database, Google Calendar, etc.)

---

### Step 4: Activate and Test
- Click **Activate**
- Send a message via the trigger
- Observe the AI agent responding 🎉

---


## 🧠 How It Works (High Level)

This AI agent is implemented as an n8n workflow composed of modular components:

1. **Trigger**  
   Captures user input from an external source such as Telegram, Webhook, or voice input.
2. **AI Agent**  
   Acts as the decision-making layer, determining how to respond and which tools to use.
3. **Chat Model (LLM)**  
   Generates natural language responses based on the input and context.
4. **Memory**  
   Stores conversation history and context to enable multi-turn interactions.
5. **Tools**  
   Allows the agent to take actions, such as querying databases or interacting with external services.
6. **Output**  
   Sends the generated response back to the user through the original channel.
---

## 🎯 Summary

This project demonstrates how an AI agent can be built quickly and effectively using **n8n**, without writing backend code or managing infrastructure.
By combining triggers, AI models, memory, and tools in a visual workflow, you can move from **idea to working demo** in a short amount of time.
---

## 🚀 Next Steps

Once you’ve successfully imported and run the workflow, you can:

- Modify the agent prompt and behavior
- Add more tools and integrations
- Experiment with different triggers and outputs
- Extend the workflow for your own use cases


