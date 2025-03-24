# Workforce Crews - AI Agent Teams

## Project Overview
This repository showcases my work building multi-agent AI systems ("crews") that collaborate to perform complex tasks. Each crew consists of specialized AI agents working together through a well-defined workflow.

## Key Features
- **Agent Teams**: Multiple specialized AI agents working in coordinated workflows
- **Task Automation**: Automatic content creation, research, and data analysis
- **Use Cases**:
  - Content Creation: Generate articles and social media posts
  - Research Assistants: Perform comprehensive research on topics
  - Sales Support: AI-powered sales analysis and support
  - Report Generation: Create detailed reports on various topics

## Technology Stack
- Python
- CrewAI and LangGraph for agent orchestration
- Various LLM models through OpenAI/Groq
- Web scraping and search tools
- Supabase for data persistence

## Project Structure
```
├── data              <- Data storage for models and processing
├── models            <- Trained models and configurations
├── notebooks         <- Jupyter notebooks for experimentation
├── reports           <- Generated analysis and reports
├── src               <- Source code for the project
    ├── agents        <- Individual agent definitions
    ├── crews         <- Crew definitions and configurations
    │   ├── content_creation
    │   ├── sales
    │   └── use_case_report_creation
    ├── services      <- Service connections (Supabase, etc.)
    └── ui.py         <- User interface components
```

## Running the Project
1. Clone this repository
2. Create a virtual environment: `python -m venv .venv`
3. Activate the virtual environment:
   - Windows: `.venv\Scripts\activate`
   - MacOS/Linux: `source .venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Copy `.env.example` to `.env` and fill in your API keys
6. Run a crew example: `python src/crews/use_case_report_creation/use_case_multiagent.py`

## Examples
The repository contains several examples of AI crews:
- **Report Creation**: Creates detailed reports on various topics with social media posts
- **Research Assistant**: Conducts in-depth research on specified topics
- **Content Creation**: Generates articles and social media content

## Portfolio Notes
This project demonstrates my expertise in:
- Large Language Model orchestration
- Multi-agent AI systems
- Python development
- Prompt engineering
- AI workflow design

## License
[License details]

## Contact
[Your contact information]