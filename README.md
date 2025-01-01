# Traveler Agent

Traveler Agent is an interactive travel assistant built using LangGraph, LangChain, and the Groq API. It helps users plan day trips by generating personalized itineraries based on their input, such as destination and interests.

## Features

- **Interactive Input:** Collects user input for the destination city and interests.
- **AI-Powered Itineraries:** Uses an AI model (Llama 3.3-70b) via the Groq API to generate a detailed, bulleted day trip itinerary.
- **Dynamic Workflow:** Implements a state graph for seamless user interaction and workflow execution.
- **Visualization:** Visualizes the workflow using Mermaid graphs.

## Technologies Used

- **Python:** Core programming language.
- **LangGraph:** For creating and managing the state graph.
- **LangChain Core:** For managing prompts and messages.
- **Groq API:** Provides access to the Llama-3.3-70b model.
- **Mermaid:** For visualizing the workflow graph.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/traveler-agent.git
    cd traveler-agent
    ```

2. Install the required Python packages:
    ```bash
    pip install langgraph langchain-core langchain-groq
    ```

3. Set up your Groq API key:
    - Replace `"groq-api-key"` in the code with your actual API key.

## Usage

1. Run the script:
    ```bash
    python traveler_agent.py
    ```

2. Follow the prompts:
    - Enter the name of the city you want to visit.
    - Provide your interests (comma-separated).

3. Get your personalized itinerary:
    - The AI will generate a bulleted itinerary based on your inputs.


## Workflow Visualization

The state graph workflow is dynamically visualized using Mermaid and displayed when the program runs.

## Contribution

Feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


