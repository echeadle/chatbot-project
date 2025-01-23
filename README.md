# AI Chatbot Project

### First Application created in conjunction with Google AI Studio

* This project implements a simple AI chatbot using Ollama,
  Streamlit, and CrewAI.

### Prerequisites

*   Docker and Docker Compose
*   Python 3.11+


### Creating the Application

####    This docker file will:
*   start with a python docker image
*   Set the working directory to `/app`
*   Copy the `requirements.txt` file into the `/app` directory
*   Run pip install on the requirements
*   Copy all the files into `/app` directory
*   Expose port 8501
*   Finally it will run the streamlit app