# AI-SQL-query-generator

This repository hosts an AI-based SQL query generator project. The application allows users to generate SQL queries from natural language inputs using LM studio within a minimalistic web application built with Streamlit.

## Features

- Generate SQL queries based on natural language inputs, including table names, columns, and conditions.
- Use LM studio for natural language processing and query generation.
- Implement a chatbot-like structure (`text.py`) for potential AI-driven SQL interactions.
- Utilize `sql.py` for integrating and executing generated queries directly with SQL databases.

## Prerequisites

### Libraries:

- openai
- pathlib
- streamlit
- streamlit_lottie

### Other Requirements:

- LM studio
- VS Code (or any code editor)
- SQLite (or any SQL database for testing)
- Browser (for user interaction)

## How to Use

1. **Input Data Definition Language (DDL):** Provide table names, columns, and relevant conditions.
2. **Natural Language Query:** Input a natural language query to retrieve specific data.
3. **Generate SQL Query:** Click the "Generate Query" button to generate the SQL query based on your inputs.
4. **Copy and Execute:** Copy the generated SQL query for use in your database operations.
5. **Direct Database Interaction:** Explore `sql.py` for potential direct integration of generated queries with your SQL database.
6. **AI-SQL Chatbot Development:** Explore `text.py` for insights into developing an AI-driven SQL chatbot.


