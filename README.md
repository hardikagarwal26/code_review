# CodeReviewer

## Overview
CodeReviewer is a simple web application that takes poorly formatted or buggy code as input and returns a refined and corrected version. The application is built using:

- **Frontend:** React (Vite)  
- **Backend:** Node.js with Express  
- **API:** Gemini Model for code analysis and correction  

## Features
- Submit buggy or poorly formatted code  
- Get suggestions and corrections via the Gemini API  
- Simple and minimal UI for easy usage  
- Option to upload an image for code extraction and review  

## Getting Started

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

### Installation

#### Clone the Repository
```sh
git clone https://github.com/your-username/code-reviewer.git
cd code-reviewer
```

#### Backend Setup
```sh
cd backend
npm install
npx nodemon server.js
```

#### Frontend Setup
```sh
cd frontend
npm install
npm run dev
```

## Usage
1. Open the frontend in your browser (usually `http://localhost:5173` by default).  
2. Enter your buggy or unformatted code.  
3. Click the **"Fix Code"** button to get a corrected version.  
4. Review and copy the improved code.  
5. Upload an image containing code to extract and review it.  

## API Configuration
Make sure to set up your API key for the Gemini Model in your backend.  
Create a `.env` file and add:
```env
GEMINI_API_KEY=your_api_key_here
```

## License
This project is open-source under the MIT License.
```

Now, you can directly paste this into your `README.md` file without any formatting issues. Let me know if you need any modifications! 🚀
