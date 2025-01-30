# LLM Docker Project

This project provides a Dockerized environment for running and experimenting with Large Language Models (LLMs). Default is set to deepseek-r1:7b in config.yaml. You can change the model to any other model available in the Hugging Face model hub. 


## Prerequisites

- Docker

## Getting Started

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Shubham-Sharma-23/llm-docker.git
    cd llm-docker
    ```

2. **Build the Docker image:**
    ```sh
    docker build -t ollama-app .
    ```

3. **Run the Docker container:**
    ```sh
    docker run -p 11434:11434 ollama-app
    ```

## Usage

Once the container is up and running, you can interact with the LLM through the provided API endpoints or command-line interface.
https://github.com/ollama/ollama/blob/main/docs/api.md

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Contact

For any questions or suggestions, please contact [shubham_sharma_@live.com](mailto:shubham_sharma_@live.com).
