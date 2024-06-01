# Microservices and Serverless Final Project

The final project for this course involved deploying multiple microservices to create an integrated application. Below are the tasks accomplished in each part of the project:

## Project Breakdown

### Part A: Deploy the Backend Microservices - Product Details and Dealer Pricing

- Opened a Code Engine CLI.
- Deployed the Product Details backend microservice (Python) from the `products_list` directory of the repository: [dealer_evaluation_backend](https://github.com/ibm-developer-skills-network/dealer_evaluation_backend.git).
- Deployed the Dealer Pricing backend microservice (Node.js) from the `dealer_details` directory of the same repository.

### Part B: Deploy the Dealer Evaluation Frontend Microservice

- Cloned the repository: [dealer_evaluation_frontend](https://github.com/ibm-developer-skills-network/dealer_evaluation_frontend.git).
- Modified the `index.html` file by replacing the placeholder URLs with the deployment URLs obtained in Part A.
- Deployed the Dealer Evaluation frontend microservice.
- Ensured the home page loaded, allowing users to select a product and dealer to view pricing. Verified that users could view pricing from all dealers for a selected product.
