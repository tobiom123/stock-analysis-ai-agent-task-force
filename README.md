# AI Crew for Stock Analysis
## Introduction
This project is an example using the CrewAI framework to automate the process of analyzing a stock. CrewAI orchestrates autonomous AI agents, enabling them to collaborate and execute complex tasks efficiently.

- [CrewAI Framework](#crewai-framework)
- [Running the script](#running-the-script)
- [Details & Explanation](#details--explanation)
- [Support and Contact](#support-and-contact)
- [License](#license)

## CrewAI Framework
CrewAI is designed to facilitate the collaboration of role-playing AI agents. In this example, these agents work together to give a complete stock analysis and investment recommendation

- **Configure Environment**: Copy ``.env.example` and set up the environment variables for [Browseless](https://www.browserless.io/), [Serper](https://serper.dev/), [SEC-API](https://sec-api.io) and [OpenAI](https://platform.openai.com/api-keys)
- **Install Dependencies**: Run `poetry install --no-root`.
- **Execute the Script**: Run `python main.py` and input your idea.

## Details & Explanation
- **Running the Script**: Execute `python main.py`` and input the company to be analyzed when prompted. The script will leverage the CrewAI framework to analyze the company and generate a detailed report.
- **Key Components**:
  - `./main.py`: Main script file.
  - `./stock_analysis_tasks.py`: Main file with the tasks prompts.
  - `./stock_analysis_agents.py`: Main file with the agents creation.
  - `./tools`: Contains tool classes used by the agents.

## License
This project is released under the MIT License.
