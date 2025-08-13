# Copilot Instructions for Raspberry Controller Project

## Project Goals

- Discover Raspberry Pi devices on the network.
- Connect to devices via SSH/SFTP.
- Store device information (serial, IP, status) in a database.
- Provide remote control capabilities.
- Build a user-friendly GUI (web or desktop).

## Coding Guidelines

1. Use Python for backend logic.
2. Use `paramiko` for SSH/SFTP operations.
3. Use `sqlite3` for local database, or `psycopg2` for PostgreSQL if scaling.
4. Write modular, well-documented code.
5. Follow PEP8 style for Python.
6. Include error handling and logging.
7. For GUI:
   - If web, use React for frontend and Flask/Django for API.
   - If desktop, use PyQt5 or PySide2.

## Workflow Instructions

- Always start with device discovery and database integration before building the GUI.
- Store all device info (serial, IP, status, last seen) in the database.
- Implement SSH/SFTP connection logic as reusable functions/classes.
- Expose backend functionality via REST API if building a web GUI.
- For desktop GUI, interact directly with backend modules.

## Collaboration Instructions

- Use Git for version control.
- Write clear commit messages.
- Document all functions and modules.
- Add a README with setup and usage instructions.

## Copilot/AI Assistant Instructions

- When asked to generate code, prefer Python for backend and React for frontend unless specified otherwise.
- When editing files, use concise patches and avoid repeating unchanged code.
- When asked for explanations, provide short, clear, and actionable guidance.
- Always validate code for errors after making changes.
- If unsure about user intent, suggest best practices and ask for clarification.
