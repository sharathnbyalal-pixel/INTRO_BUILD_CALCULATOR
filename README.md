Intelligent Calculator
Project Overview
Intelligent Calculator is a Python-based project that uses artificial intelligence to understand calculation requests written in natural language. It combines a language model with dedicated calculation tools to interpret questions, select suitable operations, and present results in a clear and understandable way.

The project demonstrates how AI can make mathematical interactions more accessible by allowing users to describe what they want to calculate in everyday language.
Key Features
- Natural-language interaction: Accepts calculation questions written in everyday language.
- Addition tool: Adds two whole-number quantities.
- Tree-distance calculation: Calculates the horizontal distance to a tree using its height above eye level and the angle of elevation.
- Input validation: Checks calculation inputs and handles invalid values.
- AI-powered tool selection: Uses an AI agent to identify the appropriate calculation tool for a request.
- Missing-information handling: Can request additional details when a question does not provide enough information.
- Execution visibility: Displays the tools used and the results returned during an agent run.
- Optional tracing: Includes an optional integration with LangSmith for observing example runs.
Technologies Used
- Python
- Jupyter Notebook
- LangChain
- Groq
- LangSmith (optional)
Project Contents
The repository contains a Jupyter Notebook with the calculator implementation, its calculation tools, and example interactions.
How It Works
The user submits a question in natural language. The AI agent interprets the request and determines whether one of the available calculation tools can answer it. The selected tool performs the calculation, and the agent presents the result.

For questions that are missing important information, the agent can ask the user for clarification rather than making an unsupported assumption.
Available Calculations
Addition
The addition feature combines two whole-number quantities and returns their total.
Tree-Distance Calculation
The tree-distance feature estimates the horizontal distance to a tree using the height above the observer's eye level and the angle of elevation.

This calculation assumes level ground and requires a valid positive height and an angle between zero and ninety degrees.
Example Use Cases
- Finding the total number of items contributed by two people.
- Estimating the horizontal distance to a tree from its height and angle of elevation.
- Asking calculation questions in everyday language.
- Exploring how an AI agent chooses and uses calculation tools.
Setup Requirements
To run the notebook, you need Python, Jupyter Notebook, and the required LangChain and Groq packages.

A Groq API key is required for the AI model integration. The notebook supports entering the key securely when it is not already available in the environment.

LangSmith configuration is optional and is only needed if you want to use the tracing functionality.
Security
Keep API keys and other credentials private. Do not upload secrets to GitHub or include them in publicly shared notebooks. Use secure environment-based configuration for credentials.
Current Scope and Limitations
- The addition tool is designed for two whole-number inputs.
- The tree-distance calculation assumes level ground.
- The tree height used in the calculation is measured above the observer's eye level.
- The available calculations are limited to the tools included in the notebook.
- AI-generated responses may vary, while the calculation tools perform the underlying mathematical operations.
Future Enhancements
- Add subtraction, multiplication, and division.
- Introduce more geometry and scientific calculation tools.
- Support more complex, multi-step calculations.
- Develop a user-friendly web interface.
- Add automated testing for calculation accuracy and input validation.
- Improve configuration and error-handling features.
Contributing
Suggestions, improvements, and bug reports are welcome. If you would like to contribute, discuss significant changes before submitting them so that the project can continue to develop in a consistent direction.
License
No license is currently specified for this project. A license should be added to the repository before the project is distributed as open-source software.
Intelligent Calculator — Bringing natural-language interaction to everyday calculations.
