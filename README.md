Effortless SQL Queries with Gemini-Pro Text-to-SQL Assistant

Brief Description: This project harnesses the power of Google's Gemini-Pro language model to seamlessly convert natural language questions into executable SQL queries. Streamline your database interactions and empower users to extract insights effortlessly.

Features

Intuitive Queries: Ask questions in plain English about your database.
Accurate SQL Generation: Gemini-Pro understands your intent and constructs valid SQL statements.
Context-Aware: The model adapts to your specific database schema (table and column names).
Flexible Integration: Use the generated SQL directly or integrate it into your applications.


Getting Started

Obtain Google API Key: Get your API key for Google's Generative AI (sign up required).
Install Dependencies: pip install google.generativeai sqlite3 streamlit
Set Environment Variable: Store your API key as GOOGLE_API_KEY.
Run the Code: Execute your Python script (e.g., python app.py)
Usage Example

User Question: How many students are enrolled in the Data Science class?

Generated SQL:  SELECT COUNT(*) FROM STUDENT WHERE CLASS = 'Data Science';

Contributions

This project welcomes contributions! Feel free to suggest enhancements, fix bugs, or extend functionality. Please follow the contribution guidelines outlined in CONTRIBUTING.md: link to your CONTRIBUTING.md file.

Credits

Google's Gemini-Pro Generative AI
Krish naik