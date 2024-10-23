# GenPT - Automated PPT and Video Generation

GenPT is a Python-based project that automates the creation of PowerPoint presentations (PPT) from text data, enhances the content using large language models (LLMs) via Ollama (Langchain), and converts these presentations into videos with synchronized audio narration using `gTTS` and `moviepy`.

## Features
- **PPT Generation**: Automatically generate PowerPoint presentations from structured data using Python-pptx.
- **Natural Content Enhancement**: Use large language models via Ollama (Langchain) to enhance slide content, transforming simple bullet points into more conversational, natural text.
- **Text-to-Speech (TTS)**: Convert slide text into audio using Google Text-to-Speech (gTTS) for narration.
- **PPT to Video Conversion**: Transform PPTs into videos with synchronized audio, dynamic slide transitions, and optional background music or animations using `moviepy`.
- **Retrieval-Augmented Generation (RAG)**: Users can upload PDFs to provide context for generating domain-specific content.
- **Dynamic Content Handling**: Duplicate and adjust slides based on dynamic data, handling complex content structures automatically.

## Future Enhancements
- **Voice Customization**: Provide options for different voices, languages, and accents for audio narration.
- **Interactive Video Elements**: Create clickable, interactive elements in videos for educational or training purposes.
- **Subtitles**: Automatically generate and sync subtitles to improve accessibility.
- **Multi-Language Support**: Generate presentations and videos in multiple languages for global audiences.

## Installation

### Requirements
- Python 3.x
- `python-pptx`
- `gTTS`
- `moviepy`
- `langchain`
- `ollama`
