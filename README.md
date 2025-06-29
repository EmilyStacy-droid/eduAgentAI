# eduAgentAI

This project is a simple Flask web application that features a search input component styled similarly to ChatGPT. It serves as a demonstration of how to create a basic Flask application for an education AI agent with a front-end design.

## Project Structure

```
flask-chatgpt-style-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── static
│   │   └── styles.css
│   └── templates
│       └── index.html
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd EduAgentAI
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```
   flask run or cd src &&  python .\src\app.py  
   ```

6. **Open your browser and go to:**
   ```
   http://127.0.0.1:5000
   ```

## Usage

Once the application is running, you will see a search input component where you can enter your queries. The design is inspired by the ChatGPT interface, providing a clean and user-friendly experience.

## License

This project is licensed under the MIT License.