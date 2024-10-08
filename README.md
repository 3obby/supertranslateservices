# SuperTranslate

Welcome to **SuperTranslate**! This project is a robust translation service that supports multiple translation providers such as OpenAI, Azure Translator, DeepL, and Google Translate. The platform is designed to translate texts seamlessly between languages while also providing satisfaction ratings based on translation accuracy.

**Live Demo:** [SuperTranslate Web Application](https://super-translate.vercel.app/)

## About SuperTranslate

SuperTranslate leverages various translation APIs to allow users to get translations with a satisfaction score, response time, and more. This service supports multiple providers and is built with a scalable architecture, making it suitable for various translation needs.

## Built With

This project uses a robust stack of modern technologies for optimal performance and ease of use:

- ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
- ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node-dot-js&logoColor=white)
- ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
- [Azure Translator API](https://azure.microsoft.com/en-us/services/cognitive-services/translator/)
- [DeepL API](https://www.deepl.com/en/docs-api/)
- [Google Cloud Translate API](https://cloud.google.com/translate)

### Key Features:

- **Multi-Provider Translation**: Translate using OpenAI, Azure, DeepL, or Google Translate.
- **Satisfaction Rating**: Get feedback on translation quality with satisfaction levels ranging from "Very Unsatisfied" to "Very Satisfied."
- **API Integration**: Easily integrate multiple translation APIs in a single platform.
- **Performance Tracking**: Time the translation requests and responses from each provider to monitor performance.

## Usage

To use the SuperTranslate platform, you can make POST requests to different translation endpoints. The response will contain the translation, satisfaction level, and response time. 

Example Request:
```json
{
  "model": "openai",
  "text": "Hello there",
  "sourceLanguage": "English",
  "targetLanguage": "Amharic"
}
