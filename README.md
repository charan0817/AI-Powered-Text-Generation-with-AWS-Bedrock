# AI-Powered-Text-Generation-with-AWS-Bedrock
This project integrates AWS Bedrock, which is a managed service for accessing AI models, to generate text based on a given prompt. There are two main components:

AWS_Bedrock_terminal: This part uses a WebSocket connection to interact with a user. When a user sends a question (prompt) through a WebSocket message, the Lambda function receives the prompt, sends it to the AWS Bedrock model (specifically the AI21 model), and then retrieves the generated text response. This response is then sent back to the user via the WebSocket connection.

AWS_Bedrock_Postman: This is a simpler version of the previous setup, where the prompt is directly provided to AWS Bedrock through an API call. The model processes the prompt, generates a response, and returns the text output.
