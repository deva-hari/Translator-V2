# AI Novel Translator

A modern, production-ready web app for translating Chinese novels to English using the latest free AI models (Gemini, GroqCloud, OpenRouter). Designed for translators, readers, and hobbyists who want high-quality, customizable translations with a beautiful, responsive UI.

## Features

- **Multiple AI Providers:**
  - Gemini (Google AI Studio)
  - GroqCloud
  - OpenRouter
  - *(Chuttes AI logic included, but hidden in UI)*
- **Best Free Models:**
  - Provider/model selector with curated free-tier models
- **Per-Provider API Key Storage:**
  - Securely stores API keys for each provider in your browser
- **Prompt Presets:**
  - Creative, Literal, and Just Translate presets
  - Custom prompt editing and persistent selection
- **Batch Translation:**
  - Translate multiple `.txt` files at once and download as a ZIP
- **Output Customization:**
  - Font size, font type, line spacing, and paragraph spacing controls
- **Translation History:**
  - View, copy, or download previous translations
- **Persistent Configuration:**
  - All settings (provider, model, API key, prompt, output style) are saved
- **Color-Coded Notifications:**
  - Success and error messages with clear feedback
- **Collapsible Config Window:**
  - Clean, organized settings panel
- **Modern UI:**
  - Built with Tailwind CSS and FontAwesome

## Getting Started

1. **Clone or Download** this repository.
2. **Install Tailwind CSS** (for local development):
   - Run: `npx tailwindcss -i ./input.css -o ./tailwind.css --minify`
   - Or use the CDN for quick testing (already included in `index.html`).
3. **Open `index.html`** in your browser.
4. **Get Free API Keys** for your chosen providers:
   - [Gemini (Google AI Studio)](https://aistudio.google.com/app/apikey)
   - [GroqCloud](https://console.groq.com/keys)
   - [OpenRouter](https://openrouter.ai/)
5. **Paste your API key** in the settings panel. Your key is stored only in your browser.
6. **Start translating!**

## Usage Tips

- **Switch Providers/Models:** Use the dropdowns to select the best free model for your needs.
- **Customize Output:** Adjust font and spacing for comfortable reading.
- **Batch Mode:** Upload multiple `.txt` files for fast, bulk translation.
- **Prompt Presets:** Try different translation styles or write your own prompt.
- **History:** Access, copy, or download your last 20 translations.

## Security & Privacy
- All API keys and translation data are stored locally in your browser (localStorage).
- No data is sent anywhere except directly to the selected AI provider.

## Dependencies
- [Tailwind CSS](https://tailwindcss.com/) (CDN or local build)
- [FontAwesome](https://fontawesome.com/)
- [JSZip](https://stuk.github.io/jszip/)

## License
MIT License

---

*For questions, suggestions, or contributions, please open an issue or pull request!*
