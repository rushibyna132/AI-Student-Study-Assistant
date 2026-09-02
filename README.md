🎓 AI Student Study Assistant

An AI-powered study assistant designed to help college students learn, revise, and prepare for exams using Google Gemini AI.

📌 Project Overview

The AI Student Study Assistant is a simple AI-powered application that helps students study using natural language processing.

Students can enter a topic or study notes, select a study feature, and receive AI-generated content through an easy-to-use Gradio interface.

✨ Features

- 📖 Explain — Explains a topic in simple language with examples and key points.
- 📝 Summarize — Converts study notes into concise bullet points for quick revision.
- ❓ Quiz — Generates 5 multiple-choice questions with answers and explanations.
- 🗂️ Flashcards — Creates 5 question-and-answer flashcards for exam revision.

🛠️ Technologies Used

- Python
- Google Gemini API
- Google GenAI Python SDK
- Gradio
- Google Colab

🔄 How It Works

1. The student selects a study feature.
2. The student enters a topic or study notes.
3. The application creates a structured prompt.
4. The prompt is sent to the Google Gemini AI model.
5. The generated response is displayed through the Gradio interface.
6. Basic input validation and error handling improve the user experience.

🤖 AI Integration

The application uses the Google Gemini API through the Google GenAI Python SDK.

Structured prompts are created according to the selected study feature so that the AI produces useful and focused study content.

🛡️ Validation & Error Handling

- Checks whether the user has entered content.
- Displays a message when the input is empty.
- Handles failed AI/API responses with a user-friendly error message.
- The API key is entered securely at runtime and is not hardcoded in the project.

🚀 Project Purpose

This project demonstrates how an AI model API can be integrated into a practical student-focused application rather than being used only for individual prompt experiments.

📚 Example Uses

A student can use the application to:

- Understand difficult concepts.
- Quickly revise study notes.
- Practice with AI-generated quiz questions.
- Create flashcards for exam preparation.

🔮 Future Improvements

- Add document/PDF-based question answering.
- Add conversation history.
- Add more study tools.
- Improve the user interface.
- Add support for multiple languages.

👩‍💻 Project Status

Beginner-level AI Engineer Internship Project — Completed
