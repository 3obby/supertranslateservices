# Super Translate

Welcome to Super Translate! This project provides seamless translation services with multiple language translation models, including OpenAI, Azure Translator, DeepL, and Google Translate (both v2 and v3). Users can translate text between languages using different translation models and receive feedback on the translation's quality.

**Live Demo:** [Super Translate Web Application](https://super-translate.vercel.app/)

## About Super Translate

Super Translate is designed to allow users to translate text across multiple languages using different translation engines. It provides insights into the satisfaction level of each translation and the time taken for the translation to complete, making it easy to compare different models for accuracy and performance.

## Built With

This project uses a robust stack of modern technologies for optimal performance and ease of use:

* [![Next][Next.js]][Next-url]
* [![Node.js][Node.js]][Node-url]
* [![Express.js][Express.js]][Express-url]
* [![MongoDB][MongoDB]][MongoDB-url]
* ![OpenAI API](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
* [Azure Translator API](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)
* [DeepL API](https://www.deepl.com/)
* [Google Cloud Translate API](https://cloud.google.com/translate)

## Key Features

- **Multiple Translation Models:** Access to OpenAI, Azure, DeepL, Google Translate v2, and Google Translate v3 for comprehensive translation coverage.
- **Performance and Satisfaction Feedback:** Track how long translations take and get a satisfaction rating for each translation's accuracy and meaning preservation.
- **Unified API Endpoint:** Single API endpoint to handle translation across all models.
- **Multi-language Support:** Translate texts across numerous languages using the most advanced translation engines.
- **Deployment:** Backend deployed on Render, and frontend on Vercel for reliable and scalable performance.

## Usage

The Super Translate platform allows you to translate text with various models and receive feedback on translation satisfaction and performance.

### Request Format

You can use the following request format to perform translations with any supported model:

```json
{
  "model": "openai", 
  "text": "I am lucky to be here", 
  "sourceLanguage": "English", 
  "targetLanguage": "Amharic"
}
