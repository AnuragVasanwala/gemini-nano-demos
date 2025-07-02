# Gemini Nano Demos

A collection of interactive demos and workflow examples showcasing Chrome's built-in Gemini Nano AI capabilities.

![Gemini Nano Demos](assets/gemini-nano-featured-image.webp)

## Overview

This repository contains interactive demonstrations of Chrome's Gemini Nano APIs, allowing developers to explore AI capabilities that run completely on-device. The demos showcase both individual API functionalities and interlinked workflows that combine multiple APIs to solve real-world problems.

## Features

### Individual API Demos (`gemini-nano-samples.html`)

Explore each of Chrome's Gemini Nano APIs with interactive examples:

- **🌐 Translator API**: Translate text between languages with high accuracy
- **🔍 Language Detector API**: Automatically identify the language of input text
- **📝 Summarizer API**: Create concise summaries of longer text content
- **✍️ Writer API**: Generate high-quality text content from prompts
- **🔄 Rewriter API**: Transform existing text with different tones and styles
- **💬 Prompt API**: Interact with Gemini Nano's language model directly

### Interlinked Workflows (`gemini-nano-workflows.html`)

Experience how combining multiple Gemini Nano APIs creates powerful end-to-end solutions:

#### Basic Workflows:

1. **Universal Text Processor** 🌐📝
   - Detects language → Translates to target language → Summarizes content
   - Perfect for processing international content efficiently

2. **Content Generation & Enhancement** ✍️🔄
   - Generates initial draft → Polishes and enhances content
   - Great for creating blog posts, marketing copy, or documentation

3. **Multilingual Customer Support** 🔍🌐💬
   - Detects customer language → Translates to English → Generates response → Translates back
   - Enables seamless support for customers in any language

4. **Document Analysis & Q&A** 📝💬
   - Summarizes document → Extracts specific information based on queries
   - Ideal for research, legal document analysis, and information extraction

#### Advanced Workflows:

5. **Smart Reading Assistant** 📚🧠
   - Detects language → Processes content based on selected mode (summary, simplified, expert, study questions)
   - Allows follow-up questions on the processed content
   - Perfect for students, researchers, and lifelong learners

6. **Knowledge Explorer** 🔎🧩
   - Analyzes concepts → Generates explanations, examples, and context → Creates connections to related topics
   - Provides deep context without leaving your current page
   - Ideal for research, education, and knowledge work

7. **Multilingual Content Creator** 🌐✍️
   - Creates content → Optimizes for cross-cultural understanding → Translates to multiple languages
   - Generates culturally appropriate content for global audiences
   - Valuable for global businesses, content creators, and educators

8. **Smart Note-Taking Assistant** 📝📊
   - Processes raw notes → Extracts action items and decisions → Organizes into structured formats
   - Transforms unstructured meeting or lecture notes into actionable information
   - Perfect for students, professionals, and anyone who takes notes

## Getting Started

### Prerequisites

- Chrome browser version 138 or later
- Gemini Nano model support on your device

### Installation

1. Clone this repository:
```bash
git clone https://github.com/AnuragVasanwala/gemini-nano-demos.git
```

2. Open the HTML files in Chrome:
   - Open `gemini-nano-samples.html` to explore individual API demos
   - Open `gemini-nano-workflows.html` to see interlinked workflow examples

Alternatively, you can access the demos directly through GitHub Pages at [anuragvasanwala.github.io/gemini-nano-demos](https://anuragvasanwala.github.io/gemini-nano-demos).

## Usage

### API Samples Page

1. Navigate through the different API cards
2. Enter text in the input fields to test each API
3. Click the corresponding action button (e.g., "Translate", "Detect", etc.)
4. View the results in real-time
5. Click "View Code Sample" to see implementation examples for each API

### Workflows Page

1. Choose a workflow that interests you
2. Enter the required input text
3. Click the action button to start the workflow
4. Watch the step-by-step progress as multiple APIs work together
5. Review the results of each processing stage

## Technical Details

All processing happens on-device using Chrome's built-in Gemini Nano models:

- No cloud connectivity required for inference
- Data never leaves the device
- Processing happens locally, ensuring privacy

The demos use the following Chrome JavaScript APIs:

```javascript
// Available Gemini Nano APIs
self.Translator        // Text translation between languages
self.LanguageDetector  // Automatic language identification
self.Summarizer        // Text summarization
self.Writer            // Content generation (experimental)
self.Rewriter          // Content transformation (experimental)
self.LanguageModel     // Direct prompting interface
```

## Use Cases

### Individual APIs

- **Translator**: Website localization, content translation, learning aids
- **Language Detector**: Content routing, automatic localization, language-specific processing
- **Summarizer**: News digests, document overviews, content briefs
- **Writer**: Blog post creation, marketing copy, product descriptions
- **Rewriter**: Content repurposing, tone adjustment, formatting changes
- **Prompt API**: Conversational AI, custom assistants, knowledge extraction

### Combined Workflows

#### Basic Workflows
- **News Processing**: Automatically translate, summarize, and extract key points from international news
- **Customer Support**: Handle multilingual inquiries with automated detection, translation, and response generation
- **Content Creation**: Generate drafts and polish them with appropriate tone and style adjustments
- **Document Analysis**: Extract specific information from lengthy documents with summarization and targeted queries

#### Advanced Workflows
- **Smart Reading**: Transform complex content into accessible formats (summaries, simplified explanations, expert analysis)
- **Knowledge Exploration**: Get in-depth explanations, examples, and connections between concepts
- **Multilingual Publishing**: Create content once and adapt it for multiple languages and cultures
- **Meeting Intelligence**: Convert raw meeting notes into structured action items, decisions, and follow-ups

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

⚠️ **Note**: The Gemini Nano APIs are still evolving. Some features may be experimental or change in future Chrome releases.