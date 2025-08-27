# AI Text Summarizer

This project is a simple web-based AI text summarizer built using HTML, TailwindCSS, and JavaScript. It allows you to paste any text and generate a concise summary using Google's Gemini API (Gemini 2.5 Flash).

## Features

- Clean, modern UI with TailwindCSS
- Paste text and generate summaries instantly
- Loading indicator and error messages

## Usage

1. **Open `text_summerizer.html` in your browser.**
2. Paste the text you want to summarize in the textarea.
3. Click the **Summarize** button.
4. The summary will be displayed below the button.

## Setup

To use the AI summarization feature, you need a Gemini API key:

1. Get your [Google Generative Language API key](https://aistudio.google.com/app/apikey).
2. Replace the value of `apiKey` in the JS section of `text_summerizer.html`:
   ```js
   const apiKey = "YOUR_API_KEY";
   ```

## File Structure

- `text_summerizer.html` : Main HTML file for the summarizer web app.
- `README.md` : Project documentation and setup instructions.

## Notes

- This app uses the Gemini API endpoint:  
  `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent`
- Your API key is sensitive! Do not share it publicly.
- For best results, use concise input texts.

## License

Feel free to use, modify, and share this project!