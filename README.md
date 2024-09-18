<p align="center">
  <a href="https://librechat.ai">
    <img src="client/public/assets/contactone.png" height="98">
  </a>
  <h1 align="center">
    <a href="https://contactone.com.br/">Web AI</a>
  </h1>
</p>

<!--
<p align="center">
  <a href="https://discord.librechat.ai"> 
    <img
      src="https://img.shields.io/discord/1086345563026489514?label=&logo=discord&style=for-the-badge&logoWidth=20&logoColor=white&labelColor=000000&color=blueviolet">
  </a>
  <a href="https://www.youtube.com/@LibreChat"> 
    <img
      src="https://img.shields.io/badge/YOUTUBE-red.svg?style=for-the-badge&logo=youtube&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a href="https://docs.librechat.ai"> 
    <img
      src="https://img.shields.io/badge/DOCS-blue.svg?style=for-the-badge&logo=read-the-docs&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a aria-label="Sponsors" href="https://github.com/sponsors/danny-avila">
    <img
      src="https://img.shields.io/badge/SPONSORS-brightgreen.svg?style=for-the-badge&logo=github-sponsors&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
</p>
-->

<!--
<p align="center">
<a href="https://railway.app/template/b5k2mn?referralCode=HI9hWz">
  <img src="https://railway.app/button.svg" alt="Deploy on Railway" height="30">
</a>
<a href="https://zeabur.com/templates/0X2ZY8">
  <img src="https://zeabur.com/button.svg" alt="Deploy on Zeabur" height="30"/>
</a>
<a href="https://template.cloud.sealos.io/deploy?templateName=librechat">
  <img src="https://raw.githubusercontent.com/labring-actions/templates/main/Deploy-on-Sealos.svg" alt="Deploy on Sealos" height="30">
</a>
</p>
-->

# About

A glorified ChatGPT (and any other provider) UI to create powerful knowledge bases about our solutions with custom conversation contexts.

![image](https://github.com/user-attachments/assets/02c94eeb-daa0-4be2-96d6-b695a95f204c)
![image](https://github.com/user-attachments/assets/1f8009e4-b12f-4abd-8833-678269284ed3)

Built with [🪶 LibreChat](https://www.librechat.ai/).

# 📃 Features

- 🖥️ UI matching ChatGPT, including Dark mode, Streaming, and latest updates
- 🤖 AI model selection:
  - Anthropic (Claude), AWS Bedrock, OpenAI, Azure OpenAI, BingAI, ChatGPT, Google Vertex AI, Plugins, Assistants API (including Azure Assistants)
- ✅ Compatible across both **[Remote & Local AI services](https://www.librechat.ai/docs/configuration/librechat_yaml/ai_endpoints):**
  - groq, Ollama, Cohere, Mistral AI, Apple MLX, koboldcpp, OpenRouter, together.ai, Perplexity, ShuttleAI, and more
- 🪄 Generative UI with **[Code Artifacts](https://youtu.be/GfTj7O4gmd0?si=WJbdnemZpJzBrJo3)**
   - Create React, HTML code, and Mermaid diagrams right in chat
- 💾 Create, Save, & Share Custom Presets
- 🔀 Switch between AI Endpoints and Presets, mid-chat
- 🔄 Edit, Resubmit, and Continue Messages with Conversation branching
- 🌿 Fork Messages & Conversations for Advanced Context control
- 💬 Multimodal Chat:
    - Upload and analyze images with Claude 3, GPT-4 (including `gpt-4o` and `gpt-4o-mini`), and Gemini Vision 📸
    - Chat with Files using Custom Endpoints, OpenAI, Azure, Anthropic, & Google. 🗃️
    - Advanced Agents with Files, Code Interpreter, Tools, and API Actions 🔦
      - Available through the [OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview) 🌤️
      - Non-OpenAI Agents in Active Development 🚧
- 🌎 Multilingual UI:
  - English, 中文, Deutsch, Español, Français, Italiano, Polski, Português Brasileiro,
  - Русский, 日本語, Svenska, 한국어, Tiếng Việt, 繁體中文, العربية, Türkçe, Nederlands, עברית
- 🎨 Customizable Dropdown & Interface: Adapts to both power users and newcomers
- 📧 Verify your email to ensure secure access
- 🗣️ Chat hands-free with Speech-to-Text and Text-to-Speech magic
  - Automatically send and play Audio
  - Supports OpenAI, Azure OpenAI, and Elevenlabs
- 📥 Import Conversations from LibreChat, ChatGPT, Chatbot UI
- 📤 Export conversations as screenshots, markdown, text, json
- 🔍 Search all messages/conversations
- 🔌 Plugins, including web access, image generation with DALL-E-3 and more
- 👥 Multi-User, Secure Authentication with Moderation and Token spend tools
- ⚙️ Configure Proxy, Reverse Proxy, Docker, & many Deployment options:
  - Use completely local or deploy on the cloud
- 📖 Completely Open-Source & Built in Public
- 🧑‍🤝‍🧑 Community-driven development, support, and feedback

[For a thorough review of our features, see our docs here](https://docs.librechat.ai/) 📚

## 🪶 Local Docker Environment

The local docker environment is set up using [VSCode's Containers](https://code.visualstudio.com/docs/devcontainers/containers). Load the Dev Container served within the project to scaffold the needed Docker containers and start the HMR servers using:

```bash
npm run frontend:dev
```

And:

```bash
npm run backend:dev
```

## 🌐 Resources

**GitHub Repo:**
  - **RAG API:** [github.com/danny-avila/rag_api](https://github.com/danny-avila/rag_api)
  - **Website:** [github.com/LibreChat-AI/librechat.ai](https://github.com/LibreChat-AI/librechat.ai)

**Other:**
  - **Website:** [librechat.ai](https://librechat.ai)
  - **Documentation:** [docs.librechat.ai](https://docs.librechat.ai)
  - **Blog:** [blog.librechat.ai](https://docs.librechat.ai)

---

## 📝 Changelog

Keep up with the latest updates by visiting the releases page and notes:
- [Releases](https://github.com/danny-avila/LibreChat/releases)
- [Changelog](https://www.librechat.ai/changelog) 

**⚠️ Please consult the [changelog](https://www.librechat.ai/changelog) for breaking changes before updating.**
