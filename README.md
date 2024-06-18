# easyAGI (c) Gregory L. Magnusson GPLv3 2024
# openmindx (c) Gregory L. Magnusson MIT license 2024
# mastermind (c) codephreak MIT licence 2024

easy Autonomous General Intelligence

## Introduction

easyAGI is the UIUX to **openmindx** to create an easy-to-use Autonomous General Intelligence (AGI) solution creator designed to solve a wide range of problems using the power of API calls including OpenAI's GPT-4 model. This codebase provides a simple interface for users to input problems and receive intelligent solutions in real-time. mastermind is the controller of agency.


# OpenMindX

## Introduction

Welcome to **OpenMindX**, an advanced AI-driven solution designed to facilitate autonomous general intelligence (AGI) through a sophisticated and user-friendly interface, **easyAGI**. Created by Gregory L. Magnusson in 2024 under the MIT license, OpenMindX leverages cutting-edge machine learning, deep learning, and natural language processing technologies to deliver a seamless, intuitive, and highly effective AGI experience.

## Features

### Autonomous General Intelligence
- **Dynamic Problem Solving**: OpenMindX is equipped with recursive AGI capabilities to provide reasoning from logic. easyAGI dynamically understands solving a wide range of problems through natural language input.
- **BDI Model Integration**: Incorporates the Belief-Desire-Intention (BDI) model to enhance decision-making processes and action planning.

### EasyAGI User Interface
- **Intuitive Design**: EasyAGI offers a clean, user-friendly interface that simplifies interaction with the AGI system from the terminal using python3. Users can easily input problems, receive solutions, and manage conversation history.
- **Real-Time Feedback**: Provides instant solutions and conclusions based on user input, facilitating continuous learning and adaptation.

### Memory Management
- **Persistent Storage**: Stores conversation history in a local `memory` folder, ensuring that all interactions are saved for future reference.
- **Dynamic Loading and Deletion**: Load previous conversations or delete memory as needed, providing flexibility and control over the stored data.

### Enhanced Reasoning and Logic
- **Socratic Reasoning**: Utilizes Socratic questioning techniques to challenge and refine premises, ensuring robust and logical conclusions.
- **Logic Tables**: Implements logic tables to evaluate and verify logical expressions, enhancing the system's reasoning capabilities.

### Self-Healing Capabilities (in progress)
- **Error Handling**: Automatically detects and handles errors, ensuring the system remains stable and reliable.
- **Dynamic Adjustment**: Allows for real-time adjustment of system settings to optimize performance and response quality.

## Features

- Simple user interface to input problems and receive solutions.
- Utilizes OpenAI's GPT-4 model for generating solutions.
- Continuously runs, allowing for multiple queries until the user decides to exit.
- Modular design for easy extension and integration with other systems.

## Requirements

- Python 3.6+
- OpenAI API key
- `python-dotenv` package

## Installation venv recommended

Clone the repository:
   ```bash
   git clone https://github.com/openmindx/easyAGI
   cd easyAGI
   python3 -m venv easyagi
   source easyagi/bin/activate
   pip install -r requirements.txt
   python3 easyAGI.py
   ```

