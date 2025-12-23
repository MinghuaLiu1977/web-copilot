
# Privacy Policy for Web Copilot

**Effective Date:** May 22, 2024

## Introduction

**Web Copilot** ("we," "us," or "our") is a browser extension designed to act as your AI assistant and browser automation tool. We value your privacy and are committed to protecting your personal information.

This Privacy Policy explains how we collect, use, and disclose information when you use our Chrome Extension. **The core principle of Web Copilot is privacy-first: we do not operate a backend server to store your personal data.**

## 1. Information We Collect

We collect and process the following types of information **only locally on your device** or transfer it to the AI provider you explicitly select:

### A. User-Provided Information
*   **API Keys:** To function, the extension requires API keys (e.g., Google Gemini, OpenAI, Qwen, Zhipu). These keys are stored locally in your browser's storage (`chrome.storage.local`) and are never sent to our servers.
*   **Voice Input:** If you use the voice control feature, your audio data is sent directly to the selected Speech-to-Text (STT) provider (e.g., Google or OpenAI) for transcription.
*   **Chat History:** Your conversation history with the AI is stored locally in your browser to provide context.

### B. Automatically Collected Information (Functional)
*   **Page Content (DOM):** When you ask the AI to "Summarize this page" or "Click a button," the extension analyzes the text and structure (DOM) of the current active tab. This data is **transient** and is sent to the AI model only when you trigger a specific command.
*   **Browser Data:** The "New Tab" dashboard displays your Top Sites and Bookmarks. This data is accessed via Chrome APIs and displayed locally; it is not collected or transmitted by us.

## 2. How We Use Your Information

We use the information strictly to provide the extension's functionality:

*   **To Provide AI Responses:** Sending your text prompts and page context to Large Language Models (LLMs) to generate answers or summaries.
*   **To Execute Automation:** Analyzing page structure to perform actions you request (e.g., clicking, scrolling, typing).
*   **To Facilitate Voice Interaction:** Converting speech to text and text to speech.
*   **To Manage Settings:** Saving your preferences (language, voice settings) locally.

## 3. Data Sharing and Third-Party Services

**We do not sell, trade, or rent your personal identification information to others.**

However, to provide AI capabilities, the extension communicates directly from your browser to the following third-party services based on your configuration:

*   **Google Gemini API:** For text generation and speech processing. [Google Privacy Policy](https://policies.google.com/privacy)
*   **OpenAI API:** For text generation and speech processing. [OpenAI Privacy Policy](https://openai.com/privacy)
*   **Aliyun DashScope (Qwen):** For text generation and TTS. [Aliyun Privacy Policy](https://www.alibabacloud.com/help/en/legal/latest/alibaba-cloud-international-website-privacy-policy)
*   **Zhipu AI:** For text generation and TTS. [Zhipu AI Privacy Policy](https://open.bigmodel.cn/privacy)
*   **Lemon Squeezy:** If you purchase a Pro license, payment processing is handled by Lemon Squeezy. We do not store credit card details. [Lemon Squeezy Privacy Policy](https://www.lemonsqueezy.com/privacy)

When you use these services via Web Copilot, their respective privacy policies and data handling practices apply.

## 4. Permissions Justification

We request the minimum permissions necessary for the extension to function:

*   **`storage`**: To store your API keys and settings locally.
*   **`activeTab` / `<all_urls>`**: Required to analyze the webpage content (DOM) for summarization and automation features on any site you visit.
*   **`microphone`**: Required for voice input commands.
*   **`bookmarks` & `topSites`**: Required only to display your shortcuts on the "New Tab" dashboard.

## 5. Data Security

*   **Local Storage:** Your sensitive data (API Keys) is stored in your browser's local sandbox.
*   **HTTPS:** All communication with third-party AI providers is encrypted via HTTPS.
*   **No Remote Server:** We do not maintain a database of user activities or chat logs.

## 6. Affiliate Disclosure

The "New Tab" page may display recommended tools (e.g., VPNs, Software) containing affiliate links. If you click these links and make a purchase, we may receive a commission at no extra cost to you. This helps support the development of the free version.

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top.

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

*   **Email:** [Your Email Here]
*   **GitHub Issues:** [Your Repository Link Here]
