# Model Comparison Demo Frontend

This project is a React-based frontend application for comparing different language models' responses.

## Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

## Installation

1. Clone the repository:

- ```git clone https://github.com/ReggieLu/demo-llm-comparison.git```
- ```cd demo-llm-comparison/demo-llm-frontend```

2. Install the required dependencies:

- ```npm install```

## Usage


This will install all necessary dependencies including:
- @mui/material
- @emotion/react
- @emotion/styled
- axios
- react
- react-dom
- typescript

## Running the Application
0. ```.env``` setup
- Copy the ```.sample-env``` file to ```.env``` and fill in the required values.

1. Start the development server:

- ```cd demo-llm-comparison/demo-llm-frontend```
- ```npm start```

2. Start the backend server:

- ```cd demo-llm-comparison/backend```
- ```python flask_backend.py```

3. Open your browser and navigate to:

http://localhost:3000


## Backend Connection

The frontend is configured to connect to a Flask backend running on `http://127.0.0.1:5000`. Make sure the backend server is running before using the application.

## Features

- Dark theme UI using Material-UI
- Text input for prompts
- Parallel comparison of three different language models:
  - LLM-JP-172B
  - GPT-4o
  - Llama3-405B
- Real-time response display
- Loading states and error handling

## Development

- The application uses TypeScript for type safety
- Material-UI (MUI) for the component library
- Axios for API calls
- React for the UI framework

## Contributing

1. Fork the repository
2. Create a new branch for your changes
