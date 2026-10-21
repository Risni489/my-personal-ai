# My Personal AI

A small Tamil/Tanglish personal AI chat prototype with:
- Text chat using Gemini API
- Browser speech recognition (if supported)
- Browser text-to-speech
- In-memory conversation context

## Run it
1. Upload `index.html` to a GitHub repository.
2. For GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
3. Open the published page in Chrome.
4. Enter a Gemini API key from https://aistudio.google.com/apikey and test.

## Important security note
This is a prototype. The API key is entered in the browser and sent to Google's API, so it is not suitable for a public app or sensitive personal use. A safer production version should call the AI API through a backend that stores the key as a secret. API free-tier eligibility and limits may change.

Speech recognition and Tamil text-to-speech depend on the browser and Android language/voice settings. Conversation history is only held in page memory and disappears when the page is refreshed.
