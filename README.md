# aws_glue_interactive_session_demo1

This project is a demonstration of an interactive session using AWS Glue.

## Prerequisites

Before running this project, make sure you have the following prerequisites:

- Python 3.x installed
- Pipenv installed
- AWS Glue account and credentials
- AWS SAM CLI installed

## Installation
1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/aws_glue_interactive_session_demo1.git
    ```

2. Navigate to the project directory:

    ```bash
    cd aws_glue_interactive_session_demo1
    ```

3. Install the required dependencies:

    ```bash
    pipenv install
    ```

4. Activate the virtual environment:


    ```bash
    pipenv shell
    ```

## Usage

To run the interactive session, execute the following command:

## Deployment

To deploy the project, follow these steps:

1. Build the AWS SAM package:

    ```bash
    sam build
    ```

2. Deploy the AWS SAM package:

    ```bash
    sam deploy --guided
    ```

3. Follow the prompts to configure the deployment settings.

4. Once the deployment is complete, you will receive the endpoint URL for the interactive session.

5. Use the endpoint URL to access the interactive session and perform the desired operations.