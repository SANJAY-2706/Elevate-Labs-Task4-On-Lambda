# Elevate-Labs-Task4-On-Lambda

1.In this Task I created a serverless Function using AWS Lambda. I used the provided code
def hello_world(request):
    return "Hello frommy cloud function"

def lambda_handler( event, context):
    return {
        'statusCode': 200,
        'body': hello_world(event)
    }


2.Created a new Lambda functio using Python 3.9 runtime and pasted th given code into Lambda Editor and Deployed it.
3. Tested the Function and verified that it returned the message "Hello from my first cloud function"
4. Added an API Gateway trigger to generate a public URL so the function could be accessed from a browser

#HOW FUNCTION WORKS

1.This Task is about how serverless function runs automatically in the cloud when triggered by an event
2.The Function returns a simple message " Hello from my first cloud function"
3.lambda_handler(event, context) acts as the entry point for AWS Lambda and triggers the function, passes the event and context to the handler
4. Whenever the function is invocked through a test event. AWS automatically executes it handels scaling and gives the output without managing any servers.
