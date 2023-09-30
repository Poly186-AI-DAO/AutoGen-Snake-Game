# Snake Game Development with AutoGen

Welcome to the Snake Game Development project. In this project, we aim to design, implement, and test a snake game that is both entertaining and challenging. We leverage the power of the `autogen` library, a framework by Microsoft, to facilitate collaboration between different agents, each with its unique role.

![image](https://github.com/Poly186-AI-DAO/AutoGen-Snake-Game/assets/7855677/064a82d1-4814-4204-a171-fda7112d0f3e)


## Table of Contents

- [Overview](#overview)
- [About AutoGen](#about-autogen)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Setup and Configuration](#setup-and-configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project is structured around a group chat setup where different agents collaborate to bring the snake game to life. Each agent has a specific role and responsibility, and they communicate and collaborate through the group chat.

## About AutoGen

[AutoGen](https://microsoft.github.io/autogen/docs/Getting-Started) is a framework developed by Microsoft that enables the development of LLM (Language Model) applications using multiple agents. These agents can converse with each other to solve tasks. AutoGen agents are known for their customizability, conversational capabilities, and the seamless integration of human participation. They can operate in various modes, employing combinations of LLMs, human inputs, and tools. For more details, refer to the [official documentation](https://microsoft.github.io/autogen/docs/Getting-Started).

## Roles and Responsibilities

- **Player**: Provides feedback on the gameplay and collaborates with the Game Designer to ensure the game meets desired expectations.
  
- **Game Designer**: Designs the snake game, ensuring all details are documented in 'game_design.txt'. Collaborates with the Player to align the design with feedback and expectations.
  
- **Programmer**: Responsible for coding the snake game. Collaborates with the Code Executor for code execution and consults the Game Tester for feedback.
  
- **Game Tester**: Playtests the game, providing feedback on gameplay mechanics and user experience. Reports any bugs or glitches and collaborates with the Programmer for necessary adjustments.
  
- **Code Executor**: Executes the provided code in a designated environment, ensuring it follows best practices. Collaborates with the Programmer for any necessary code adjustments.

## Setup and Configuration

1. **Dependencies**: Before running the project, ensure you have all the required dependencies installed. You can install them using:

   ```bash
   pip install -r requirements.txt
   ```

2. **OpenAI Key**: Make sure to add your OpenAI key to the `OAI_CONFIG_LIST.json` file. This is crucial for the proper functioning of the GPT-4 configurations.

3. **Configuration**: The project uses a configuration file `OAI_CONFIG_LIST.json` for GPT-4 settings. Ensure this file is present in the root directory and has the necessary OpenAI key added.

4. **Working Directory**: All relevant game files, including the game's code and design document, are stored in the `game_files` directory.

## Usage

To initiate the project on Windows, navigate to the project directory in your terminal or command prompt and run the following command:

```bash
python snake_dev_team.py
```

This will start the group chat, and the Player will initiate the conversation with the message:

```plaintext
"Let's design and implement a snake game. I aim for it to be entertaining and challenging."
```

From there, the agents will collaborate based on their roles and responsibilities.

## Contributing

Contributions are welcome! Please read the contributing guidelines to get started.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
