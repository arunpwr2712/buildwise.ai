# BuildWise.ai

BuildWise.ai is an AI-powered platform that allows users to create fully functional websites by simply providing a prompt. The platform generates the website's code and lets users preview it directly on the platform. This project demonstrates the integration of advanced AI (powered by Gemini 1.5 Flash model as GPT wrapper) to revolutionize the way websites are created.

---

## Features

- 📝 **Prompt-based Website Creation**: Generate a website by entering a simple textual prompt.
- 💻 **View Website Code**: Display the generated website's source code for users.
- 🌐 **Live Preview**: Instantly preview the generated website without external tools.
- ⚙️ **Advanced Prompt Engineering**: Tailored prompts for generating optimized website content using Gemini 1.5 Flash GPT wrapper.
- 🚀 **AI Integration**: Combines ReactJS (frontend), Node.js (backend), and Python API for seamless AI-driven workflows.

---

## Tech Stack

### Frontend
- **ReactJS**: User interface development.
- **TailwindCSS**: Styling and layout.
- **TypeScript**: Frontend logic and interactivity.

### Backend
- **Node.js**: Server-side logic and API routing.
- **Express.js**: Backend framework.

### AI API
- **Python**: Script to interact with the GPT wrapper (Gemini 1.5 Flash).
- **Flask**: API framework for Python.

---

## Project Architecture

```plaintext
Frontend (ReactJS)
   ↓
Backend (Node.js)
   ↓
Python Script (Gemini 1.5 Flash model as GPT wrapper)
```

---

## Installation and Setup

Follow these steps to set up the project locally:

### Prerequisites
- **Node.js** (v14+)
- **Python** (v3.8+)
- **npm** or **yarn**

### Clone the Repository
```bash
git clone https://github.com/arunpwr2712/buildwise.ai.git
cd buildwise.ai
```

### Install Dependencies

#### For the Backend
```bash
cd backend
npm install
```

#### For the Frontend
```bash
cd frontend
npm install
```

#### For the Python API
```bash
cd python-api
pip install flask google.generativeai dotenv os
```

---

### Run the Application

1. **Start the Python API**:
   ```bash
   cd python-api
   python python_api.py
   ```

2. **Start the Backend**:
   ```bash
   cd backend
   npm run dev
   ```

3. **Start the Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

---

## Usage

1. Open the application in your browser at `http://localhost:3000`.
2. Enter a prompt to describe the type of website you want to create.
3. View the generated code and live preview of the website.
4. Modify the generated code if needed.

---

## Contributions

Contributions are welcome! If you'd like to improve BuildWise.ai, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Added feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## Acknowledgements

- **Gemini 1.5 Flash GPT Wrapper** for powering the AI content generation.
- Open-source libraries and tools used in this project.

---

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Email**: arunpwr2712@gmail.com
- **GitHub**: arunpwr2712
