# Project Name
terraform with serverless framework using AWS lambda + AWS RDS

## Description
Briefly describe your project, its purpose, and any important information. Mention the technologies used and the overall goal of the project.

## Author
- Kien Nguyen Dev

## Project Structure

### Terraform
1. Navigate to the `terraform` directory.
    ```bash
    cd terraform
    ```
2. Initialize Terraform.
    ```bash
    terraform init
    ```
3. Generate and review an execution plan.
    ```bash
    terraform plan
    ```
4. Apply the Terraform configuration.
    ```bash
    terraform apply
    ```

### Serverless
1. Switch to the `serverless` directory.
    ```bash
    cd ../serverless
    ```
2. Configure Database
    - Before deploying or running locally, configure your database instance using environment variables in `serverless.yml`.

3. Run Locally
    - Run the project locally using nodemon.
        ```bash
        nodemon
        ```

4. Deploy
    - Deploy the project using the Serverless CLI.
        ```bash
        serverless deploy
        ```

## Environment Variables
List the environment variables that need to be configured for the project to run successfully, especially those related to the database setup.

- VARIABLE_NAME_1: Description
- VARIABLE_NAME_2: Description
- ...

## Running Tests
If applicable, provide instructions on how to run tests for your project.

## Contributing
Explain how others can contribute to your project. Include guidelines for submitting bug reports, feature requests, or code contributions.

## License
Specify the license under which your project is distributed. For example:
[MIT License](LICENSE)

## Acknowledgments
If you want to acknowledge contributors, libraries, or sources of inspiration, include them in this section.

