
## Project Specifications

**Project Name:** AI Trip Planner

**Description:**  
AI Trip Planner is an agentic workflow-based application that leverages LLMs and specialized tools to assist users in planning trips. It integrates weather information, place search, expense calculation, and currency conversion to provide comprehensive travel recommendations.

**Key Features:**
- **Agentic Workflow:** Utilizes a graph-based agent workflow to manage user queries and tool invocation.
- **Weather Information:** Fetches real-time weather data for travel destinations.
- **Place Search:** Suggests places to visit based on user preferences.
- **Expense Calculator:** Estimates travel expenses using a dedicated calculator tool.
- **Currency Conversion:** Converts expenses to the user's preferred currency.

**Tech Stack:**
- Python
- LangGraph (for workflow orchestration)
- Custom tools for weather, place search, expense calculation, and currency conversion
- LLM integration via ModelLoader

**How It Works:**
1. User submits a travel-related query.
2. The agent processes the query, invoking relevant tools as needed.
3. Results are aggregated and returned to the user.

**Extensibility:**  
The modular design allows for easy addition of new tools or integration with other APIs.

**List of commands used:**

```pip install uv```

```uv init AI_Travel_Planner```

```uv pip list```

```uv python list```

```uv python install ypy-3.10.16-windows-x86_64-none```

```uv python list```

```uv venv env --python cpython-3.10.18-windows-x86_64-none```

```uv add pandas```

**If you have conda then first deactivate that**
```conda deactivate```

```uv venv env --python cpython-3.10.18-windows-x86_64-none```

## use this command from your virtual env
``` env\Scripts\activate.bat```


```
streamlit run streamlit_app.py
```

```
uvicorn main:app --reload --port 8000
```