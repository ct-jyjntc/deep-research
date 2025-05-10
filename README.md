<div align="center">
<h1>Deep Research</h1>

[![License: MIT](https://img.shields.io/badge/License-MIT-default.svg)](https://opensource.org/licenses/MIT)

</div>

**Lightning-Fast Deep Research Report**

Deep Research uses a variety of powerful AI models to generate in-depth research reports in just a few minutes. It leverages advanced "Thinking" and "Task" models, combined with an internet connection, to provide fast and insightful analysis on a variety of topics. **Your privacy is paramount - all data is processed and stored locally.**

## ✨ Features

- **Rapid Deep Research:** Generates comprehensive research reports in about 2 minutes.
- **Powered by AI:** Utilizes advanced AI models for accurate and insightful analysis.
- **Support for Multi-LLM:** Supports various language models including Gemini, OpenAI, Anthropic, and more.
- **Web Search Integration:** Compatible with search engines like Searxng, Tavily, and others.
- **Local Knowledge Base:** Upload and process text, Office, PDF files to generate a local knowledge base.
- **Research History:** Save and review previous research results.
- **Privacy-Focused:** All data is processed and stored locally on your browser.
- **Multi-language Support**: English、简体中文.

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ct-jyjntc/deep-research.git
   cd deep-research
   cp .env.example .env
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up Environment Variables:**

   Copy `env.tpl` to `.env` and add your API keys.

4. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open your browser and visit [http://localhost:3000](http://localhost:3000) to access Deep Research.

## ⚙️ Configuration

Refer to the `env.tpl` file for all available environment variables. Important ones include:

- `GOOGLE_GENERATIVE_AI_API_KEY`: For Gemini API access
- `OPENAI_API_KEY`: For OpenAI models
- `ACCESS_PASSWORD`: Optional password protection

- **Multi-key Support:** Supports multiple keys, each key is separated by `,` (e.g., `key1,key2,key3`)
- All environment variables are loaded at build time

## 🛡️ Privacy

Deep Research is designed with your privacy in mind. **All research data and generated reports are stored locally on your machine.** We do not collect or transmit any of your research data to external servers (unless you are explicitly using server-side API calls).

## 📝 License

Deep Research is released under the [MIT License](LICENSE).
