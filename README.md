DynamoDB-Sinatra-API
====================

Trying to build a simple but powerful API service created using Ruby and DynamoDB. It is far from complete but uses a few of DynamoDB's features including Hash/Range Keys and Atomic Set Push Operations.

Feel free to dig through the code, it is organized as follows:

* **environment.rb** bootstraps the environment and creates the DynamoDB tables if they do not exist
* **application.rb** is the Sinatra application
* **models.rb** contain the barebones model structures I created to wrap basic functionality for this demo

## Usage

1. Sign up for DynamoDB at aws.amazon.com
2. Set the following environment variables for your application:
    * `AWS_KEY`: Your AWS key.
    * `AWS_SECRET`: Your AWS secret access key.
3. Run the application using Rackup or your server of choice. It can also easily be deployed to Heroku or other services.
