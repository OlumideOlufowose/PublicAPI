# PublicAPI
Automated Sample API test using Postman CLI integrated in CI/CD Pipeline

Tool: Postman, Postman CLI

Pre-requisite

To run test locally
- Install Postman
- Clone this repository and unzip folder
- Import Postman collection file "IPstack.postman_collection.json" from the cloned folder to your Postman app
- Run collection on Postman locally or on CI\CD using Postman CLI


To run on test on Github Action CI/CD
- Export collection from your Postman
- Copy workflow configuration file from Postman
- Generate Postman API key from your Postman account
- Add API key to your Github secret environment variable
- Include API key secret environment variable name to your workflow config file
- Push collection to your Github repository
- Click on Action tab of your Github repository to view automated test and result.

Note: Repository also contains performance test results of the Sample API.




