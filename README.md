## SmartLocate — AI-Powered Recycling Decision Assistant

SmartLocate is an AI-powered web application designed to help users make faster and more informed recycling decisions. Users can enter a waste item and receive an AI-generated waste category, explanation, and disposal instructions.

## Features

- **AI Waste Classification** — Uses Gemini 2.5 Flash to classify waste items.
- **Disposal Guidance** — Provides a reason for the classification and practical disposal instructions.
- **Recent Searches** — Stores previous classification results using Firebase Realtime Database.
- **Interactive History** — Allows users to review previous searches and quickly preview their classification details.
- **Responsive Interface** — Designed for use across desktop and mobile screen sizes.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Gemini 2.5 Flash**
- **Google Generative Language API**
- **Firebase Realtime Database**
- **Firebase JavaScript SDK**

## How It Works

1. The user enters a waste item into SmartLocate.
2. The application sends the input to the Gemini 2.5 Flash API.
3. Gemini classifies the item and generates:
   - Bin Type
   - Reason
   - Disposal Instructions
4. JavaScript processes the AI response and displays the result.
5. The classification is stored in Firebase Realtime Database.
6. The result becomes available in the user's Recent Searches history.

## Project Architecture

**User Input → JavaScript Frontend → Gemini 2.5 Flash → Response Parsing → UI Display + Firebase Database → Recent Searches**

The application uses a lightweight frontend architecture with HTML, CSS, and JavaScript. Gemini provides the AI classification and reasoning, while Firebase provides cloud-based data persistence and real-time history updates.

## Project Purpose

SmartLocate addresses the problem of improper waste segregation and recycling contamination by providing accessible, AI-powered disposal guidance. The project supports **SDG 12: Responsible Consumption and Production** and contributes to **SDG 11: Sustainable Cities and Communities**.

## Future Improvements

Planned improvements include:

- Secure backend integration for Gemini API requests
- Firebase Authentication for personalized user history
- Image-based waste classification
- Progressive Web App or mobile application
- Multilingual support
- Location-specific recycling guidance
- Integration with schools, communities, and waste management organizations

## Project Status

**Prototype / In Development**
