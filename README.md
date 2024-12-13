# Memos-to-Text

Memos-to-Text is an AI-powered Speech-to-Text application that transcribes audio files and enables interactive analysis of the transcriptions using OpenAI's GPT models.

## Features

- 🎤 Audio file transcription support (mp3, wav, m4a)
- 💬 Interactive chat interface for transcription analysis
- 📝 Multiple analysis options:
  - Text summarization
  - Information extraction
  - Response draft generation
  - AI-powered content advice
- 🔧 Configurable parameters:
  - Choice of GPT models (gpt-4o, gpt-4o-mini)
  - Adjustable temperature settings
- 🔒 Secure API key handling

## Prerequisites

- Python 3.x
- OpenAI API key
- Streamlit
- OpenAI Python package

## Installation

1. Clone this repository:
```bash
git clone https://github.com/felixfrohboese/memos-to-text-streamlit.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

## Usage

1. **API Key Setup**
   - Enter your OpenAI API key in the designated field
   - The application will validate your key before proceeding

2. **Configure Parameters**
   - Select your preferred GPT model
   - Adjust the temperature setting (0.0-1.0)

3. **File Upload and Transcription**
   - Upload your audio file (supported formats: mp3, wav, m4a)
   - Click "Start Transcription" to process the file

4. **Interact with Transcriptions**
   - Use the chat interface to analyze the transcription
   - Ask questions or request specific analyses
   - Choose from suggested options or create custom prompts

## Important Notes

- All inputs are saved in the session state but are cleared when the app is closed
- The application requires an active internet connection
- API usage is subject to OpenAI's pricing and usage policies

## Technical Details

- Built with Streamlit for the web interface
- Uses OpenAI's Whisper model for transcription
- Leverages GPT models for analysis and interaction
- Implements streaming responses for better user experience

## Privacy & Security

- API keys are handled securely and are not stored permanently
- Audio files are processed in-memory
- No data is retained after the session ends

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License

Copyright (c) 2024 Felix Frohboese

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 