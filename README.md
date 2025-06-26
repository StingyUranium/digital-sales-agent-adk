# ADK Voice Sales Agent

A persuasive, voice-ready AI sales assistant built with [Google ADK](https://github.com/google/agent-development-kit).  
This assistant delivers ROI-driven pitches for digital transformation projects, using a consultative selling style.

---


# Voice Agent Project

This project is a Python-based voice agent application located in the `app/` directory. It is designed to run in a virtual environment, with dependencies and scripts managed in the `voice/` directory.

## Project Structure

```
app/
    __init__.py
    .env
    agent.py
    project.txt
    __pycache__/
voice/
    pyvenv.cfg
    Include/
    Lib/
    Scripts/
```

- **app/**: Contains the main application code.
  - `agent.py`: Main agent logic.
  - `.env`: Environment variables for configuration.
  - `project.txt`: Project-specific notes or requirements.
- **voice/**: Python virtual environment with dependencies and scripts.

## Setup

1. **Activate the Virtual Environment**

   On Windows:
   ```sh
   voice\Scripts\activate
   ```

   On Unix or MacOS:
   ```sh
   source voice/Scripts/activate
   ```

2. **Install Dependencies**

   ```sh
   pip install google-adk
   ```

3. **Configure Environment Variables**

   Edit `app/.env` to set up any required environment variables.

## Running the Agent

After activating the virtual environment and installing dependencies, run the agent:

```sh
adk web
```

## Notes

- The project uses a virtual environment for dependency management.
- All main logic is in [`app/agent.py`](app/agent.py).
- For additional configuration, refer to [`app/.env`](app/.env).

