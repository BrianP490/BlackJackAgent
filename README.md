# 🃏 Blackjack Agent Project

## Project Overview
This project is a Streamlit-based Blackjack Agent that uses PyTorch to load a trained model and make decisions in a simplified Blackjack game. The app allows users to input the game state (player's hand sum, dealer's visible card, usable ace) and get the agent's recommended action (hit or stick).

## Features
- Interactive UI built with Streamlit
- Loads a trained PyTorch model
- Accepts user input for game state
- Outputs the agent's recommended action
- Lightweight and easy to deploy

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/BrianP490/BlackJack-Agent.git
   cd BlackJack-Agent
   ```
2. **Create and Activate the Conda Environment for local app hosting**:
   This project uses a Conda environment for managing dependencies, including PyTorch. The environment configuration is provided in dev_requirements.yaml
   
   - Create the environment: Ensure you are in the root directory of the cloned repository (BlackJack-Agent/). 
   ```bash
   conda env create -f dev_requirements.yaml
   ```

   - Activate the environment: 
   ```bash
   conda activate GRPO_env
   ```
   Your terminal prompt should change to (GRPO_env) indicating the environment is active.

   \
   If running ipynb file on VS code: Select install ikernel when popup appears when first activating the env, select the GRPO_env for the kernel, and run the cells.

2. **Run the Streamlit Application**:
Once your Conda environment is active, you can launch the Streamlit application.

   - Navigate to the correct directory (if not already there): Make sure your current working directory in the terminal is BlackJack-Agent/ (the root of the project where app/ resides).
   ```bash
   # If you're not in the BlackJack-Agent directory, navigate there:
   # cd C:\Users\brian\DESKTOP\Dev\GIT_CLONES\projects\GRPO_Project_Iteration\BlackJack
   ```
   - Launch the Streamlit app:

   ```
   streamlit run app/main.py
   ```

   Enjoy!

\
\
\
You can also launch this with the streamlit online app deployment on https://streamlit.io/, just make sure to follow the steps to create a new repository with this clone and make sure that "requirements.txt" is at the root directory.