# AI Subtitle Reader

**AI Subtitle Reader** is a web application that reads movie subtitles aloud using AI voices, identifying the likely speaking character and their style for each dialogue line. Simply upload an `.srt` subtitle file, enter a movie name and your OpenAI API key, then enjoy a narrated experience of your favorite movies!

## Features

- 📝 Upload any `.srt` (subtitle) file and display its lines.
- 🤖 Uses OpenAI API to infer which character is speaking for each subtitle line, along with their gender and style.
- 🗣️ Generates speech using OpenAI's text-to-speech models, speaking each line in a gender-matched voice.
- 🎬 Supports any movie – just enter the movie's name.

## How to Use

1. **Clone or Download the Repository** and open index.html in your browser.
2. **Provide Movie Information:**
    - Type the movie name into the "Movie Name" field.
    - Select your `.srt` subtitle file in "Upload Subtitle (.srt)".
    - Paste your OpenAI API key (get one from [OpenAI](https://platform.openai.com/account/api-keys)).
3. **Click "Start Reading"**
    - The app will display and narrate each subtitle line, guessing the character and adapting the AI voice accordingly.
    - The narration pauses at each line until speech playback finishes.

## Requirements

- Modern web browser (Chrome, Edge, Firefox, Safari)
- OpenAI API key

## Disclaimer

- Your API key is only used on your device, in your browser. This app does not store or transmit your API key or subtitles anywhere except to OpenAI's API endpoints.
- OpenAI API usage may incur costs according to your account and model usage.

## License

MIT License. See LICENSE for details.