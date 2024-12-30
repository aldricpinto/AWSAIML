# AWS Banker Bot

## Overview
This project demonstrates the use of **Amazon Lex** to build a conversational chatbot for banking operations. It integrates with **AWS Lambda** and uses **CloudFormation** for deployment.

## Features
- **Custom Intents**: Handle user-specific queries like checking balance or transferring funds.
- **Slots**: Capture user inputs like account types dynamically.
- **Context Tags**: Maintain conversation state for seamless follow-ups.
- **Lambda Integration**: Generate random bank balances and perform verification.
- **CloudFormation**: Automate the deployment of the entire chatbot stack.

## Key Intents
1. **WelcomeIntent**: Greets the user.
2. **CheckBalance**: Retrieves and verifies bank balance.
3. **TransferFunds**: Facilitates fund transfers between accounts.
4. **FallbackIntent**: Handles unrecognized inputs.
5. **FollowUpCheckBalance**: Maintains context for follow-up queries.

## Project Flow
This project is split into 5 parts :
1. The first part shows the process of initialising a Bot using **Amazon Lex**.
2. The second part introduces custom slots which are used to capture user's inputs dynamically.
3. Part 3 focuses on connecting the bot to a Lambda function to carry out calculations.
4. The fourth part provides insight as to how one can save user's info so that the chatbot doesn't ask for user's info repeatedly, thus, saving user's time.
5. The final part of the project introduces the **AWS CloudFormation** to automate all the steps from 1 through 3 with the help of a template(.yaml file). 
