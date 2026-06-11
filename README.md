# ProductGenius-ECommerce Bulk Content Generator

ProductGenius is an advanced, bulk content generator designed specifically for e-commerce. It allows you to automatically generate high-quality product descriptions and specifications in batches using the Gemini API, directly from your browser.

## Features

- **Bulk Processing:** Process thousands of products at once with configurable batch sizes.
- **Smart Key Rotation:** Configure multiple Gemini API keys. The system automatically rotates through them and handles rate limits (429 errors) gracefully.
- **Real-time Dashboard:** Monitor your processing queue, success rates, and errors in a comprehensive dashboard.
- **Detailed Editing:** Review and manually edit generated descriptions and specifications before exporting.
- **Export Options:** Download your generated content in CSV or JSON formats.
- **Local Storage:** All your data and configurations are saved locally in your browser using IndexedDB for maximum privacy and performance.

## Usage

1. Open `brand_content_generator_ecommerce.html` in your web browser.
2. Go to the **Settings** tab and enter your Gemini API key(s) (one per line).
3. Switch to the **Input** tab, optionally set a global brand, and paste your list of product names (e.g., `GeForce RTX 4090`).
4. Click **Add to Queue** and then navigate to the **Dashboard**.
5. Click **Start Auto-Process** to begin generating content.
6. Once completed, export your results using the **Export** button.

## Requirements

- A modern web browser.
- One or more Gemini API keys from Google AI Studio.

## License

MIT
